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
