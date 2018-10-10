# SimpleCA

Bash Wrapper for Manual OpenSSL Certificate Authority commands.

Recommended for lab testing purposes and learning CA concepts.

--------
#### As root in /root/ directory

    Prepare Environment:
  1. `git clone https://gitlab.com/kat.morgan/simpleca.git`
  2. `mv /etc/openssl/openssl.cnf /etc/openssl/openssl.cnf.bak`
  3. `ln -sf ~simpleca/openssl.cnf /etc/openssl/`
  4. `cd /root/simpleca`

    Initialize Certificate Authority & Issue Certificate(s)
  1. `./init-ca`
  2. `./issue-cert`
