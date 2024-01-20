# Topic: Deadlock & Concurrency Control

### Site: https://os-project.netlify.app/


# Technologies Used: -
• HTML5
• CSS
• JAVASCRIPT
• BOOTSTRAP

# Software’s to Be Installed:
Any text editor like notepad, WordPad etc are sufficient.
Any code editor like VScode, Sublime etc.

# Download link: -
1. Download the Visual Studio Code installer for Windows.
2. Once it is downloaded, run the installer (VSCodeUserSetup-{version}.exe). This 
will only take a minute.
3. By default, VS Code is installed 
under C:\users\{username}\AppData\Local\Programs\Microsoft VSCode.
# Introduction: -
This website contains information about the concurrency & deadlock topics of OS. After giving input 
run the algorithm. The theory pages are static pages mainly implemented using HTML and CSS for 
styling. The layout and design are kept very elegant and simple for better viewing and easy navigation. 
The pages are responsive and can be opened on mobile phones, tablets, Desktop without any
problem. We have implemented 6 algorithms namely MUTEX, PRODUCER&CONSUMER, BANKER, 
BINARY SEMAPHORE, COUNTING SEMAPHORE and LOCK VARIABLE.


# How to Run Algorithm?

### Clone the repo in your local machine and open the folder in your IDE. (prefered is VS Code).
### Open index.html file and click GO live option which is located at bottomright corner of your VScode editor. Screen look like below.

## DISK SCHEDULING 
Disk Scheduling is basically used to schedule I/O request arriving in the system. It is important to schedule the I/O requests because at a time many I/O requests are made, and our disk controller can 
execute any one of the requests. So, to choose one request out of the others we use various disk scheduling algorithms so that each request is accessed in the minimal time and each request gets 
executed.

Suppose we have track numbered from 1 to 99 and someone wants the data from track number 20,35,60. Then the disk scheduling algorithms decides that in which order shall we fulfil the request. 
This is important because we must move read/write head over the tracks and to minimize the seek time we use these disk scheduling algorithms.

## Concurrency 
Concurrency is the execution of the multiple instruction sequences at the same time. It happens in the operating system when there are several process threads running in parallel. The running process 
threads always communicate with each other through shared memory or message passing. Concurrency results in sharing of resources result in problems like deadlocks and resources starvation. 
Concurrency is the execution of the multiple instruction sequences at the same time. It happens in the operating system when there are several process threads running in parallel. The running process 
threads always communicate with each other through shared memory or message passing. Concurrency results in sharing of resources result in problems like deadlocks and resources starvation. 
It helps in techniques like coordinating execution of processes, memory allocation and execution scheduling for maximizing throughput.

## Deadlock 
It helps in techniques like coordinating execution of processes, memory allocation and execution scheduling for maximizing the output. Deadlock is a situation where a set of processes are blocked 
because each process is holding a resource and waiting for another resource acquired by some other process. The permanent blocking of a set of processes that either compete for system resources or 
communicate with each other  A set of processes is deadlocked when each process in the set is blocked awaiting an event that can only be triggered by another blocked process in the set v. It is 
permanent because none of the events is ever triggered in v. It is not an efficient solution in the general case.
