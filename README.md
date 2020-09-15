# superset-notes

```
 # this may work for running apache superset on ubuntu 18.04

1  sudo apt-get update
2  sudo apt-get install -y git emacs-nox tmux vim
3  tmux
4  tmux a
5  sudo apt-get install -y build-essential libssl-dev libffi-dev python3-dev python3-pip libsasl2-dev libldap2-dev
6  sudo apt-get install -y python3-venv
7  python3 -m venv venv
8  . venv/bin/activate
9  pip install --upgrade setuptools pip
10  pip install apache-superset
11  superset db upgrade
12  export FLASK_APP=superset
13  flask fab create-admin
14  superset load_examples
15  superset init
16  superset run -p 8080 --with-threads --reload --debugger
17  superset run -p 8080 --with-threads
18  superset -V
19  superset -Version
20  superset --V
21  superset help
22  superset 
23  superset --version
24  superset version
25  superset run -p 8080 --with-threads


```
