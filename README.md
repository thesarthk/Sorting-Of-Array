# Sorting-Of-Array
// Sort the  without using java Method
// In Increasing Order
public class Sorting_of_Array {
    public static void main(String[] args) {
        int[] a = new int[5];
       int temp;
        int[] ss = {3,55,6,7,1,4};
        int j;
        for (int i = 0; i < ss.length ; i++) {
            for( j=i;j< ss.length;j++){
                if(ss[i]<ss[j]){
                  temp=ss[i];
                    ss[i]=ss[j];
                    ss[j]=temp;

                }
            }
        }
        System.out.println("\n\n\n\n");
        for (int aaa: ss
        ) {
            System.out.print(aaa+",");
        }

        }

    }
    
