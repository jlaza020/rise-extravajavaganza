### This is what test would return if a = {1,2,3,4} and v = 3.

```java
public static int test(int[] a, int v)
{
    for (int i = 0; i < a.length; i++)
    {
        if (a[i] == v)
            return i;
        else return -1;
    }
}
```

    (A) -1
    (B) 0
    (C) 1
    (D) 2
    (E) The code will not compile
