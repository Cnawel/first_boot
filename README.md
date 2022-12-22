# first_boot
Python script that makes all the necessary apt installs, updates and upgrades, tested on Debian 11

V1.0:
  - Run scripts separetely. From 1 to 5.
  - 
  - The order of the facts DOES alterate the product.
  - 
  - 1 **Network**: Set Hostname, set Static IP, set gateway, set DNS
                   Set Mail send/receive
                   IP TABLES: - SSH - VNC. OPT: Block by external IP
      
  - 2 **Usermod** : Create 2 groups: admin, user
                    Create root (root), radmin (admin-root), testuser(basic)
                    OPT: Del root access from external
                    
  - 3 **APT**: GIT: Install, set config: user.name, user.email
               DOCKER: Install, config, networks
               VIM:
               
