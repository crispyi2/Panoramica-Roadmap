# Panoramica-Roadmap
### [Panoramica Repository](https://github.com/time-killer-games/Panoramica)

## Area System (frame system overhaul)

- Frames, Props, Hotspots, and Sounds will now be stored in .json files for a given area
  - run.ini will now be used to for setup purposes
    - Window Size and Location

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
