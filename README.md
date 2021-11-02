# CMPS-3240-Lab6

Original Benchmark (from Lab manual):
```shell
$ for i in {1..3}; do time ./bench_dewvm.out; done;

real    0m0.716s
user    0m0.284s
sys     0m0.428s

real    0m0.657s
user    0m0.324s
sys     0m0.332s

real    0m0.661s
user    0m0.280s
sys     0m0.384s
```

Benchmark after modifications:
```shell
$ for i in {1..3}; do time ./bench_dewvm.out; done;

real	0m0.245s
user	0m0.169s
sys	  0m0.076s

real	0m0.243s
user	0m0.191s
sys	  0m0.052s

real	0m0.234s
user	0m0.170s
sys	  0m0.065s
```
