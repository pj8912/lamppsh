# lamppsh
lampp commands for linux

Make the executable for `start`,`stop`,`restart` by running the 
following command

### Start
```
chmod +x lamppsh-start.sh
```

### Restart
```
chmod +x lamppsh-res.sh
```
### Stop
```
chmod +x lamppsh-stop.sh
```

Move the files to usr/local/bin:

### For Start
```
sudo mv lamppsh-start.sh /usr/local/bin/lamppsh-start
```
Do the same for restart and stop.

## Start Lampp Server
```
lamppsh-start
```

