# OS Lab – Assignment 5
## Process Synchronization using xv6

**Name:** Manogna  
**Roll No:** 2401MC46

## Programs Implemented

1. **Peterson's Algorithm** – Mutual Exclusion
2. **Producer-Consumer Problem** – Bounded Buffer
3. **Readers-Writers Problem**
4. **Dining Philosophers Problem** – Deadlock Avoidance

## Environment

- xv6
- Ubuntu / WSL2
- GCC
- QEMU

## How to Run

Build xv6 using:

```bash
make clean
make
make qemu

Run the programs inside xv6:

$ peterson
$ prodcons
$ readwrite
$ dining
Results
Peterson's Algorithm: Final counter = 20
Producer-Consumer: Completed successfully
Readers-Writers: Completed successfully
Dining Philosophers: All 5 philosophers completed 5 cycles successfully
Conclusion

The assignment demonstrates process synchronization, mutual exclusion,
bounded-buffer synchronization, reader-writer synchronization, and
deadlock avoidance in xv6.
