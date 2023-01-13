# LinkedList
import java.util.ArrayList;
import java.util.Arrays;
import java.util.LinkedList;
import java.util.List;

public class DSA {


    public static void main(String args[]){

        String[] nameList = {"hanna","dav","abel","seni","kebede","hanna"};

//        for (int i = 0; i < nameList.length; i++) {
//            System.out.println(nameList[i]);
//        }
//
//        for(String name:nameList){
//            System.out.println(name);
//        }

        ArrayList<String> members = new ArrayList<>();



        members.add("abel");
        members.add("hanna");
        members.add("dav");
        members.add("seni");
        members.add("hailu");
        members.add("asede");
        System.out.println(members);

//        for (int i = 0; i < members.size(); i++) {
//            members.get(i);
//        }

        members.set(2, "zerihun");
        members.remove(3);

        System.out.println(members);


        List anything = new ArrayList();

        anything.add("hanna");
        anything.add(78);
        anything.add(members);
        anything.add(nameList);








    }
}
