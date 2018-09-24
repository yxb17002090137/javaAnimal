# what animal are you?
public class Animal{
	private String color;
	private String size;
	private String name;
	
	public Animal(){
	}
	
	public Animal(String name,String color,String size) {
		this.name=name;
		this.color=color;
		this.size=size;
	}
	public String getColor() {
		return color;
	}
	public void setColor(String color) {
		this.color=color;
	}
	public String getsize() {
		return size;
	}
	public void  setsize(String size) {
		this.size=size;
	}
	public String getname() {
		return name;
	}
	public void  setname(String name) {
		this.name=name;
	}
}
