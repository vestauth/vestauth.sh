![curl -sfS https://vestauth.sh/ | sh](https://vestauth.com/binary-banner.png)
```sh
curl -sfS https://vestauth.sh | sh
```
> [`vestauth`](https://github.com/vestauth/vestauth#readme) binary installer
>
> * [see usage](https://github.com/vestauth/vestauth#readme)

&nbsp;

## Install

```sh
curl -sfS https://vestauth.sh | sh
```

or self-execute this file:

```sh
curl -sfS https://vestauth.sh > install.sh
chmod +x install.sh
./install.sh
```

more install examples:

```sh
# curl examples
curl -sfS "https://vestauth.sh/" | sudo sh
curl -sfS "https://vestauth.sh/?version=0.44.0" | sh
curl -sfS "https://vestauth.sh/?directory=." | sh
curl -sfS "https://vestauth.sh/?directory=/custom/path&version=0.44.0" | sh

# self-executing examples
./install.sh --version=0.44.0
./install.sh --directory=.
./install.sh --directory=/custom/path --version=0.44.0
./install.sh --help
```

## Usage

see [`vestauth`](https://github.com/vestauth/vestauth) for extended usage guides.

---

#### more information

* alternatively, install with wget `wget -qO- https://vestauth.sh/install.sh | sh`
* make sure you are using `https`, not `http`. We do not redirect for trust reasons.
