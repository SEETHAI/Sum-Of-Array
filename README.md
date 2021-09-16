# Sum-Of-Array
Java program to find the Sum Of Array
public class SumOfArray {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args)
    {
        int[] arr=new int[]{1,2,3,4,5};
       
             int sum=0;
               for(int i=0; i<arr.length;i++) {
           sum=sum+arr[i];
                }
                  System.out.println("Sum of all the elements of an rry:"+sum);
               
                }
