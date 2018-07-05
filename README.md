# Global knowledge

A few questions to test your global knowledge.

## Linux

Here are lists with one intruder. Please find it.

1. Code source
  - [ ] Git
  - [ ] Svn
  - [ ] IDE

2. Distributions
  - [ ] Debian
  - [ ] CentOS
  - [ ] Mandriva

3. Rights
  - [ ] Copyright
  - [ ] Copyleft
  - [ ] Creative Commons

4. Users
  - [ ] admin
  - [ ] root
  - [ ] administrator

5. Commands
  - [ ] sudo
  - [ ] ls
  - [ ] dir

6. Ports
  - [ ] 21
  - [ ] 22
  - [ ] 25

7. Methodologies
  - [ ] TDD
  - [ ] Scrum
  - [ ] BCC

8. Get argument from command line
  - [ ] `$1`
  - [ ] `$ARGV[1]`
  - [ ] `$PARAM[1]`

9. Curl command
  - [ ] `curl -XPOST https://server.com/users`
  - [ ] `curl --post --insecure https://server.com/users`
  - [ ] `curl -L -k -s --data '{"key": "value"}' https://server.com/users`

10. Process list
  - [ ] `ps`
  - [ ] `top`
  - [ ] `id`

11. Help me
  - [ ] `man top`
  - [ ] `cp --help`
  - [ ] `mysql -h`

12. Search
  - [ ] `grep -rinI toto *.log`
  - [ ] `find . -type f -name '*.log' `
  - [ ] `sed s/toto// *.log `

13. Standards
  - [ ] `time python script.py 1>> file.log 2>> error.log`
  - [ ] `echo "select name from users" | mysql > file.log 2>&1`
  - [ ] `ps faux &1>2 file.log`

14. bash loops
  - [ ] while
```
while read LINE
do
  echo $LINE
done < file.log
```
  - [ ] for
```
for i in {0..10}
do
  echo ${i}
done
```
  - [ ] foreach
```
foreach i in $(cat file.log)
do
  echo $i
done
```

15. quote me
`MY_VAR=8  echo '${MY_VAR};22' | cut -d ';' -f1`
  - [ ] 22
  - [ ] 8
  - [ ] `${MY_VAR}`

16. Read
  - [ ] `cat /tmp/toto.log`
  - [ ] `tail -f  ~/file.log`
  - [ ] `less /var/log/apache2/access.log`

### Find intruder

Here are lists with one intruder. Please find it.

1. Languages
  - [ ] python
  - [ ] bash
  - [ ] ksh

2. HTTP servers
  - [ ] Apache HTTPD
  - [ ] Werkzeug
  - [ ] NGINX

3. Databases
  - [ ] MongoDB
  - [ ] PostgreSQL
  - [ ] MySQL

4. Algorithms
  - [ ] md5
  - [ ] aes256
  - [ ] sha1

5. Protocols
  - [ ] Telnet
  - [ ] SSH
  - [ ] FTP



## Python

Here are lists with one intruder. Please find it.

1. Versions
  - [ ] 2
  - [ ] 3
  - [ ] 4

2. Loops
  - [ ] foreach
  - [ ] for
  - [ ] while

3. Iterables
  - [ ] dict
  - [ ] tuple
  - [ ] list

## Web

Here are lists with one intruder. Please find it.

1. Semantic
  - [ ] `GET /index.php?id=123`
  - [ ] `GET /update.php?value=alpha&key=name&id=123`
  - [ ] `GET /servers/123`

2. Technologies
  - [ ] HTML/CSS/Javascript
  - [ ] Passenger/Ruby
  - [ ] Objective C/Xcode

3. Vulnerabilities
  - [ ] XSS
  - [ ] SQL Injection
  - [ ] AJAX

4. Rules
  - [ ] W3C
  - [ ] RestFul
  - [ ] MVC

5. Format
  - [ ] JSON
  - [ ] XML
  - [ ] TXT

## Code

### Python

1. Scopes
```
a = 4

def my_function(a):
    a = a + 8

my_function(a)

print(a)
```

2. Cursors
```
a = list()

def my_function(a):
    a.append(123)

my_function(a)

print(a)
```

3. Types
```
a = 123

def addition(a):
    return a + '1'

print(addition(a))
```

4. Loops
```
for i in [0, 1, 2, 3]:
    print(i)
```

```
for i in range(4):
    print(i)
```

```
for i in {0: 0, 1: 1, 2: 2; 3: 3}:
    print(i)
```

5. Built-in
  - [ ] `__eq__`
  - [ ] `__init__`
  - [ ] `__constructor__`

6. Types
` a = (1) `
  - [ ] len(i) == 1
  - [ ] isinstance(a, tuple)
  - [ ] a != '1'

7. Hashable
  - [ ] `a` is a list `a[0] = 0`
  - [ ] `a` is a dict `a['0'] = 0`
  - [ ] `a` is a tuple `a[0] = 0`
