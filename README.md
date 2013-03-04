## hbtrack

#### Installation
```
git clone https://github.com/zachallaun/hbtrack && cd hbtrack
chmod +x hbtrack
echo "alias hbtrack=$(pwd)/hbtrack" >> ~/.zshrc && source ~/.zshrc
```
Replace `.zshrc` as necessary.

#### Usage

```
hbtrack repo_name [repo_name ...]
```

`hbtrack` should be given the name(s) of one or more GitHub repositories that you own. The tool has no knowledge of local repositories, and does not need to be issued in any directory that you wish to track.

For instance, assuming that I've already entered my own credentials, I could track a few repositories that I own with the following:

```
hbtrack relative periphery.illogic am-interested connect-foe
```
