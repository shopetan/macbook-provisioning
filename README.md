# macbook-provisioning
Provisioning tool for OSX

#Usage

First 

```
bash <(curl -fsSL https://raw.githubusercontent.com/IFTTT/dash/master/bin/bootstrap)
```

Second

```
git clone git@github.com:shopetan/macbook-provisioning.git
```

and

```
HOMEBREW_CASK_OPTS="--appdir=/Applications" ansible-playbook -i hosts -v localhost.yml -K
```

Finish!