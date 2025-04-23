Para instalar, execute:
```
export GH_ACCOUNT=andreyev/lhc-infra
export GH_BRANCH=add_roles
export INSTALL_URL=https://raw.githubusercontent.com/andreyev/lhc-infra/refs/heads/add_roles/install.sh
curl -s $INSTALL_URL | sudo env INSTALL_URL="$INSTALL_URL" bash
```

Para depurar a instalação, adicione `-x` após o comando bash.
