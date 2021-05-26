# mkcapsule
mkcapsule is a tool for saving secret data. capsule file is an executable file to extract encrypted data in the capsule file. The secret data is encrypted by MAC address of your PC automatically. You should separate and store the secret data and your PC.

### Requirements
* Ubuntu 20.10
* Rust
* Cargo

### Usage
**install**
```bash
git clone https://github.com/TakutoYoshikai/mkcapsule.git
cd mkcapsule
./install.sh
# register PATH
echo export PATH=$PATH:/path/to/mkcapsule/bin >> ~/.bashrc
```

**make a capsule**
```bash
mkcapsule <SECRET FILE>
# exported capsule file in current directory.
```

### License
MIT License
