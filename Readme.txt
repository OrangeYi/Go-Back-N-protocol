Ziyi Chen

Make version: GNU Make 3.81
openjdk version "1.8.0_91"
OpenJDK Runtime Environment (build 1.8.0_91-8u91-b14-0ubuntu4~14.04-b14)
OpenJDK 64-Bit Server VM (build 25.91-b14, mixed mode)

Just use "make" to compile the file.


Example Execution
1. Onthehosthost1: ./nEmulator 9991 host2 9994 9993 host3 9992 1 0.2 0 
2. Onthehosthost2: java receiver host1 9993 9994 <output File>
3. Onthehosthost3: java sender host1 9991 9992 <input file>

Execution step:
1. Run emulator (eg, ./nEmulator 9991 host2 9994 9993 host3 9992 1 0.2 0 )
2. Run receiver (eg, java receiver host1 9993 9994 <output File>)
3. Run sender (eg, java sender host1 9991 9992 <input file>)
ps: Make sure u have the input file before you run the sender

