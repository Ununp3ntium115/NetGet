Here are the core classes, functions, and methods that will be necessary:

1. NetworkScanner: This class will handle the network scanning, finding active ports and routers.
2. ProtocolHandler: This class will handle the different protocols (TCP, UDP, FTP, SSH).
3. Authenticator: This class will handle the different types of authentication (LDAP, Kerberos, HTTPS to Azure).
4. PacketRelay: This class will handle the packet relay, including finding active ports that a router is currently attached to.

Now, let's start with the entrypoint file for the backend server:

This concludes the backend part of the implementation. The frontend part in Swift is beyond the scope of this task.```bash
# a) Install dependencies
python3 -m venv venv
source venv/bin/activate
pip install -r backend/requirements.txt

# b) Run all necessary parts of the codebase
FLASK_APP=backend/main.py flask run &
```
# a) Install dependencies
python3 -m venv venv
source venv/bin/activate
pip install -r backend/requirements.txt

# b) Run all necessary parts of the codebase
FLASK_APP=backend/main.py flask run &
