
# Install the autoconf ansible role

```bash
# Create a directory for the ansible role. 
install -d ~/.ansible/roles/computate.computate_autoconf

# Clone the autoconf ansible role. 
git clone git@github.com:computate-org/computate_autoconf.git ~/.ansible/roles/computate.computate_autoconf

# Change into the autoconf ansible role directory. 
cd ~/.ansible/roles/computate.computate_autoconf
```

# Run the autoconf ansible playbook to install autoconf locally. 

```bash
ansible-playbook install.yml
```

Christopher Tate
