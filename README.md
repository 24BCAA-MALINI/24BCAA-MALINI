public class TrignometryApproximation
{
public static void main(String[]args)
{
double theta=Double.parseDouble(args[0]);
double sinSquaretheta=Math.sin(theta)*Math.sin(theta);
double cosSquaretheta=Math.cos(theta)*Math.cos(theta);
double result=sinSquaretheta+cosSquaretheta;
boolean isApproximateone=(result==1);
System.out.println(isApproximateone);
}
}
