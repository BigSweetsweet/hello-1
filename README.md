#public class Hello {

public static void main(String args�ۣ�) {

System.out.println(�延ӭ��ѧϰJava����!��);

}��

}




package pm;  
import java.util.Scanner; 
public class SwitchTest {
    public static void main(String[] args) {
       Scanner sc=new Scanner(System.in);
   while (true) {
    System.out.println("������Ҫת�����¶����ͣ�C �� F");
    String s = sc.next().trim();
    if ("c".equalsIgnoreCase(s)) {
          System.out.println("������Ҫת�����ϵ��¶�:..");
     double db = sc.nextDouble(); 
    double db2 = (db * 9 / 5) + 32;
     System.out.println("��Ӧ�Ļ����¶ȣ�" + db2 + "F");
    } else if ("f".equalsIgnoreCase(s)) {
          System.out.println("������Ҫת�����ϵ��¶�:..");
     double db = sc.nextDouble();
     double db2 = (db - 32) * 5 / 9;
     System.out.println("��Ӧ�������¶ȣ�" + Math.round(db2) + "C");
    }else if("exit".equalsIgnoreCase(s)){
     break;
    }
   }
  }
  }
