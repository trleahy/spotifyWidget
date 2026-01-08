# spotifyWidget
A widget for OBS that displays the currently playing song on Spotify. It supports both compact and full-screen layouts, with optional album art and customizable duration.

## URL Parameters

The widget supports several URL parameters for customization:

### style
Controls the visual appearance and layout of the widget.
- `style=1` (default): Rounded corners, compact layout
- `style=2`: Square/sharp corners, compact layout
- `style=3`: Full-screen layout with blurred background

### hideAlbumArt
Hides the album art and expands the song info area.
- Add `hideAlbumArt` to the URL (no value needed)

### duration
Sets how long the widget stays visible when a song starts playing (in seconds).
- `duration=5` - Widget shows for 5 seconds then hides
- `duration=0` (default) - Widget stays visible while music is playing

### Example URLs

**Compact widget with square corners:**
```
https://.../spotifyWidget?client_id=YOUR_ID&client_secret=YOUR_SECRET&refresh_token=YOUR_TOKEN&style=2
```

**Compact widget with rounded corners, hide album art, and show for 10 seconds:**
```
https://.../spotifyWidget?client_id=YOUR_ID&client_secret=YOUR_SECRET&refresh_token=YOUR_TOKEN&style=1&hideAlbumArt&duration=10
```

**Full-screen layout for streaming/OBS:**
```
https://.../spotifyWidget?client_id=YOUR_ID&client_secret=YOUR_SECRET&refresh_token=YOUR_TOKEN&style=3
```

**Full-screen layout without album art (text-only):**
```
https://.../spotifyWidget?client_id=YOUR_ID&client_secret=YOUR_SECRET&refresh_token=YOUR_TOKEN&style=3&hideAlbumArt
```

##

If you're not me and you have a question, you can contact me using the form [here](https://oblivionmedia.typeform.com/to/EwQYqmPa).