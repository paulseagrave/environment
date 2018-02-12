# Some useful setup commands

```bash
sudo apt-get update
```

# Python and PIP
```bash
sudo apt-get install python3
sudo apt-get install python-pip
```

# AWS CLI
```bash
sudo pip install awscli
aws help
sudo pip install groff # May be needed if aws help complains
sudo pip install less  # May be needed if aws help complains
```

# Git
```bash
git config --global push.default simple
git clone git@github.com:paulseagrave/environment.git
git remote add origin https://github.com/paulseagrave/environment.git
cd environment
echo '#Environment' > README.md
git add README.md
git commit -m "Initial commit"
git push origin master
```