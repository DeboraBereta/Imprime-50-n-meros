# Imprime-50-n-meros


import java.util.Scanner;
public class atv1 {

    public static void main(String[] args) {
        int[] n;
        int c=0;
        n= new int[50];
        for (int i = 101; i < 151 ; i++){
            n[c] = i;
            c++;
        }
        for (int i =0; i<=49 ; i++){
        System.out.println(n[i]);    
        }
    }
 
}
