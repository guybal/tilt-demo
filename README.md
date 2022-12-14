```shell
ytt template -f config/ --output-files manifest/

```

install tilt:
```shell
curl -fsSL https://raw.githubusercontent.com/tilt-dev/tilt/master/scripts/install.sh | bash
```

sudo usermod -aG docker $USER && newgrp docker