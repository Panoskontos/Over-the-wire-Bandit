# Over-the-wire-Bandit Solutions

### Level 0
-----
```

cd ~ 
cat readme 

```

### Level 1
------
```

cat /home/bandit1/-

```

### Level 2
----
```
cat /home/bandit2/spaces\ in\ this\ filename
```


### Level 3
----
```
cd ~
cd inhere/
ls -a
cat .hidden
```
### Level 4
----
```
file -- *
cat -- \-file
```
### Level 5
----
```
find . -type f -size1033c ! -executable
```

### Level 6
----
```
find . -size 33c -user bandit7 -group bandit6
```


### Level 7
----
```
grep "millionth" data.txt
```


### Level 8
----
```
sort data.txt | uniq -u
```

### Level 9
----
```
strings data.txt | grep -a "[=]*"
```

### Level 10
----
```
base64 -d data.txt
```
