# wx_cms_v1
一个cms的微信小程序


git 操作：

Administrator@SKY-20171115MGZ MINGW64 ~
$ git config --global user.name "yelloohe"

Administrator@SKY-20171115MGZ MINGW64 ~
$ git config --global user.email "yelloohe@gmail.com"

Administrator@SKY-20171115MGZ MINGW64 ~
$ ssh-keygen -t rsa -C "yelloohe@gmail.com"
Generating public/private rsa key pair.
Enter file in which to save the key (/c/Users/Administrator/.ssh/id_rsa):
Created directory '/c/Users/Administrator/.ssh'.
Enter passphrase (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /c/Users/Administrator/.ssh/id_rsa.
Your public key has been saved in /c/Users/Administrator/.ssh/id_rsa.pub.
The key fingerprint is:
SHA256:c0j4lYqqhDVUijCOZRoyLR1JDZZU6SaQNJuntte3g58 yelloohe@gmail.com
The key's randomart image is:
+---[RSA 2048]----+
|BOOBo.           |
|OXOoo  .   .     |
|+*oo  . . o      |
| .+ o  + +       |
| ooo  . S .      |
|.o....   o       |
|........         |
| ... ...o        |
|  .   .E.        |
+----[SHA256]-----+

Administrator@SKY-20171115MGZ MINGW64 ~
$ eval "$(ssh-agent -s)"
Agent pid 11584

Administrator@SKY-20171115MGZ MINGW64 ~
$ ssh -add ~/.ssh/id_rsa
ssh: unknown option -- d
usage: ssh [-1246AaCfGgKkMNnqsTtVvXxYy] [-b bind_address] [-c cipher_spec]
           [-D [bind_address:]port] [-E log_file] [-e escape_char]
           [-F configfile] [-I pkcs11] [-i identity_file]
           [-J [user@]host[:port]] [-L address] [-l login_name] [-m mac_spec]
           [-O ctl_cmd] [-o option] [-p port] [-Q query_option] [-R address]
           [-S ctl_path] [-W host:port] [-w local_tun[:remote_tun]]
           [user@]hostname [command]

Administrator@SKY-20171115MGZ MINGW64 ~
$ ssh-add ~/.ssh/id_rsa
Identity added: /c/Users/Administrator/.ssh/id_rsa (/c/Users/Administrator/.ssh/id_rsa)

Administrator@SKY-20171115MGZ MINGW64 ~
$ ssh git@github.com
The authenticity of host 'github.com (192.30.253.112)' can't be established.
RSA key fingerprint is SHA256:nThbg6kXUpJWGl7E1IGOCspRomTxdCARLviKw6E5SY8.
Are you sure you want to continue connecting (yes/no)? yes
Warning: Permanently added 'github.com,192.30.253.112' (RSA) to the list of known hosts.
PTY allocation request failed on channel 0
Hi yelloohe! You've successfully authenticated, but GitHub does not provide shell access.
Connection to github.com closed.

Administrator@SKY-20171115MGZ MINGW64 ~
