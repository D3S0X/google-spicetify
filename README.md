# google-spicetify
Spotify with Google style

## My Changes
- Improved color schemes
- Volume always visible
- Style download progress, offline indicator, tracklist sort arrow
- Remove artist page separator line
- Round selected item end like selected playlist
- Round artist page popular tracks cover image
- Move left sidebar a bit up
- Hover to view friend list

## Previews
Using `Base` color scheme

#### Home
<img src="./screenshots/home.png" alt="img" align="center" width="600px">

#### Artist
<img src="./screenshots/artist.png" alt="img" align="center" width="600px">

#### Playlist
<img src="./screenshots/playlist.png" alt="img" align="center" width="600px">

## How to install
1. Install [spicetify-cli](https://github.com/khanhas/spicetify-cli) and make sure it applies default theme succesfully.
2. Run these commands:
  
**Linux and MacOS** in Bash:
```bash
cd "$(dirname "$(spicetify -c)")/Themes"
git clone https://github.com/D3S0X/google-spicetify
```

**Windows** in Powershell:
```powershell
cd "$(spicetify -c | Split-Path)\Themes"
git clone https://github.com/D3S0X/google-spicetify
```

3. Finally, run:
```
spicetify config current_theme google-spicetify
spicetify apply
```

There are 7 color schemes you can choose: `Base`, `DarkWater`, `DarkBlue`, `LightGreen`, `LightWater`, `LightBlue`, `Gow`. Change scheme with commands:
```
spicetify config color_scheme <scheme name>
spicetify apply
```

## Color schemes preview

#### Base

See [Previews section](#Previews)

#### DarkWater
<img src="./screenshots/dark_water.png" alt="img" align="center" width="600px">

#### DarkBlue
<img src="./screenshots/dark_blue.png" alt="img" align="center" width="600px">

#### LightGreen
<img src="./screenshots/light_green.png" alt="img" align="center" width="600px">

#### LightWater
<img src="./screenshots/light_water.png" alt="img" align="center" width="600px">

#### LightBlue
<img src="./screenshots/light_blue.png" alt="img" align="center" width="600px">

#### Gow
<img src="./screenshots/gow.png" alt="img" align="center" width="600px">