# mkcapsule
This is a client program of [capsule](https://github.com/TakutoYoshikai/capsule).

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
