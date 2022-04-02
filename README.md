# The C++ Standard Library
Print the following statement: `The sum is N.` where N is the sum of the digits in [50, 100]. Aside from "mandatory" lines of code, no more than 3 statements are allowed. A statement is typically terminated with a semi-colon. Loop starts are also considered statements (`do {`, `while ()`, for () {`). See the skeleton below.

```cpp
#include <LIST ALL INCLUDES>

int main()
{
    <Statement 1>
    <Statemetn 2>
    <Statement 3>
    
    return 0;
}
```

## Hints
- The goal of this assignment is to utilize the C++ Standard Library.
- Before submitting, the following line of code can help you troubleshoot. It assumes your `std::vector` (<- use this) is called `nums`. Just substitute your vector's name in.
```cpp
#include <cassert>
  
int main() {
    // ...
    assert(nums.front() == 50 && nums.back() == 100);
    // ...
```
- If you use the check above, remember to delete **both** of those lines before submitting.

## Remember
- Name your file wsuid\_lab07.cpp
- You are now required to include a comment block at the top of the file. See the Coding Guidelines handout.
