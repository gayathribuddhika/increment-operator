import java.util.Scanner;
public class incrementOperator {

    
    public static void main(String[] args) {
        int x = 5;
        //x++; 
        //x=x+1;
        //x++(post increment),++x(pre increment)
        //x++,first print the value then increment.++x frist increment then print.   
        int y = 10;
        int m = 12;
        int p = 2;
        int j= 15;
        y += 5;//y=y+5
        m *=2;//m=m*2
        p -=1;//p=p-1;
        j /=3;//j=j/3
        System.out.println(++x); 
        System.out.println(x);
        System.out.println(y);
        System.out.println(m);
        System.out.println(p);
        System.out.println(j);
    }
    
}
