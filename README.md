# Spotify

A fork of [orchis](https://github.com/canbeardig/Spicetify-Orchis-Colours-v2) with **Sweetpastel** colors.

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
  spicetify config SweetPastel
  spicetify apply
  ```

## Screenshots

![image](https://user-images.githubusercontent.com/65948476/182006248-0fe33cd3-a1be-4d8f-a4e2-39ac8cb595eb.png)
