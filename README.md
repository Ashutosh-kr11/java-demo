# java-demo

#update app:
```bash
package com.demo;
import com.google.gson.Gson;

public class App {
    public static void main(String[] args) {
        Person p = new Person("Ashutosh", 24);
        Gson gson = new Gson();
        String json = gson.toJson(p);
        System.out.println("JSON Output: " + json);
    }
}

class Person {
    String name;
    int age;

    Person(String name, int age) {
        this.name = name;
        this.age = age;
    }
}
```
