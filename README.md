## zigup
A tiny script helps you to install different versions of Zig

### Usage
Clone the Git repo and run zigup
```sh
git clone https://github.com/rilysh/zigup
cd zigup && ./zigup

# Now the script will create a directory called "zig" in your /home/<USER>
# or $HOME directory. By default, zigup will install development build of 
# Zig. You can download specific version, by specifying zigup 0.10.0. Run 
# zigup --list-previous to get a list of stable and older versions of Zig.
```
