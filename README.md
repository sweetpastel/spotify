# spotify

a fork of [Spicetify-Orchis-Colours-v2](https://github.com/canbeardig/Spicetify-Orchis-Colours-v2) with **sweetpastel** colors

![image](https://user-images.githubusercontent.com/65948476/183907349-a1c2ac69-abb9-4d77-9098-61bcaa56dee6.png)

## installation

requirements:

- [``Spotify >v1.1.56``](https://www.spotify.com/us/download/)
- [``Spicetify``](https://spicetify.app)

setup:
 
1. clone this repository

  ```sh
  git clone https://github.com/sweetpastel/spotify
  cd spotify
  ```
  
2. copy the theme into the themes folder. 
  
  - gnu/linux: 
  
  ```sh
  cp -r SweetPastel ~/.config/spicetify/Themes/
  ```

  - macOS:

  ```sh
  cp -r SweetPastel ~/spicetify_data/Themes/
  ```
  
  - microsoft windows: 
  
  ```sh
  cp SweetPastel "$(spicetify -c | Split-Path)\Themes\"
  ```

3. apply the theme

  ```sh
  spicetify config SweetPastel
  spicetify backup apply
  ```
  
  ## acknowledgements
  
  - thanks to [``canbeardig``](https://github.com/canbeardig) for making the **Spicetify-Orchis-Colours-v2**
