ping-pong
=========

Mutual exclusion within ring topology - Ping-Pong algorithm (Misra 1983).


How to compile and run:
-----------------------
```bash
mpic++ main.cpp -std=c++11
mpirun -n [proc_num] ./a.out [--ping] [--pong]```

`--ping` and `--pong` turn on message lost simulation

