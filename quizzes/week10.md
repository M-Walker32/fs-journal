# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
A namespace denotes a schema
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
A class defines an object or ,many objects and provides refrences to their values
A struct does the samethign except instead of refrences to values it stores the values
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
void
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
The class Car
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
the value to be returned
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
it prevents the car from being created as a stand alone object
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
A virtuial is another object that this object will be attatched to
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
private, protected, public, internal
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
Only its self
```