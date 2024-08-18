# mdenergy_updated
## Steps for installation
### Step 1 : Extract the mdenergy folder present in my repo.
![image](https://github.com/user-attachments/assets/d3f3e702-2d73-4d9f-986a-1d64942de680)  
### Step 2: Open terminal in src folder and enter the command “make linux”.
![image](https://github.com/user-attachments/assets/a8d23faf-4899-4d1d-b2cb-276e3ede83bc)

If you get the output below there is no error enjoy life.
![image](https://github.com/user-attachments/assets/2c53edc6-9653-4f29-adb7-8dd94bed3618)

### Step 3: Enter the command in terminal “mkdir -p ~/vmd/tcl”
### Step 4: Enter the command in terminal “sudo make install” 
![image](https://github.com/user-attachments/assets/beb540ef-24dd-4de4-84e0-a28c0888b01e)

If you got the output below then the installation is done and do your stuff my debugging is done
![image](https://github.com/user-attachments/assets/df923261-37ac-438a-9797-b11422825ae5)
<hr>  

### Edits Made in src folder:
If you want the details of the errors solved its just replacing 
```
#include<iostream.h>
```
with 
```
#include<iostream> 
using namespace std;
```
In each file present in src folder 
Also replace 
```
#include<iomanip.h>
```
With 
```
#inlcude<iomanip>
```
Add ```#include <cstring>``` in Energies.C  
Add ```#include <cstdlib>``` in hbondpsf.C  
Replace ```#include<new.h>``` with ```#include<new>``` in ResizeArrayRaw.h	
