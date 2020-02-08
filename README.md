# pop-mail-client

### Intsall PoPa3d

```bash
sudo apt-get install popa3d
```
or if you have a root permissions 
```bash
apt-get install popa3d
```
### Start service
```bash
sudo service popa3d start
``` 
or if you have a root permissions
```bash
service popa3d start
```
let's verify that this service is running now.
```bash
sudo service popa3d status
```
or
```bah
service popa3d status
```
### Running de python script

```bash
python3 pop-mail-client.py
```
where ....
```python
server = "127.0.0.1" # Your Local IP address
user = "equinockx"   # Your user
password = "example" # your password
```
