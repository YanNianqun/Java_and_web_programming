### Classes, types and For each loops.
+ Class are types.
+ Object = Code + Data
```
public class Point {  // A class is template specifies how to make objects.
  private int x; // Declare two fileds.
  private int y;
  public Point(int startx, int starty) { // Declare of constructor.
    x = startx;
    y = starty;
  }
  public int getX() { return x }; //Declare three methods. Methods are functions inside class.
  public int getY() { return y };
  public double distance (Point OtherPt) { 
    int dx = x - OtherPt.getX();
    int dy = y - OtherPt.getY();
    return Math.sqrt(dx * dx + dy * dy); // static call.
  }
  public static void main (String[] args) { // static methods. Do not work on any particular instance of a class but belong to the class in general.
    point p1 = new Point (3, 4); // the "new" store the number in the heap.
    point p2 = new Point (6, 8);
    System.out.println(p1.distance(d2))
  }
```
+  Method call is like function call except that we need to specifiy the object.
+ Type shows how to interprate and opetate on the data.
  + There are two kinds of types in Java: Primitive and Objects.
    Primitives: int, double, char, boolean, float, long, byte, short.
    1. Value directly in a box.
    2. Can't invoke a method on.
    3. Can't be null (but can use a wrapper class)
  + Object: String, Point, Shape, any class you write your self.
    1. Reference (arrow)to object.
    2. Can invoke methods, access field with dot.
    3. Can be null.
    4. == checks if arrows point at some objects. 
