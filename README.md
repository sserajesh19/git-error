# git-error
git push error

Why getting this error

OpenSSH_8.2p1 Ubuntu-4ubuntu0.11, OpenSSL 1.1.1f  31 Mar 2020
debug1: Reading configuration data /etc/ssh/ssh_config
debug1: /etc/ssh/ssh_config line 19: include /etc/ssh/ssh_config.d/*.conf matched no files
debug1: /etc/ssh/ssh_config line 21: Applying options for *
debug1: Connecting to github.com [20.237.73.82] port 22.
debug1: Connection established.
debug1: identity file /home/user/.ssh/id_rsa type 0
debug1: identity file /home/user/.ssh/id_rsa-cert type -1
debug1: identity file /home/user/.ssh/id_dsa type -1
debug1: identity file /home/user/.ssh/id_dsa-cert type -1
debug1: identity file /home/user/.ssh/id_ecdsa type -1
debug1: identity file /home/user/.ssh/id_ecdsa-cert type -1
debug1: identity file /home/user/.ssh/id_ecdsa_sk type -1
debug1: identity file /home/user/.ssh/id_ecdsa_sk-cert type -1
debug1: identity file /home/user/.ssh/id_ed25519 type 3
debug1: identity file /home/user/.ssh/id_ed25519-cert type -1
debug1: identity file /home/user/.ssh/id_ed25519_sk type -1
debug1: identity file /home/user/.ssh/id_ed25519_sk-cert type -1
debug1: identity file /home/user/.ssh/id_xmss type -1
debug1: identity file /home/user/.ssh/id_xmss-cert type -1
debug1: Local version string SSH-2.0-OpenSSH_8.2p1 Ubuntu-4ubuntu0.11
debug1: Remote protocol version 2.0, remote software version babeld-9192804c
debug1: no match: babeld-9192804c
debug1: Authenticating to github.com:22 as 'git'
debug1: SSH2_MSG_KEXINIT sent
debug1: SSH2_MSG_KEXINIT received
debug1: kex: algorithm: curve25519-sha256
debug1: kex: host key algorithm: rsa-sha2-512
debug1: kex: server->client cipher: chacha20-poly1305@openssh.com MAC: <implicit> compression: none
debug1: kex: client->server cipher: chacha20-poly1305@openssh.com MAC: <implicit> compression: none
debug1: expecting SSH2_MSG_KEX_ECDH_REPLY
debug1: Server host key: ssh-rsa SHA256:uNiVztksCsDhcc0u9e8BujVUpIDTMczCvj3tD2s
@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
@       WARNING: POSSIBLE DNS SPOOFING DETECTED!          @
@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
The RSA host key for github.com has changed,
and the key for the corresponding IP address 20.207.73.82
is unknown. This could either mean that
DNS SPOOFING is happening or the IP address for the host
and its host key have changed at the same time.
@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
@    WARNING: REMOTE HOST IDENTIFICATION HAS CHANGED!     @
@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@

# To Resolve this error just follow this steps
 
Just create or rename the public key to `~/.ssh/known_hosts.pub`.

# Example : $ mv ~/.ssh/known_hosts.old ~/.ssh/known_hosts.pub

# Note: 

"I would be happy to help you with this error. If you need my assistance, please connect with me."
