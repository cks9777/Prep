# Prep

class Apple
{

    public void eat() {
  
    System.out.println("See, he is eating apple");
  
    }
}
  
public class OverrideEx extends Apple
{
  public static void main(String[] args){
  
    OverrideEx ov=new OverrideEx();
    ov.eat();
    add(2,3);
    ov.add(2,3,5);
  }
  
   public static void add(int i,int j){
        System.out.println("The summation of two integer is "+(i+j));
    }
    public void add(int i,int j,int k){
        System.out.println("The summation of three integer is "+(i+j+k));
    }
}
