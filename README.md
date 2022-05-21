### 过滤某些你想过滤的字符，有些域名扫得多了，需要过滤

### usage
```
cat 1.txt | ./filter -s gov,login, ... > 2.txt
cat 1.txt | ./filter -s gov,login, ...  | tee -a 2.txt
```
