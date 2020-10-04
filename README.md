# fio-benchmark
```
1. apt install fio
2. git clone https://github.com/liwsakilive/fio-benchmark.git
3. cd fio-benchmark
4. vim clients.txt <--- Add your client ip
```
## remote to client
```
5. ssh user@1.1.1.1
  5.1 apt inatall fio -y
  5.2 fio --server <--- run all client
```
## comeback to fio-benchmark directory
```
6. fio --client=clients.txt fio-random-read.fio  
7. fio --client=clients.txt fio-random-write.fio 
```
