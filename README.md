# iterm2-scripts

The `multi-ssh.py` is a script that will read in a list of FQDN servers to SSH to and create a split window of all the connections. From there, you can go into broadcast mode (by default `cmd + shift + i`)

You can place the `multi-ssh.py` script anywhere on your machine but if you place it in the `~/Library/Application\ Support/iTerm2/Scripts/` directory, it will be under the `Scripts` drop down menu when using iTerm2. 

Make sure to update line 8 with the file location of the servers you want to SSH to. 

Example file formate is a FQDN per line of the file. 

```
example.com
example.net
```

For more information on the Python API package, visit https://www.iterm2.com/python-api/
