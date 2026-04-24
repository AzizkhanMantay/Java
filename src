import java.util.*;
class Student implements Comparable<Student> {
String name;
double gpa;
Student(String name, double gpa) {
this.name = name;
this.gpa = gpa;
}
@Override
public int compareTo(Student other) {
return Double.compare(other.gpa, this.gpa);
}
}
public class Main {
public static void main(String[] args) {
List<Student> students = new ArrayList<>();
students.add(new Student("Ali", 3.2));
students.add(new Student("Aruzhan", 3.8));
students.add(new Student("Dias", 2.9));
students.add(new Student("Dana", 3.5));
Collections.sort(students);
for (Student s : students) {
System.out.println(s.name + " - " + s.gpa);
}
}
}
