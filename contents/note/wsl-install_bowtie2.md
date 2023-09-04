# WSL: Install ***bowtie2*** in ubuntu

### 1. Install wget

``` bash
ubuntu@JK:~$ sudo apt install wget
```

### 2. Update the repository cache

``` bash
ubuntu@JK:~$ sudo apt update
```

### 3. Create a fresh directory

``` bash
ubuntu@JK:~$ mkdir bowtie2
```

### 4. Change directory

``` bash
ubuntu@JK:~$ cd bowtie2
```

### 5. Install bowtie2

``` bash
ubuntu@JK:~/bowtie2$ sudo apt install bowtie2
```

### 6. Check if it is installed successfully

``` bash
ubuntu@JK:~/bowtie2$ bowtie2
```

``` bash
# No index, query, or output file specified!
# Bowtie 2 version 2.4.4 by Ben Langmead (langmea@cs.jhu.edu, www.cs.jhu.edu/~langmea)
```