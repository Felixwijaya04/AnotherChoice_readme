### Another Choice

![image](https://github.com/Felixwijaya04/Felixwijaya04/blob/main/images/Gif_Another_Choice%20(1).gif)

## 🔴About Game
**Another Choice** is a 2.5D educational visual novel game. In this game, players follow the journey of a young woman with a unique dream: to become a news anchor delivering accessible news for people with disabilities. Despite setbacks, she discovers renewed hope and determination to overcome her weaknesses and pursue her goal. The game will teach players how to read and write a braille code by simulating word to braille and the other way around. 

What is Braille? Braille is the tactile system visually impaired uses understood by physical touch​. Braille consists of 63 different dot patterns, that are placed within six-dots cells. One of the uses of Braille is often seen in public facilities such as elevator buttons, public transportation, ATM machines and others.

## 📋 Project Info

<b> Developed with Unity 2022 </b>

| **Role** | **Name** | **Development Time** 
|:-|:-|:-|
| Game Designer | Felix Wijaya | 2 weeks |
| Lead Game Programmer | Mario Valent Wibowo | 2 months |
| Second Game Programmer | Felix Wijaya | 2 months |
| 2D Artist & Animator | Vincent Tanujaya | 2 months |
| Environment Artist | Felix Wijaya | 2 months |
<details>
  <summary> <b>Contribution as (Game Designer)</b> </summary>
  
  - Game design
  - Story writer
  - Level design
  
</details>
<details>
  <summary> <b>Contribution as (Lead Game programmer)</b> </summary>
  
  - Game Movement
  - Camera Behaviour
  - Braille Mechanic
  - Day & Night Cycle
  - Shadow Optimization
  - Dialogue System
  
</details>

<details>
  <summary> <b>Contribution as (Second Game programmer)</b> </summary>
  
  - Audio programming
  - Game settings
  - Graphic optimization
  
</details>
<details>
  <summary> <b>Contribution as (Environment Artist)</b> </summary>
  
  - Make a city design using the 3D assets provided
  - Responsible for lighting & composition
  
</details>

## 📜 Scripts

|  Script       | Description                                                  |
| ------------------- | ------------------------------------------------------------ |
| `DayHandle.cs` | Responsible for changing the sky and light between day and night cycle |
| `DayState.cs`  | Responsible for tracking day progress |
| `LetterBehaviour.cs`  | Responsible for converting keyboard inputs into braille character |
| `IHDRIsky.cs`  | Scriptable object class used to store sky data |
| `SoundManager.cs`  | Manages all audio sources and allowing player to change the volume settings  |
| `etc`  |
<br>

## 🔥Development Process
- **Environment** <br> The game was built in High Definition Render Pipeline (HDRP), ensuring the best graphic our game can provide. For the lighting system, we use realtime global illumination. Then we add a reflection probe and post-processing to set a suitable mood for the game. To create the level design, we use the terrain tools to paint texture such as road and sidewalk textures. The environment assets we used can be bought here: [Unity Asset Store](https://assetstore.unity.com/packages/3d/environments/urban/tokyo-street-228474)
![image](https://github.com/Felixwijaya04/AnotherChoice_readme/blob/main/images/Screenshot%20(539).png)
- **2D Characther** <br> In our game, we seamlessly blend 2D and 3D objects within the same scene. Our character, portrayed as a 2D sprite image, casts shadows thanks to a custom shader created using Shader Graph and applied to the character’s sprite renderer.
![image](https://github.com/Felixwijaya04/AnotherChoice_readme/blob/main/images/anotherChoice.png)
- **Optimization** <br> Currently the game has been optimized by occlusion culling, draw call batching, LODs. This optimization brings a significant changes to the game performance, an increase of 20 fps was made after occlusion culling was enabled.
<br>![image](https://github.com/Felixwijaya04/AnotherChoice_readme/blob/main/images/Screenshot%202024-10-08%20161844.png)


