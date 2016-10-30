# noname
Project for Metrics 

Hotspot VM:
. Garbage Collector
. JIT Compiler
. VM Runtime

Ordinary Object pointers(oops) : Internal Hotspot Runtime representation of java objects

32 Bit VM Runtime: 
    Max 4GB memory can be used but it depends on OS. 
    Windows: 1.5 GB
    Linux: 2.5 to 3.0
64 Bit VM Runtime:
    Theoritically no limit on memory 
    Performnace hit as the size of oops inceresed from 32 to 64 bit so less variales on cpu cache.
        Can be improved --> -XX:+UseCompressedOops
VM Runtime Responsibilities:
    VM Lifecyle Management
    Cmd line parsing
        Standard Options
        Non Standard Options
            Starts with prefix -X
        Developer Options
            Starts with prefix -XX
    Class Loading
    Byte code interpreter
    Exeption Handling
    synchronization
    Thread Management
    Java Native Interface
    VM Fatal error Handling
    
    
    
