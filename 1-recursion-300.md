### Given the following method declaration, this is printed as the result of the call mystery(1234).

```java
//precondition:  x >=0
public static void mystery (int x)
{
   System.out.print(x % 10);

   if ((x / 10) != 0)
   {
      mystery(x / 10);
   }
   System.out.print(x % 10);
}
```

    (A) 1441
    (B) 43211234
    (C) 3443
    (D) 12344321
    (E) Many digits are printed due to infinite recursion.
