  <p align="center">
  <a href="https://github.com/ALBINPRAVEEN/Spotify-Linux">
</p>


***

<center>
    <h4 align="center">A multi-featured adblocker for the Spotify Linux application.</h4>

        <strong>Last tested version:</strong> 1.1.99.878
    </p> 
</center>

### Features:

- Blocks all banner/video/audio ads within the app
- Blocks logging (Sentry, etc)
- Unlocks the skip function for any track
- Blocks Spotify automatic updates (optional)
- Hides podcasts, episodes and audiobooks on Home Screen (optional)

### Installation/Update:

NOTE: Spotify-Linux does not support the Spotify client from Snap 
- Close Spotify completely.
- Run The following command in Terminal:

```
bash <(curl -sSL https://raw.githubusercontent.com/ALBINPRAVEEN/Spotify-Linux/main/install.sh)
```

#### Optional Install Arguments:
`-c`  Clear app cache -- use if UI-related patches aren't working  
`-e`  Experimental features -- enables experimental features  
`-E`  Exclude feature -- disables specified feature(s) [currently only supports `leftsidebar`]  
`-f`  Force patch -- forces re-patching if backup detected  
`-h`  Hide podcasts, episodes and audiobooks on home screen  
`-o`  Old UI -- skips forced 'new UI' patch  
`-P`  Path directory -- manually set Spotify directory if not found in PATH  
`-p`  Premium subscription setup -- use if premium subscriber  

Use any combination of flags.  
The following example clears app cache, adds experimental features but excludes leftsidebar:
    
```
bash <(curl -sSL https://raw.githubusercontent.com/ALBINPRAVEEN/Spotify-Linux/main/install.sh) -ce -E leftsidebar
```


### Uninstall:

- Close Spotify completely.
- Run The following command in Terminal:

```
bash <(curl -sSL https://raw.githubusercontent.com/ALBINPRAVEEN/Spotify-Linux/main/uninstall.sh)
```

or

- Reinstall Spotify

### DISCLAIMER

- Ad blocking is the main concern of this repo. Any other feature provided by Spotify-Linux or consequence of using those features will be the sole responsibility of the user, not BlockTheSpot/Spotify-Linux/ALBINPRAVEEN/Spotify-Linux.

