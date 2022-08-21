# gemini_unit2_task4_prob3

import java.util.*;
public class HashsetDemo
{
public static void main(String[] args)
{
HashSet hs= new HashSet(); for(int i=0;i<10;i++) { hs.add(?i?); } System.out.println(?Set is ?+hs); //view HashSet
Iterator it=hs.iterator(); //add an iterator to hs
System.out.println("Elements using iterator:");
while(it.hasNext()) //display elements by using iterator
{
Integer s=(Integer)it.next();
System.out.println(s);
}
}
}
