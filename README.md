# web-security
1. User Enumeration
  - Because when you enter an invalid username or password it tells you which one is invalid allows users to brute force attack a user. if they guess his username all he has to do is guess his password, this makes it a lot easier for hackers 
    - wordpress 4.2
2. (Required) xss
  - XSS, CVE-2016-7168, Test Version: WordPress 4.5.3, patched WordPress 4.6.1:
  - this vulnerability that allows users with editor or author privileges to run XSS on WordPress, any version before 4.2.3 can do this. any user with the above privileges, who tries to embed cross site scripting on their post can do this. This may be used for privilege escalation.
3. second xss
  - If an admin attempts to load a bogus media file exceeding maximum allowed file size through upload.php, a file name could allow the execution of cross site scripting. This is because of the lack of file name sanitation. 
    - second XSS , CVE-2017-9061, Test Version: WordPress 4.7.4, patched WordPress 4.7.5
