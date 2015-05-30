## Run

```
$ cd coreos
$ vagrand up
$ vagrand ssh
CoreOS stable (633.1.0)
```

```
core@core-01 ~ $ python -V
Sending build context to Docker daemon 79.87 kB
Sending build context to Docker daemon
Step 0 : FROM python:2.7
Pulling repository python
9fa21a3e9f2f: Download complete
39bb80489af7: Download complete
df2a0347c9d0: Download complete
7a3871ba15f8: Download complete
a2703ed272d7: Download complete
c9e3effdd23a: Download complete
24b3549417de: Download complete
3009dde7a8a5: Download complete
9da97b9166df: Download complete
a80d186674da: Download complete
fe7091222d5c: Download complete
29d755a35726: Download complete
1452a2aa19dd: Download complete
Status: Downloaded newer image for python:2.7
 ---> 9fa21a3e9f2f
Step 1 : ENV PYTHONUNBUFFERED 1
 ---> Running in 4a7d8fa7390b
 ---> 4786559fdc11
Removing intermediate container 4a7d8fa7390b
Successfully built 4786559fdc11
Python 2.7.10
```
