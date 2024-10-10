# ngulf.py
* this script supports three methods. synflood, request, and pyslow. 

# note
* this tool was developed for educational purposes, and therefore is not to be used for illegal or destructive activity.


# requires modules
* termcolor
* colorama



# usage
```

                           888  .d888 
                           888 d88P"  
                           888 888    
88888b.   .d88b.  888  888 888 888888 
888 "88b d88P"88b 888  888 888 888    
888  888 888  888 888  888 888 888    
888  888 Y88b 888 Y88b 888 888 888    
888  888  "Y88888  "Y88888 888 888    
              888                     
         Y8b d88P                     
          "Y88P"                      
                                                                                        
                                                                                                      
 Version:0.1 

usage: ./ngulf -t [target] -p [port] -t [number threads]

options:
  -h, --help       show this help message and exit

options:

  -d <ip|domain>   specifiy target ip or domain address
  -t <float>       set timeout for socket
  -T <int>         set threads number for connection (default = 1000)
  -p <int>         specify port target (default = 80) |only required with pyslow attack|
  -s <int>         set sleep time for reconnection
  -i <ip address>  specify spoofed ip unless use fake ip
  -Request         enable request target
  -Synflood        enable synflood attack
  -Pyslow          enable pyslow attack
  --fakeip         Option to create fake ip if not specify spoofed ip

Example:
    ./ngulf -d www.example.com -p 80 -T 2000 -Pyslow
    ./ngulf -d www.domain.com -s 100 -Request
    ./ngulf -d www.google.com -Synflood -T 5000 -t 10.0
```
    
