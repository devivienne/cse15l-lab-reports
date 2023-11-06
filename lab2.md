# Part 1

```
import java.io.IOException;
import java.net.URI;
import java.util.Scanner;

class Handler implements URLHandler {
    String str = "";
    int num = 0;
    public String handleRequest(URI url) {
        if (url.getPath().equals("/add-message")) {
            String[] parameters = url.getQuery().split("=");
            if (parameters[0].equals("s")) {
                num += 1;
                String num1 = Integer.toString(num);
                str += num1 + ". " + parameters[1] + "\n";
                return str;
            }
        }
        return "404 Not Found!";
    }
}

class StringServer {
    public static void main(String[] args) throws IOException {
        if(args.length == 0){
            System.out.println("Missing port number!");
            return;
        }

        int port = Integer.parseInt(args[0]);

        Server.start(port, new Handler());
    }
}
```

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
I learned how to run servers on remote computers and how to access servers in easier way such as logging in without passwords. I also learned how to access URLs from the command line with using curl command. 

