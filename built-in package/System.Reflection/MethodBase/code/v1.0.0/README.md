# Different in `C#` version
This project uses `C#` 11

There are difference between newever version of `C#` and older version of `C#`.

+ top level of `Program.cs`

By `C#` rule, it should be 

provided you have a project named `Example`

`Program.cs`

```
namespace Example
{
    class Program
    {
        static void Main(string args[])
        {
            // your code
        }
    }
}
```

However, in newer version, you can simply write like this

`Program.cs`

```
// your code
```

or in traditional fashion.

thanks to `vs` tool, it will automatically generate `Program` class with definition `static void Main` and 

put your code into `static void Main`.   
