import java.util.ArrayList;
import java.util.List;

public class AcessElementsFromArrayList {
    public static void main(String[] args) {
        List<String> stringList = new ArrayList<>();
        //here checking the list is empty or not this ie empty method only return true/false statement
        //list default size is 0
        System.out.println("THE LIST IS :"+stringList.isEmpty());
        stringList.add("c");
        stringList.add("c++");
        stringList.add("java");
        stringList.add("python");
        stringList.add("javaScript");
        stringList.add("c#");
        stringList.add("Spring");
        stringList.add("Django");
        //this method is used to get the size of an list
        System.out.println("THE SIZE OF THE LIST IS :"+stringList.size());

        //the starting index of the list is "0"
        //this get method is used to get the element from the list
        String lang = stringList.get(2);
        System.out.println(lang);

        //modify the element from a list
        stringList.set(1,".net");
        System.out.println(stringList);

        //remove method to remove a particular element this is for index based below one is for particular object
        stringList.remove(3);
        System.out.println(stringList+"AFTER");

        stringList.remove(".net");
        System.out.println("REMOVING OBJECT"+stringList);

        // to remove list of objects from the array list we can create a new list and add the list of objects
        //that we wanted to remove and then we can use removeall method to remove those from the list
        List<String> newLang = new ArrayList<>();
        newLang.add("Django");
        newLang.remove("python");
        stringList.removeAll(newLang);
        System.out.println("LIST AFTER REMOVING MULTI ELEMENTS FROM LIST"+stringList);

        //clear method is used to remove all the elements from the list
        stringList.clear();
        System.out.println("LIST AFTER CLEARIN G ALL ELEMENTS"+stringList);

    }
}
