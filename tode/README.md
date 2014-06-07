###Installation

* mount the server vm tode directory (at tODE command line)

  ```Shell
  mount /opt/git/ServerVM tode /home serverVM
  ```

###Web Server

* register the web server with WAGemStoneRunSmalltalkServer (at tODE command line):

  ```Shell
  ./webServer --register=zinc --port=8383 
  ```

* start the web server:

  ```Shell
  ./webServer --start
  ```

* stop the web server:

  ```Shell
  ./webServer --stop
  ```