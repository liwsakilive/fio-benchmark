# fio-benchmark
```
1. git clone https://github.com/liwsakilive/fio-benchmark.git
2. cd fio-benchmark
3. vim clients.txt <--- Add your client ip
```
## remote to client
```
4. ssh user@1.1.1.1
  4.1 apt inatall fio -y
  4.2 fio --server <--- run all client
```
## comeback to fio-benchmark directory
```
5. fio --client=clients.txt fio-random-read.fio  
6. fio --client=clients.txt fio-random-write.fio 
```
