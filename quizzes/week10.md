# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
The name space is the name of your entire folder. So if the folder name is fs-journal it would be the name space. They organize and provide a level of separation of code.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
A struct is a value type. A class is a reference type. Structs are stored in a stack where classes are stored in heaps.
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
A method that has no return type would be the void method. It can have a return but doesn't require one.
```
## Example 1
```c#
abstract class Car
{
  ...
  public virtual string Start()
  {
    return "Vroooom";
  }
}
```
**5.** In the example what is the access modifier of the `Start()` method?
<!-- enter you answer in the space below -->
```
The access modifier is public which refers to what other files can read and use this method.
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
The string is a type of data that something is set to. So since it's set to string it indicates that the return will be a string.
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
The example with abstract prevents the internal details from being made public or accessed anywhere else. It will only show functionality and that is it.
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
The virtual in the example modifies the method it's on. So if any other class inherits it, it can be overridden by that class.
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
The four access modifiers are private, public, protected, and internal. 
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
The only files that can access something with protected are other same assemblies or a derived class of that project.
```