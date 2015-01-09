# testcobra

use go build the code
$go install testcorba.go

run the execute file

$ ./testcobra 


Usage: 
  app [command]

Available Commands: 
  print [string to print]   Print anything to the screen
  echo [string to echo]     Echo anything to the screen
  help [command]            Help about any command


Use "app help [command]" for more information about that command.


    $ ./testcobra print test
      Print: test


    $ ./testcobra echo times --times=2 hello
    Echo: hello
    Echo: hello

    $ ./testcobra echo times -t 2 hello
    Echo: hello
    Echo: hello

