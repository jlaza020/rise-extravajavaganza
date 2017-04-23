### Given the following method declaration, the following method will return true if and only if this is true.

```java
public static boolean check(String s)
{
   return s.length() >= 2 &&
          (s.charAt(0) == s.charAt(1) ||
           check(s.substring(1)));
}
```

      (A) The string s contains two or more of the same characters.
      (B) The string s starts with two or more of the same characters.
      (C) The string s contains two or more of the same character that are next to each other.
      (D) The string s ends with two or more of the same characters

