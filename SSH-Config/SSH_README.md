# SSH Configuration

## Key-gen

    ssh-keygen -t rsa -b 4096 -C "your_email@example.com"

## Easy connection
 create a file conf into folder .ssh like below :
```config
 Host    name-host-connection
    ForwardAgent yes
    HostName    @IP
    User    UserLogin
    Port    SSH-Port
    IdentityFile C:\Users\nameuser\.ssh\id_rsa (Windows)
    IdentityFile ~/.ssh/id_rsa (Linux)
```

## Connection command 

    ssh name-host-connection