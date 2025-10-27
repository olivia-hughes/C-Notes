## Functions

Functions - arguments can have default values. 

```cpp
int volume(int length=1, int width=1, int height=1){}
```
Default values act as a placeholder unless other value(s) are otherwise stated.
If you have a function that takes anything other than only numerical values, such as a function that takes one float argument and one int argument, then the numerical argument/value should be stated at the end of the parameter list.
```cpp
void printArea(float length, int decimalPlaces = 2){}
```

### Return objects
Returning the object as an argument
```cpp
// structure
object = return object_name

// Example
Example add(Example Ea, Example Eb){}

### Function Overloading

✅ Can write more than one function with the same name - as long as they have different numbers of arguments or different argument types. 
Compiler will determine which version to use for each call by looking at the arguments. 
Return types of overloaded functions - may be same or different
```cpp
int square(int x);
float square(float x);
float area(float height, float width);
float area(float radius);
```
❌ Impossible to declare a function in the body of another function.
✅ Instead use inline functionality (similar, short, simple)
```cpp
inline int cube(int i){return i*i*i;}
```
