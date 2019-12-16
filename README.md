# 13_unit_homework
## Part 1: Local File Inclusion 

**Instructions:**

- Using **only** the LFI techniques that you have learned this past week, see if you can read the following confidential information from the server:
  - The `/etc/hosts` file
  ![Part 1 Local File Inclusion hosts](https://user-images.githubusercontent.com/8258629/70916291-73de2200-1fe9-11ea-8118-0920b63ebb06.PNG)

  - The `/etc/passwd` file
  ![Part 1 Local File Inclusion passwd](https://user-images.githubusercontent.com/8258629/70916494-c61f4300-1fe9-11ea-8361-169126c4730a.PNG)
- - -  

## Part 2: Command Injection 

**Instructions:**

- Using **only** the command injection techniques that you have learned this past week, see if you can read the following information from the server: 
  - The `/etc/hosts` file
  ![Part 1 Local File Inclusion hosts](https://user-images.githubusercontent.com/8258629/70916291-73de2200-1fe9-11ea-8118-0920b63ebb06.PNG)
  - The `/etc/passwd` file
    ![Part 1 Local File Inclusion passwd](https://user-images.githubusercontent.com/8258629/70916494-c61f4300-1fe9-11ea-8361-169126c4730a.PNG)
  
In addition to finding those files on the server, see if you can find information about the server itself. Specifically:

- All the groups on the server
  ![All the groups on the server](https://user-images.githubusercontent.com/8258629/70916525-d0d9d800-1fe9-11ea-961d-ae085b484e9c.PNG)
- The Kernel
![The Kernel](https://user-images.githubusercontent.com/8258629/70916555-ddf6c700-1fe9-11ea-8973-5b3940060792.PNG)
- Any cronjobs they may have
![Any cronjobs they may have](https://user-images.githubusercontent.com/8258629/70916597-f5ce4b00-1fe9-11ea-8eda-d53b8d08be5d.PNG)

- - -

## Part 3: Manually preforming XSS (0:10)

Cause an alert to pop up with the users cookie using XSS
![Part 3 Manually preforming XSS](https://user-images.githubusercontent.com/8258629/70916707-21513580-1fea-11ea-9e01-67fa61c44746.PNG)
