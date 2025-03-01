class Addition{
    public void add(int a,int b){
        System.out.println("method of parent"+(a+b));
    }
}
class EOC extends Addition{
    public void add(int a,int b){
        System.out.println("method of child"+(a+b));
    }
}
public class Run{
    public static void main(String args[]){
        EOC obj1=new EOC();
       obj1.add(4,9);

    }
}# firstproject
