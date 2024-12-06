# parrot-update
to resolve this problem in parrot update apply this:-
1- sudo nano /etc/apt/source.list
add this link in it and comment other 
```deb http://mirrors.mit.edu/parrot/ rolling main contrib non-free```

and save file and try update by this command 
```sudo apt-get update -o Aquired::ForceIPv4=True && sudo apt-get upgrade -o Aquired::ForceIPv4=True```

Then just wait for the process. It might takes a few minutes.

Hopes this help!!

