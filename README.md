# Prep
Prep for call &amp; initializing with README

class Apple{
  public void eat() {
  
  System.out.println("See he is eating apple");
  }
  
public class OverrideEx extends Apple
{
  public static void main(String[] args){
  
    OverrideEx ov=new OverrideEx();
    ov.eat();
  }
}
