# Part 1

`import java.io.IOException;
import java.net.URI;
import java.util.Scanner;

class Handler implements URLHandler {
    String str = "";
    public String handleRequest(URI url) {
        if (url.getPath().equals("/add-message")) {
            String[] parameters = url.getQuery().split("=");
            if (parameters[0].equals("s")) {
                Scanner stringScanner = new Scanner(System.in);
                String str = stringScanner.next();
                return String.format("Input string is" + str);
            }
            Scanner stringScanner = new Scanner(System.in);
            String str = stringScanner.next();
            return String.format("Input string is" + str);
        }
        return "404 Not Found!";
    }
}`


![Image](1-1.png)
It should call url.getPath().equals method but because there was errors in my code, it only only returned and showed 404 NOt Found!.

# Part 2
  ## 2-1
  ![Image](2-1.png)\
  ![Image](2-1-1.png)
  ## 2-2
  ![Image](2-2.png)
  ## 2-3
  ![Image](2-3.png)

# Part 3

