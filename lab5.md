I created one java file and created one bash file that I can test java file.

# 1
Student: These are my java file and bash file. I tried to test out a simple java file and it keeps giving me this error.
test.sh:
```
javac lab5.java

# Checking if compilation was successful
if [ $? -eq 0 ]; then
    echo "Success"
    javac lab5
else
    echo "Fail"
fi
```

lab5.java:
```
public class lab5{
    public static void main(String[] args) {
        
        System.out.println("This is lab5");
    }
}
```
