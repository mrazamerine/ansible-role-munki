# Ansible role – Munki

Ansible role for setting up a [munki](https://github.com/munki/munki) server.


## Variables

* **keepalive_timeout_seconds**  – Keepalive timeout length (in seconds) for nginx (int) [300]

* **munki\_http\_password** – Password for HTTP Basic Authorization (string)

* **munki\_ssl\_cert\_path** – Path to SSL certificate (string)

* **munki\_ssl\_privkey\_path** – Path to SSL certificate private key (string)
