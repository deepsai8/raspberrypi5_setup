# raspberrypi5_setup
some initial configs for raspberry pi 5

### install these before anyting else:
```bash
sudo apt update
sudo apt install openssl libssl-dev
openssl version -a
```

and

```bash
sudo apt install -y \
    build-essential \
    libbz2-dev \
    libncurses5-dev \
    libncursesw5-dev \
    libffi-dev \
    libreadline-dev \
    libsqlite3-dev \
    liblzma-dev \
    zlib1g-dev \
    tk-dev \
    libgdbm-dev \
    libnss3-dev \
    libssl-dev \
    uuid-dev \
    wget \
    curl \
    llvm \
    libncurses-dev \
    xz-utils \
    tk-dev \
    libxml2-dev \
    libxmlsec1-dev
```

### homebrew
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

### pyenv
```
curl -fsSL https://pyenv.run | bash
```

### Ollama installation
```bash
curl -fsSL https://ollama.com/install.sh | sh
```

### Terminal tools
```bash
sudo apt-get install btop
sudo apt install duf
sudo apt install ncdu
```

### Other utilities
```bash
curl wttr.in/City
sudo snap install musikcube
sudo apt install googler
```

https://terminaltrove.com/list/
