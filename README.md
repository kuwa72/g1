# g1
Go oneliner

## example

```
cat /etc/profile |  sh -x ./g1 'for{if(!sc.Scan()){break};fmt.Println(sc.Text())}'
# /etc/profile

# System wide environment and startup programs, for login setup
# Functions and aliases go in /etc/bashrc
...omitted...
```
