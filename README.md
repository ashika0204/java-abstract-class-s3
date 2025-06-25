# java-abstract-class-s3
abstract class shape
{
    abstract void numberofsides();
}
class rectangle extends shape
{
    void numberofsides()
    {
        int l,b;
        double area1;
        Scanner sc=new Scanner(System.in);
 System.out.println("enter the length and breadth of rectangle");
        l=sc.nextInt();
        b=sc.nextInt();
        area1=l*b;
        System.out.println("area of rectangle"+area1);
   System.out.println("the number of sides of rectangle is 4");
    }
}
