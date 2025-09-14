# SpotifyWidget
A widget for OBS that displays the currently playing song on Spotify.

## URL Parameters

The widget supports several URL parameters for customization:

### style
Controls the visual appearance of the widget corners and album art.
- `style=1` (default): Rounded corners
- `style=2`: Square/sharp corners

### hideAlbumArt
Hides the album art and expands the song info area.
- Add `hideAlbumArt` to the URL (no value needed)

### duration
Sets how long the widget stays visible when a song starts playing (in seconds).
- `duration=5` - Widget shows for 5 seconds then hides
- `duration=0` (default) - Widget stays visible while music is playing

### Example URLs
Show widget with square corners:
```
https://.../spotifyWidget?client_id=YOUR_ID&client_secret=YOUR_SECRET&refresh_token=YOUR_TOKEN&style=2
```

Show widget with rounded corners, hide album art, and show for 10 seconds:
```
https://.../spotifyWidget?client_id=YOUR_ID&client_secret=YOUR_SECRET&refresh_token=YOUR_TOKEN&style=1&hideAlbumArt&duration=10
```

##

If you're not me and you have a question, you can contact me using the form [here](https://oblivionmedia.typeform.com/to/EwQYqmPa).