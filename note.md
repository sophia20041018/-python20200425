# #101
## #base64

```python
import base64
base64.b64encode(b"QnJlYWtBTExDVEZ7NTN1c1pRM2hXVzI1ZGNoWjdkWGV9")
b'UW5KbFlXdEJURXhEVkVaN05UTjFjMXBSTTJoWFZ6STFaR05vV2pka1dHVjk=
```
```python
a=[66 ,114, 101, 97, 107, 65 ,76 ,76 ,67 ,84, 70, 123, 65, 109, 118, 48, 117, 68, 121, 101, 114, 118, 80, 116, 109, 86, 114, 57, 83, 83, 83, 75, 125]
for i in a:
	print(chr(i),end" ")
  ```




# #PPC_Ez
## #hello world
```python
from pwn import *
ip = "120.114.62.214"
port =2405
r= remote(ip,port)
print(res)
```


## #3rd
```pythohn
from pwn import *
ip = "120.114.62.214"
port =2400
r= remote(ip,port)
r.recvuntil("Now you trun ")
r.recvuntil(" : ")
res = r.recvline()[:-1]
res = list(map(int, res.split()))
res sort()
print(res[-3])
r.interactive()
```


## #count
```python
from pwn import *
ip = "120.114.62.214"
port =2403
r= remote(ip,port)
for i in range(1,101):
	r.recvuntil("wave")
	r.recvuntil("?")
	r.sendline("str(i)")
r.interactive()
print(res)
```





