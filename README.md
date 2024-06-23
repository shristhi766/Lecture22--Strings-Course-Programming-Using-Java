# Lecture22--Strings-Course-Programming-Using-Java

package strings;
public class StringStudy{
public static void main(Strings[] args){
        String name = "CipherSchool";
        String name2 = "CipherSchool";
    String name3 = new String("CipherSchools");
    String name4 = new String("CipherSchools");
    System.out.println(name == name 2);
    System.out.println(name3 == name 4);
    System.out.println(name == name 3);
String s1 = "Hello";
String s1 = s1+ "Peeps";
System.out.println(s1);
System.out.println(s1 + " How're you doing");
System.out.println(s1);


/////ANOTHER WAY 
String s2 = new String("Hello");
String s3 = new String("People");
String s4 = s2.concat(s3);
System.out.println(s2);
System.out.println("=======================================")
System.out.println("1. CONCATENATION");
String s1 = "Hello";
String s2 = "Peeps";
System.out.println(s1);
System.out.println(s1 + "How're you doing");
System.out.println(s1);
String s1 = "Hello";
String s2 = "Peeps";
s2.concat(s3);
System.out.println(s4);
System.out.println(s2);






System.out.println("==============================");
System.out.println("7. Length of a String");
int len = name.length();
System.out.println("Length:" +name+ "is:" + len);
System.out.println("==============================");
System.out.println("8. Finding index of a char in a String");
int index = name indexOf('e');
System.out.println("Index of 'e' in "+name+" is:" +index);


int index2 = name.indexOf('E');
System.out.println("Index of 'E' in " + name+  "is: + index2);

int index3 = name.indexOf('School');
System.out.println("Index of 'School' in " + name+  "is: + index3);

int index4 = name.indexOf('o', 10);
System.out.println("Index of 'o' in " + name+  "is: + index4);


while()
{
        indexOfO = name.indexOf('o', indexOfO + 1);
        if(indexOfO == 1) break;
        System.out.println("O found at: " + indexOfO);
