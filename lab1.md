# 1. `cd`
  ## 1-1. the command with no arguments
  ![Image](1-1.png)\
  The working directory was /home/lecture1 when the command was run. cd means to change the current directory to the given path and the working directory changed to ~ which means that the working directory changed to the /home directory. The output is not an error.
  
  ## 1-2. the command with a path to a directory as an argument
  ![Image](1-2.png)\
  The working directory was /home/lecture1 when the command was run. The output is like this because the current directory was switched to messages from lecture1. The output is not an error.
  
  ## 1-3. the command with a path to a file as an argument
  ![Image](1-3.png)
  The working directory was /home when the command was run. en-us.txt is a file not a directory. Output is an error because when we use cd, we are supposed to switch the current working directory to the given path. However, since en-us.txt isn't a directory, it doesn't switch to a different directory when we typed cd, and it's not doing what it's supposed to do, so I would consider it an error.


# 2. `ls`
   ## 2-1. the command with no arguments
   ![Image](2-1.png)\
   The working directory was /home when the command was run. The output is like this because lecture1 directory is under /home/ directory and ls shows the files and folders in the given path. The output is not an error.
   
   ## 2-2. the command with a path to a directory as an argument
   ![Image](2-2.png)\
   The working directory was /home when the command was run. The reason for the output is because messages directory, Hello.class file, Hello.java file, and README file were under lecture1 directory and ls shows the files and folders in the given path which was lecture1. The output is not an error.
   
   ## 2-3. the command with a path to a file as an argument
   ![Image](2-3.png)\
   The working directory was /home when the command was run. The output is this because that is the path to a file. The output is not an error.


# 3. `cat`
   ## 3-1. the command with no arguments
   ![Image](3-1.png)\
   The working directory was /home when the command was run. cat prints the contents of one or more files given by the path, but since there are only folders not files under /home/ directory, it can't print anything. That's why there is nothing when the command was run. Output is not an error.
   
   ## 3-2. the command with a path to a directory as an argument
   ![Image](3-2.png)\
   The working directory was /home/lecture1 when the command was run. I think the output was like this because messages has three text files but the given path was the only directory, not a specific file so it's showing Is a directory. I think it is an error because cat is used to print the contents of files given by the path, but none of the files are given by the path. The path is just a  directory.
   
   ## 3-3. the command with a path to a file as an argument
   ![Image](3-3.png)
   The working directory was /home/lecture1/Hello.java when the command was run. It is because cat prints the contents of the files given by the path and a file which is Hello.java is given by the path. It is not an error.
