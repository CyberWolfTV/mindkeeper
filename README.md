# mindkeeper
Helps u to remind passwds u want to store in ur head only.

## Installation
```
sudo apt install python3
sudo apt install python3-pip
pip3 install pwinput
pip3 install pycryptodome
# dependencies done...
git clone https://github.com/CyberWolfTV/mindkeeper.git
cd mindkeeper
chmod +x mindkeeper
sudo mv mindkeeper /bin/mindkeeper
cd ..
rm -rf mindkeeper
mindkeeper --help
```

## How and Why?
- Learn ur passwds by using em more often.
- It will ask u for passwords and will tell u wether they are correct or not.
 It knows wether they are  correct or not even though it cant see the passwds.
 When u enter em first they will get encrypted and hashed.
- Is it possible to recover the passwds?
  - No, the hashes of the encrypted passwd could only get bruteforced if someone knows the master key.
  - Even if they know the masterpasswd and have a direct hash of the passwd they couldnt tell wether urs is really the one they have a hash of.
- If u have passwds which u dont want to save or write down u need to use them often to not forget em, for this reason i made this script.
