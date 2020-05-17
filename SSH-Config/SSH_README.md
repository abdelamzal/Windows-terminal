# SSH Configuration

## Key-gen

    ssh-keygen -t rsa -b 4096 -C "your_email@example.com"

## Easy connection
 create a file conf into folder .ssh like below :

 Host    name-host-connection
    ForwardAgent yes
    HostName    @IP
    User    UserLogin
    Port    SSH-Port


## Connection command 

    ssh name-host-connection