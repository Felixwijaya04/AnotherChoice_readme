## 🔴About
**Another Choice** is a 2.5D educational visual novel game. In this game, players follow the journey of a young woman with a unique dream: to become a news anchor delivering accessible news for people with disabilities. Despite setbacks, she discovers renewed hope and determination to overcome her weaknesses and pursue her goal. The game will teach players how to read and write a braille code by simulating word to braille and the other way around. 

What is Braille? Braille is the tactile system visually impaired uses understood by physical touch​. Braille consists of 63 different dot patterns, that are placed within six-dots cells. One of the uses of Braille is often seen in public facilities such as elevator buttons, public transportation, ATM machines and others.

<br>

## 🔥Development Process
- **Environment** <br> The game was built in High Definition Render Pipeline (HDRP), ensuring the best graphic our game can provide. For the lighting system, we use realtime global illumination. Then we add a reflection probe and post-processing to set a suitable mood for the game. To create the level design, we use the terrain tools to paint texture such as road and sidewalk textures. The environment assets we used can be bought here: [Unity Asset Store](https://assetstore.unity.com/packages/3d/environments/urban/tokyo-street-228474)
![image](https://github.com/Felixwijaya04/AnotherChoice_readme/blob/main/images/Screenshot%20(539).png)
- **2D Characther** <br> In our game, we seamlessly blend 2D and 3D objects within the same scene. Our character, portrayed as a 2D sprite image, casts shadows thanks to a custom shader created using Shader Graph and applied to the character’s sprite renderer.
![image](https://github.com/Felixwijaya04/AnotherChoice_readme/blob/main/images/anotherChoice.png) ![image](https://github.com/Felixwijaya04/AnotherChoice_readme/blob/main/images/Shader%20Graph.png)
- **Day & Night Cycle** <br> This game feature allow the game to change the time dynamically based on the player game progress. The system is made with scriptable objects to store and alter the game data such as lighting, sky color and post processing.
![image](https://github.com/Felixwijaya04/AnotherChoice_readme/blob/main/images/SO%20Day%20night.png)
- **Optimization** <br> Currently the game has been optimized by occlusion culling, draw call batching, LODs.


