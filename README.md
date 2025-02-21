# Things to Learn by Heart as a Backend Engineer

## Computer Organization and Architecture

## Operating System
### 1. What?
- An Operating System is a System software that manages all the resources of the computing device. 

### 2. Why?
- Resources needs to be managed
- Applications talk to the OS
- Most OSs are general purpose (EG: linux, window are different purpose)
#### Scheduling things
- scheduling is critical
- Fair share of resources to all processes (CPU, Memory, IO)
- Application works on any hardware
- Occasional breaking changes (64bit/32bit)
- Do we can build app without OS?

=> OS APIs abstracts the hardware -> Hide complexity
=> Understand OS that help we build efficient application.


### 3. OS Architecture Overview
#### System Architecture
- System has resources
- The Kernel is OS core component

#### CPU
- Central Processing Unit
- Consists of cores
- Each core has a clock speed
- Executes machine level instructions
- Fast cache

#### Memory
- Random Access Memory
- Fast but Volatile (loss the data)
- Store process states and data
- limited
- Slower than CPU cache

#### Storage
- Persisted storage
- HDD, SSD
- Slower than memory

#### Network
- Communicates with other hosts
- NIC (Network Interface Controller)
- Protocol implementations

#### Kernel
- The core of the OS
- Manages the resores
- The OS is more than the kenel. EG: GUI, command lines, UI, tooling

#### File System
- Storage is mostly blocks of bytes
- File system is an abstraction
- How files stored on disk
- btrfs, ext4, fat32, NTFS, tmpfs

#### Program vs Process
- Program is the compiled executable
- Process is an instance of the program
- Process is an program in motion
- Execution file format

#### Process Management
- Kernel managess processes
- Schedules process for a CPU
- Switches a process for another
- Grant access to resources like storage

#### User space vs Kenel space
- User space: Browser, Db
- Protected kernel space: Kernel code, device drivers, TCP/IP stack
- Isolated

#### Device Drivers
- Drivers are software in the kernel
- Manages hardware devices
- NVMe, Keyboard, NIC, etc...
- Interrupt Service Routine

#### System Calls
- To jump from User to Kernel mode
- User makes a system call
- read(), write(), malloc()
- Mode switch

## Networking

## Programing language (Golang)

## Database

## Design Pattern

## Software Architecture pattern

## Database Internal

## Docker

## Kubenetes

## System Design
