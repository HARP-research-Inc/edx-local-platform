# edx-local-platform
A local instance of the OpenEdx sandbox platform run by Tutor, stored within Docker.  

# packages/things to install
**IMPORTANT:**  
Make sure Docker Desktop is installed and running! (this is where the containers are located)  
  
The OpenEdx local and development platform runs on Tutor software, so make sure to install and upgrade it within a Python environment.    
```
cd tutor
source activate .venv/bin/activate
pip install "tutor[full]"
pip install --upgrade "tutor[full]"
tutor dev start &
```
Press 'enter' to see the terminal prompt again.  
  
The main sign-in page is at the following port:  
```
http://local.openedx.io:8000/
```
To log in as an admin, type *admin* into the username bar and *password* into the password bar.  
  
This is the dashboard, where all the courses are displayed.
<img width="1512" height="777" alt="Captura de pantalla 2025-08-14 a la(s) 9 15 36 a m" src="https://github.com/user-attachments/assets/eb35809d-df2a-4fc3-ac51-b4f48e87cd11" />  
  
To edit the course itself, go to this port:
```

http://apps.local.openedx.io:2001/authoring/home
```
<img width="1512" height="778" alt="Captura de pantalla 2025-08-14 a la(s) 9 19 12 a m" src="https://github.com/user-attachments/assets/e6849460-fcda-4e7b-bfbd-7f9cd9ba3e69" />
All courses made are listed here.
