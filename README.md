jenkinsctl
===========

Start &amp; Stop Jenkins daemon on Mac OS X

## Usage
start jenkins deamon  
```
jenkinsctl start
```

stop jenkins deamon  
```
jenkinsctl stop
```

## Instllation
1. Check out jenkinsctl into `~/.jenkinsctl`.  
````
$ git clone git://github.com/shoyan/jenkinsctl.git ~/.jenkinsctl
````

2. Add `~/.jenkinsctl/bin` to your `$PATH` for access to the `jenkinsctl` command-line utility.  
```
$ echo 'export PATH="$HOME/.jenkinsctl/bin:$PATH"' >> ~/.bash_profile
```

3. Reload `~/.bash_profile`  
```
$ source ~/.bash_profile
```

## License

(The MIT license)

Copyright (c) 2014 Shohei Yamasaki
