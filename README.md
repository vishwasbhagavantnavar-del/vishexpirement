package vishex.pkg1;
import java.util.Scanner;


public class Vishex1 {

    
    public static void main(String[] args) {
        int m,n;
        Scanner s=new Scanner(System.in);
        System.out.println("Enter the values for m & n");
        m=s.nextInt();
        n=s.nextInt();
        
        int[][] a=new int [m][n];
        int[][] b=new int [m][n];
        int[][] sum=new int [m][n];
        
        System.out.println("Enter the elements of Matrix A");
        for(int i=0;i<m;i++){
            for(int j=0;j<n;j++){
                a[i][j]=s.nextInt();
            }
        }
        for(int i=0;i<m;i++){
            for(int j=0;j<n;j++){
                System.out.print(a[i][j]+" ");
            }
            System.out.println();
        }
        System.out.println("Enter the elements of Matrix B");
        for(int i=0;i<m;i++){
            for(int j=0;j<n;j++){
                b[i][j]=s.nextInt();
            }
        }
        for(int i=0;i<m;i++){
            for(int j=0;j<n;j++){
                System.out.print(b[i][j]+" ");
            }
            System.out.println();
        
    }

        System.out.println("SUM of A & B:");
        
         for(int i=0;i<m;i++){
            for(int j=0;j<n;j++){
                sum[i][j]=a[i][j]+b[i][j];
            
                System.out.print(sum[i][j]+" ");
            }
            System.out.println();
         }
    
        }
    }
