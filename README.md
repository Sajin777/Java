Class:

    # Blueprint, framework
    # LogicL entity
    # Can be communicate with one main class
    
      syntax:
             class class_name
             {
                // body of the class
             }

Object:

    # Instances of class
    # Physical entity
    # Communicate themself
    
      syntax:
             class_name oject_name = new class_name();
      Example:
             student s = new student();

How to get Dynamic imput form the user ?

     There are 2 ways,
     
               * BufferedReader
               * Scanner
               
> Code using BufferedReader:

BUFFEREDREADER code:
import java.io.BufferedReader;
import java.io.InputStreamReader;
import java.io.IOException;
class add
{
  public static void main(String args[])
  {
    int n1,n2,t;
    BufferedReader br = new BufferedReader(new InputStreamReader(System.in));
    System.out.println("Enter num1: ");
    n1=Integer.parseInt(br.nextline());
    System.out.println("Enter num2: ");
    n2=Integer.parseInt(br.nextline());
    t=n1+n2;
    System.out.println(t);
    br.close();
  }
}

Datatypes

    # Primitive
        > boolean
        > char
        > byte
        > short
        > int
        > long
        > float
        > double
    
    # Non primitive
        > String
        > Array
        > etc
