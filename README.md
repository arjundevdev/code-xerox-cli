code-xerox-cli Readme
==============

This code is used to post issue on github/bitbucket repository via Command Line Interface. Here is the step to run this code with server requirements


A) System Requirements:

1. Linux Server
2. Apache 2.0+ Server
3. PHP 5.2+
4. Enable curl extension
5. Enable register_argc_argv


B) How to Install:

1. Need to upload all the script file on the server via FTP or any other file uploader.

   a) create_issue.php

   b) inc/OAuthApi.php

   c) inc/OAuthApiException.php

2. Open command line and connect to server via host username & host password

3. Code directory will be
   e.g. cd /var/home/html/

4. Need to trigger below given URL on browser to post repository issue on the github|bitbucket (Please add your github|bitbucket login credentials in place of username and passowrd)

  e.g. php issue.php username password "https://github.com/arjundevdev/code-xerox-cli" "Issue Title" "Issue Description"
     
  e.g. php issue.php username password "https://bitbucket.org/arjundevdev/code-xerox-cli" "Issue Title" "Issue Description"


