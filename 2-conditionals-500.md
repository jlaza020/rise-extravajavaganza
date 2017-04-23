### The following method will return true if and only if:

```java
public boolean check(String s) {
   return s.length() >= 2 && (s.charAt(0) ==
      s.charAt(1) || check(s.substring(1)));
}
```

    (A) s starts with two or more of the same characters
    (B) s contains two or more of the same characters
    (C) s contains two or more of the same character in a row
    (D) s ends with two or more of the same characters
    (E) s.charAt(0) == s.charAt(1)

