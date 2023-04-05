# Spotify

A fork of [orchis](https://github.com/canbeardig/Spicetify-Orchis-Colours-v2) with **SweetPastel** colors

![image](https://user-images.githubusercontent.com/65948476/183907349-a1c2ac69-abb9-4d77-9098-61bcaa56dee6.png)

## Installation

Requirements:

- [``Spotify >v1.1.56``](https://www.spotify.com/us/download/)
- [``Spicetify``](https://spicetify.app)

Setup:
 
- Clone this repository

  ```sh
  git clone https://github.com/SweetPastel/Spotify -b Orchis
  cd Spotify
  ```
  
- Copy the theme into the themes folder. 
  
  Linux / MacOS: 
  
  ```sh
  cp -r SweetPastel ~/.config/spicetify/Themes/
  ```
  
  Windows: 
  
  ```sh
  cp SweetPastel "$(spicetify -c | Split-Path)\Themes\"
  ```

- Apply the theme

  ```sh
  spicetify config current_theme SweetPastel
  spicetify apply
  ```
  
  ## Acknowledgements
  
  - Thanks to [``canbeardig``](https://github.com/canbeardig) for making the **Spicetify Orchis Theme**
