# javacmd

## Motivation
A lot of simple java programs have the same initial structure like following: 

```Java
import java.util.*;

class {{ClassName}}
{

    public static void main(String[] args)
    {

    }
}
```
This commandline utility creates that template by just providing the class name. 
It even changes the {{ClassName}} with the name of the class you enter!



### Installation

`git clone https://github.com/AmirNaghibi/javacmd.git`

`./install`



### Usage
```Bash
jcreate YourClassName
```
