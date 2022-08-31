# Panoramica-Roadmap
### [Panoramica Repository](https://github.com/time-killer-games/Panoramica)

## Area System (frame system overhaul)

- Frames, Props, Hotspots, and Sounds will now be stored in .json files for a given area
- .json files will be stored in a given area's folder
  - run.ini will now be used to for setup purposes
    - Window Size and Location
    - The starting Area
    - Starting in Windowed or Fullscreen
  - Area Jsons will store information for configuring areas
    - Area Aspect Ratio
    - Starting Frame
    - Area Frames
      - Sound Channels
      - Prop Maps
      - Hotspot Maps
    - If it's in Debug mode or not
    - If it uses Panorama Mode or not
 - Full IDE for easily Creating and Editing areas
  - Full transform controls for Props and Hotspots
  - Setting area frames
  - Asset Browser
    - Importing Audio, Video, and Image files for use as props
  - Export as an Area folder

## General Features

## Props System

- Special Sprite Prop
  - Full free transform capabilities
  - Full tweening and spritesheet capabilities
  - Built in Hotspots
  - Option to appear above or behind the base panorama image
- Special Sound Prop that plays sound effects at specified point
  - Pans from one ear to the other depending on where the panorama view is
- Special UI Prop that creates an interactive gui that is part of the panorama
  - UI elements can run gml functions when interacted with
- Special Video Props that play videos and gifs that is part of the panorama
  - Option to appear above or behind the base panorama image
- Full Layering Capabilities for Sprite, UI, and Video Props
  - All props can be set to appear over or under another prop (including the base panorama)
- Full Scriptability for all props
  - Ability to change all parameters of props in gml code
  - Call functions and set parameters
