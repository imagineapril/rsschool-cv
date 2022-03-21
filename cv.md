# Timokhina Julia

# Contact Info

- julia.timokhina604@gmail.com
- +79172494457
- GitHub: imagineapril

# About myself

I like travelling and reading. My goal is to get a job as js-developer for helping people do beautiful things on the web. I've worked as a teacher for German and English for 3 years. Now I have a remote job (making websites on Wordpress and Tilda).

# Skills

- HTML
- Java Core

# Code Examples

```java
public class Palindrome {

    static boolean isPalindrome2(String s2){

        StringBuffer rev = new StringBuffer(s2).reverse();
        String strRev = rev.toString();
        if (s2.equals(strRev)) {
            return true;
        } else {
            return false;
        }
    }

    static boolean isPalindrome1(String s1){
        int n = s1.length();
        for (int i = 0; i < (n / 2); ++i) {
            if (s1.charAt(i) != s1.charAt(n - i - 1)) {
                return false;
            }
        }
        return true;
    }

    public static void main(String[] args) {
        System.out.println(isPalindrome1("12121"));
        System.out.println(isPalindrome2("12121"));
        System.out.println(isPalindrome1("мадам"));
        System.out.println(isPalindrome2("мадам"));
    }
}
```

# Education

- Kazan State Pedagogical University (German and English teacher)
- Kazan State Technical University (Computer Security)
- Innopolis Institue of Additional Education (Java Core)

# Languages

- German C1 (DSD II)
- English C1 (EF SET, but I don't trust it:))
- Spanish A1
