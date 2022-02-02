# Recursie-Functions-Hardware
Hardware implemented recursive function with two inputs and an output using stack. 
In this project we implemented the below recursive function:

```int fib (int n)
{
    If (n <= 1)
        return 1;
    else
    {
        If (n > N/2)
            return ((n - 1) * fib (n - 1) + (n - 2) * fib (n - 2));
        else
            return ((n - 2) * fib (n - 1) + (n - 1) * fib (n - 2));
    }
}
```
with verilog using a ```stack``` with ```push```, ```pop```, ```top``` and ```isEmpty``` signals.
Datapath and Controller figures can be found in REPORT.pdf
