# Shape-

# Cicle

public class Circle extends Shape
{
    int r;
    public Circle(int x,int y,int r)
    {
        super(x,y);
        this.r=r;
    }

    void draw()
    {
        System.out.println("Radius is=" +r);
    }
}


# Rectangle

public class Rectangel extends Shape
{
    int length;
    int width;

    public Rectangel(int x,int y,int length,int width)
    {
        super(x,y);
        this.length=length;
        this.width=width;
    }
    void draw()
    {
        System.out.println("Length of Rectangle is=" +length);
        System.out.println("Width of Rectangle is=" +width);
    }
}

# Triangle

public class Triangle extends  Shape
{
    int height;
    int base;

    public Triangle(int x, int y,int height,int base)
    {
        super(x, y);
        this.height=height;
        this.base=base;
    }
    void draw()
    {
        System.out.println("Height of Triangle is=" +height);
        System.out.println("Base of Triangle is=" +base);
    }
}


# Shape

public class Shape {
    int x;
    int y;

    public Shape(int x,int y)
    {
        this.x=x;
        this.y=y;
    }

}

# Main

public class Main {
    public static void main(String[] args)
    {
      //  Shape s=new Shape(10,20);
        //s.draw();

        Circle c=new Circle(10,20,15);
        c.draw();

        Rectangel r=new Rectangel(10,20,15,25);
        r.draw();

        Triangle t=new Triangle(10,20,18,22);
        r.draw();
}
}
