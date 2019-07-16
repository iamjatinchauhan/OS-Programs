# OS-Programs
## System call
### Program to write some message on the screen.
```c++
#include<stdlib.h>
int main()
{
    write(1, "hello", 5); // 1st parameter is file descriptor (1 is for standard output), 2nd parameter is the message and 3rd parameter is the length of the message
}
```
