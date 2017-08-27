对象是类的一个实例，有状态和行为。
类是一个模板，它描述一类对象的行为和状态。
类包括数据data member(属性）和成员函数member function。


类是对象的抽象，而对象是类的具体实例。类是抽象的，
而对象是具体的。类是用于创建对象的蓝图.


软件对象也有状态和行为。软件对象的状态就是属性，行为通过方法体现。
在软件开发中，方法操作对象内部状态的改变，对象的相互调用也是通过方法来完成。
```
类是现实世界或思维世界中的实体在计算机中的反映，它将数据以及这些数据上的操作封装在一起。
对象是具有类类型的变量。类和对象是面向对象编程技术中的最基本的概念。
它是一个定义包括在特定类型的对象中的方法和变量的软件模板。
```
package com.example.helloworld;

public class（class代表类） Gift {
    private double price;
    private String size;
    private String color;



    public Gift(double price,String size, String newColor) {
        this.price = price;
        this.size = size;
        this.color = newColor;
    }

    public void print() {
        System.out.println("print in gift");
        System.out.println(this.price);
        System.out.println(this.size);
        System.out.println(this.color);

    }
    public double price(){
        System.out.println("价格为 : " + price);
       return price;
    }

    public void setPrice(double price) {
        this.price = price;
    }
（这些public都代表一个成员函数）

}
```
System.out.println("gift1");
        Gift gift1（对象） = new Gift(20,"10cm*10cm","blue");

        gift1.print();
        gift1.setPrice(15);
        gift1.print();
        
```


