# what animal are you?
public class Animal{
	private String color;
	private String size;
	private String name;
	private String height;
	private String weight;
	
	public Animal(){
	}
	
	public Animal(String name,String color,String size,String height,String weight) {
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
	public String getheight(){
		return height;
	}
	public void setheight(String height){
		this.height=height;
	}
	public String getweight(){
		return weight;
	}
	public void setweight(String weight){
		this.weight=weight;
	}
	
	public class Wolf extends Animal{
		private String eyescolor;
		public Wolf(){
		}
		public Wolf(String eyescolor){
			this.eyescolor=eyescolor;
		}
		public String geteyescolor(){
			this.eyescolor=eyescolor;
		}
		public String seteyescolor(){
			return eyescolor;
		}
	}
}
