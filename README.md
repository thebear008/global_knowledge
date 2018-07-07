# Global knowledge

A few questions to test your global knowledge.

## Linux

Here are lists with one intruder. Please find it.

1. Code source
  - [ ] Git
  - [ ] IDE
  - [ ] SVN

2. Distributions still alive
  - [ ] Debian
  - [ ] CentOS
  - [ ] Mandriva

3. Packages
  - [ ] yum
  - [ ] rpm
  - [ ] deb

4. Default users
  - [ ] apache
  - [ ] root
  - [ ] superadmin

5. Commands
  - [ ] sudo
  - [ ] move
  - [ ] ls

6. Ports with unsafe protocols
  - [ ] 21
  - [ ] 22
  - [ ] 25

7. Agile
  - [ ] BCC
  - [ ] TDD
  - [ ] Scrum

8. Argument from command line

`bash toto.sh 28`

  - [ ] `[ -n "$0" ]`
  - [ ] `[ "$1" == 'toto.sh' ]`
  - [ ] `[ "$PARAM[1]" -eq 'toto.sh' ]`

9. Curl command
  - [ ] `curl -XPOST https://server.com/users`
  - [ ] `curl -L -k -s --data '{"key": "value"}' https://server.com/users`
  - [ ] `curl --post --insecure https://server.com/users`

10. Process list
  - [ ] `top`
  - [ ] `id`
  - [ ] `ps`

11. Help me
  - [ ] `mysql -h`
  - [ ] `man top`
  - [ ] `cp --help`

12. Search
  - [ ] `grep -rinI toto *.log`
  - [ ] `find . -type f -name '*.log' `
  - [ ] `sed s/toto// *.log `

13. Standards
  - [ ] `time python script.py 1>> file.log 2>> error.log`
  - [ ] `ps faux &1>2 file.log`
  - [ ] `echo "select name from users" | mysql > file.log 2>&1`

14. bash loops
  - [ ] while
```
while read LINE
do
  echo $LINE
done < file.log
```
  - [ ] foreach
```
foreach i in $(cat file.log)
do
  echo $i
done
```
  - [ ] for
```
for i in {0..10}
do
  echo ${i}
done
```

15. quote me

`MY_VAR=8  echo '${MY_VAR};22' | cut -d ';' -f1`

  - [ ] `22`
  - [ ] `8`
  - [ ] `${MY_VAR}`

16. Reading permissions
  - [ ] `cat /var/log/auth.log`
  - [ ] `tail  ~/file.log`
  - [ ] `tac /tmp/toto.log`

17. Change rights
  - [ ] `chmod 755 *.sh`
  - [ ] `chmod -p *.sh`
  - [ ] `chmod +x *.sh`

## Misc

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

4. Hash still OK for production
  - [ ] md5
  - [ ] sha256
  - [ ] sha512

5. Secured
  - [ ] HTTPS
  - [ ] SSH
  - [ ] FTP

6. Windows Server
  - [ ] 2000
  - [ ] 2010
  - [ ] 2016

7. Softwares
  - [ ] NetMeeting
  - [ ] Active Directory
  - [ ] OpenLDAP

8. Attributes
  - [ ] `cn`
  - [ ] `zn`
  - [ ] `dn`

9. Default Windows users
  - [ ] ROOT
  - [ ] ADMINISTRATOR
  - [ ] SYSTEM

10. DNS record
  - [ ] ALIAS
  - [ ] A
  - [ ] MX


11. Is JSON ?
  - [ ] `jsonize file.json`
  - [ ] `cat file.json | python -m json.tool`
  - [ ] `cat file.json | jq .`

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

3. Editable
  - [ ] dict
  - [ ] tuple
  - [ ] list

4. Loops

- [ ] using list

```
for i in [0, 1, 2, 3]:
    print(i)
```

- [ ] using range

```
for i in range(4):
    print(i)
```

- [ ] using dict
```
for i in {'zero': 0, 'one': 1, 'two': 2, 'three': 3}:
    print(i)
```

5. Built-in
  - [ ] `__constructor__`
  - [ ] `__eq__`
  - [ ] `__init__`

6. Types

` a = (1) `

  - [ ] `len(a) == 1`
  - [ ] `isinstance(a, int)`
  - [ ] `a != '1'`

7. Hashable
  - [ ] `a` is a list `a[0] = 0`
  - [ ] `a` is a dict `a['0'] = 0`
  - [ ] `a` is a tuple `a[0] = 0`

8. Check my code
  - [ ] pylint
  - [ ] flake8
  - [ ] pytest


## Web

Here are lists with one intruder. Please find it.

1. Semantic
  - [ ] `PATCH /users/abcdef/role/admin`
  - [ ] `DELETE /servers/123`
  - [ ] `GET /update.php?value=alpha&key=name&id=123`

2. Technologies
  - [ ] HTML/CSS/Javascript
  - [ ] Objective C/Xcode
  - [ ] Passenger/Ruby

3. Vulnerabilities
  - [ ] AJAX
  - [ ] XSS
  - [ ] SQL Injection

4. Set of rules
  - [ ] W3C
  - [ ] RESTFul
  - [ ] MVC

5. Format
  - [ ] JSON
  - [ ] TXT
  - [ ] XML

## Code

Write the result.

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

4. Try

```
key = 3
secrets = [ None, 1, 'abc', {}, (1,) ]

if secrets[key]:
    print('ok')
else:
    print('KO with value {}'.format(secrets['3']))
```

5. Interpretor

File `file.py` contains the following lines : 

```
#!/usr/bin/python

class MyClass(object):
    def __init__(self):
        self.name = 'jean'
        self.firstname = 'robert'


my_obj = MyClass()

print my_obj.name
```

We are executing 3 lines, what is the output ?

```
chmod 700 file.py
./file.py
python3 file.py
```

6. Decorator

```
from functools import wraps


def my_decorator(f):
    @wraps(f)
    def decoration(*args, **kwargs):
        print(args[1])
        return f(*args, **kwargs)
    return decoration


@my_decorator
def my_function(*args, **kwargs):
    if 'login' in kwargs:
        print('hello')
    else:
        print('bye')

my_function(123, 'abc', 'def', user='login', password='xxyy')
```

7. Exception

```
my_list = [1, 2, 3]


try:
    if my_list[3] > my_list[1]:
        print('here')
    else:
        print('there')
except ValueError:
    print('Error 1')
except IndexError:
    print('Error 2')
```

8. Requests

```
import requests

my_request = requests.request('post', 'https://google.ca')

if my_request.status_code == 200:
    print('ok')
elif my_request.status_code == 405:
    print('ok2')
else:
    print('ko')
```

9. JSON

```
import json

try:
    my_json = json.loads('{"key": [1, 2, 3]}')
except json.JSONDecodeError:
    print('try again')
```

10. Files

What is the output ?

```
rm -f /tmp/test.txt
cat << EOF > /tmp/test.py
with open('/tmp/test.txt', "w") as f:
    f.write("TEST")
EOF
for i in {1..3}
do
  python /tmp/test.py
done
cat /tmp/test.txt
```
