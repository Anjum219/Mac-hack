1. Download the installer file from [here](https://dotnet.microsoft.com/en-us/learn/languages/fsharp-hello-world-tutorial/install)
2. Type `dotnet` in a __new__ terminal and if you get error 'dotnet command not found` try to locate the directory in your system (step 3-)
3. 
```
cd /usr/local/share/dotnet/
ls
```
Do `cd` and `ls` to find the dotnet file. In my case it's location was `/usr/local/share/dotnet/x64/dotnet`

4. Now create a symbolic link of that file in `/usr/local/bin/` by
```
ln -s /usr/local/share/dotnet/x64/dotnet /usr/local/bin/
```


Proper installation would show the following after typing `dotnet`
```
Usage: dotnet [options]
Usage: dotnet [path-to-application]

Options:
  -h|--help         Display help.
  --info            Display .NET information.
  --list-sdks       Display the installed SDKs.
  --list-runtimes   Display the installed runtimes.
```
