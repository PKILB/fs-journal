# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
They are used to organize code into logical groups and to prevent naming collisions that can occur.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
Struct are value types whereas classes are reference types.
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
Void
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
It is set to a public virtual.
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
That there will be a string being returned.
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
I am not for sure here.
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
It will have a relationship with another variable.
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
public protected default and private
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
The declared class itself.
```