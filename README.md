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

### Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement". Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (git checkout -b feature/AmazingFeature)
3. Commit your Changes (git commit -m 'Add some AmazingFeature')
4. Push to the Branch (git push origin feature/AmazingFeature)
5. Open a Pull Request

### License
MIT License
