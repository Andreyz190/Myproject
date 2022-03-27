## Ansible start
```bash 
  259  apt install ansible
  260  sudo apt install ansible
  261  ansible --version
  262  cd /etc/
  263  cd ..
  264  cd /etc/ansible/
  265  nano ansible.cfg
  266  ansible localhost -m ping
  267  ping 10.0.2.15
  268  ping 172.20.10.7
  269  nano ansible.cfg
  270  cd ..
  271  ls
  272  cd ansible/
  273  ls
  274  nano hosts
  275  sudo nano hosts
  276  nano hosts
  277  ansible client_pc -m ping -u client
  278  sudo nano hosts
  279  ansible client_pc -m ping -u client
  280  ssh-rsa
  281  cd ..
  282  ls
  283  cd home/
  284  ls
  285  a
  286  cd andreiz/
  287  ls
  288  cd ..
  289  ssh-copy-id client@172.20.10.7
  290  ansible client_pc -m ping -u client
  291  ansible client_pc -m ping -u
  292  ansible client_pc -m ping
  293  ansible client_pc -m ping -u client
  294  sudo nano hosts
  295  cd /etc/ansible/
  296  ls
  297  sudo nano hosts
  298  ansible client_pc -m ping -u client
  299  sudo nano hosts
  300  ansible client_pc -m ping -u client
  301  sudo nano hosts
  302  ansible client_pc -m ping -u client
  303  sudo nano hosts
  304  ansible client_pc -m ping
  305  sudo nano hosts
  306  ansible client_pc -m ping
  307  sudo nano hosts
  308  ansible client_pc -m ping
  309  ansible-inventory
  310  ansible-inventory --graph
  311  ansible-inventory --host
  312*
  313  ansible-inventory --graph
  314  ansible-inventory --myhost
  315  ansible-inventory --Myhost
  316  ansible-inventory --graph
  317  ansible-inventory --Myhost
  318  ansible-inventory --host Myhost
  319  apt-get install sshpass
  320  sudo apt-get install sshpass
  321  ansible client_pc -m ping
  322  cd ..
  323  nano /etc/ssh/ssh_config
  324  ansible client_pc -m shell -a 'cat /etc/os-release'
  325  ssh-copy-id ubuntu1@212.98.187.134:19
  326  ssh-copy-id ubuntu1@212.98.187.134
  327  ping 212.98.187.134
  328  ping 212.98.187.134:19
  329  ssh-copy-id 19 ubuntu1@212.98.187.134
  330  ssh-copy-id -19 ubuntu1@212.98.187.134
  331  ssh-copy-id -p 19 ubuntu1@212.98.187.134
  332  ssh-copy-id -p 20 ubuntu2@212.98.187.134
  333  ping -p 19 212.98.187.134
  334  ping -p 20 212.98.187.134
  335  ping -p 21 212.98.187.134
  336* ssh-copy-id -p 20 ubuntu2@212.98.187.134
  337  ping 192.168.100.243
  338  ping ubuntu2
  339* ping host
  340  cd ..
  341  cd /etc/ansible
  342  ls
  343  sudo nano hosts
  344  ansible stages_host -m shell -a 'cat /etc/os-release'
  345  sudo nano hosts
  346  ansible  production -m shell -a 'cat /etc/os-release'
  347  ansible stages_host -m shell -a 'cat /etc/os-release'
  348  ansible stages -m shell -a 'cat /etc/os-release'
  349  ansible staging -m shell -a 'cat /etc/os-release'
  350  sudo nano hosts
  351  ansible staging -m shell -a 'cat /etc/os-release'
  352  ansible staging -m ping
  353  ansible production -m ping
  354  cd
  355  ls
  356  cd myproject/
  357  mkdir 04.ansible
  358  mv 04.ansible 04.Ansible
  359  ls
  360  cd 04.Ansible/
  361  nano readme.md
  362  history
```
