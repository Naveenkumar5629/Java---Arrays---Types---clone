# Java---Arrays---Types---clone
import java.util.*;
class Main {
    public static void main(String[] args) {
        //System.out.println(System.in);
        int a[]={72,56,9,76,1098};
        int b[]= a.clone();
        for(int temp:a){
            System.out.print(temp+" ");
        }
        System.out.println();
        for(int temp1:b){
            System.out.print(temp1+" ");
        }
    }
}
