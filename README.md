# Pokemon-Emerald-HD
**An independent visual-enhancement frontend for Pokémon Emerald, powered by mGBA, SDL3 and OpenGL**  
*Bringing a new visual experience to Pokémon Emerald through enhanced rendering, atmospheric lighting, bloom, and an ambitious HD-2D-inspired aesthetic*  
> 🚧 Project Status: CURRENTLY IN DEVELOPMENT 
## Overview  
Pokémon Emerald HD is a Windows application built around the mGBA emulation core, designed to enhance the original Pokémon Emerald experience through a custom rendering pipeline.

The goal is to preserve the original game's visual identity while introducing modern graphical effects, atmospheric depth, and enhanced presentation.

Rather than modifying the original game, the project focuses on creating a separate application layer responsible for emulation, rendering, and visual enhancements.

### Features

mGBA-powered Game Boy Advance emulation

Custom SDL3 application frontend

OpenGL-based rendering pipeline

Enhanced shaders and post-processing

Bloom and atmospheric lighting (in development)

HD-2D inspired visual direction

Custom keyboard input mapping

## Screenshots  
*Screenshots and comparison images will be added as development progresses*

## Installation  
*Installation guide will be provided alongside the first public release*

### Requirements

Windows 10 or later

Pokémon Emerald game file

Supported graphics hardware with OpenGL compatibility

## Usage  
Launch the application with a compatible GameBoy Advance ROM 
`Pokemon-Emerald-HD.exe "path\to\game.gba"`

The application initializes the emulation core and renders the game through its custom graphics pipeline

## Technical Overview  
Pokémon Emerald HD is built using

| Technology | Purpose |
|------------|---------|
| C++        | Core app development |
| mGBA       | GameBoy Advance emulation |
| SDL3       | Window management, input and audio |
| OpenGL     | Graphics rendering |
| GLSL       | Custom shaders and visual effects |
| CMake      | Build config |

### Rendering Pipeline  
The project aims to introduce a custom rendering pipeline that enhances the original game's presentation without changing its underlying gameplay

Planned visual enhancements include:

Bloom and light scattering

Dynamic lighting effects

Atmospheric depth

Color grading and contrast adjustments

HD-2D-inspired visual effects

### Roadmap  

- [x] Initial windows application
- [x] SDL integration
- [x] OpenGL rendering initialization
- [x] mGBA core integration
- [x] Basic ROM loading
- [x] Audio integration and refinement
- [ ] Custom post-processing pipeline
- [ ] Enhanced lighting and bloom effects
- [ ] Atmospheric depth effects
- [ ] Performance optimization
- [ ] Public release

## Contributions  
Contributions, suggestions, and technical discussions are welcome

If you're interested in graphics programming, emulation, shaders, or game rendering, feel free to explore the project and participate in its development

## Donations  
Pokémon Emerald HD is an independent development project

If you enjoy the project and want to support its development, you can contribute through:  
[Ko-fi](https://ko-fi.com/chaisito/goal?g=0)  
[GitHub Sponsors](https://github.com/sponsors/chaisito)  

Every contribution helps support development, testing, and future improvements

## DISCLAIMER  

> [!IMPORTANT]
> Pokémon Emerald HD is an unofficial, independent fan project. It is not affiliated with, endorsed by, or associated with Nintendo, Game Freak, The Pokémon Company, or any of their subsidiaries
> Pokémon and all related trademarks and copyrighted materials belong to their respective owners
> This project does not distribute copyrighted game ROMs or original Pokémon game assets. Users must provide their own legally obtained game files


