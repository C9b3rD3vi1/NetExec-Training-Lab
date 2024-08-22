# NetExec-Training-Lab


NetExec is a tool for assisting in network service exploitation. It has tons of different modules for exploiting different kinds of network protocols, like RPC, SMB, and others like LDAP, WMI, SSH and FTP. 💥


You can find it online on Github, and the official documentation website:

    . https://github.com/Pennyw0rth/NetExec
    . https://www.netexec.wiki/

Their documentation includes this note:


This tool is based on CrackMapExec and was originally created by bytebleeder and maintained by @mpgn over the years, shout out to them! With the retirement of mpgn, we (@zblurx, @Marshall and @NeffIsBack) decided to maintain the tool NetExec, formerly known as CrackMapExec, as a completely free open source tool.

As mentioned, NetExec has support for a lot of different protocols:

            SMB
            SSH
            LDAP
            FTP
            WMI
            WINRM
            RDP
            VNC
            MSSQL

Often times, you'll interact with these using different sets of credentials, either with username or password pairing that you already know authenticate, or bruteforcing to uncover new access.

# Installing NetExec with pipx

    sudo apt install pipx git
    pipx ensurepath
    pipx install git+https://github.com/Pennyw0rth/NetExec


Now you should be able to run

    NetExec


or more simply:

    nxc