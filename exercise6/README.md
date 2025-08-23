# Exercise 6  

## Task  
- Create 3 users on a Linux system: **Mary**, **Joseph**, and **John**  
- Create a file named `index.js`  
- Assign different permissions to each user on this file:
  - John → Read  
  - Joseph → Write  
  - Mary → Execute  

## Steps  

### 1. Create Users  
```bash
sudo adduser mary
sudo adduser joseph
sudo adduser john
```

### 2. Create File 
```bash

touch index.js
```
### 3. Assign Permissions
``` bash
# john → Read
sudo setfacl -m u:mary:r-- index.js

# Joseph → Write
sudo setfacl -m u:joseph:-w- index.js

# mary → Execute
sudo setfacl -m u:john:--x index.js
```

### 4. Verify Permissions
``` bash
getfacl index.js
```