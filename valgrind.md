**compile code with:**
```bash
gcc -g *.c
```

**run code**
```bash
valgrind --leak-check=full --show-leak-kinds=all --track-origins=yes
```