# Windows Subsystem for Linux

```
--distribution, -d <Distro>
        Run the specified distribution.

C:\Users\tuyen>wsl -l
Windows Subsystem for Linux Distributions:
Ubuntu (Default)
kali-linux
Ubuntu-18.04
```

```
--export <Distro> <FileName>
        Exports the distribution to a tar file.
        The filename can be - for standard output.

wsl --export Ubuntu d:\wsl\Ubuntu-20.04
```

```
--unregister <Distro>
        Unregisters the distribution and deletes the root filesystem.


```

```
--import <Distro> <InstallLocation> <FileName> [Options]
        Imports the specified tar file as a new distribution.
        The filename can be - for standard input.

        Options:
            --version <Version>
                Specifies the version to use for the new distribution.
       
D:\wsl>wsl --import Ubuntu Ubuntu2004 Ubuntu-20.04

```
