## 🔴About
**Another Choice** is a 2.5D educational visual novel game. In this game, players follow the journey of a young woman with a unique dream: to become a news anchor delivering accessible news for people with disabilities. Despite setbacks, she discovers renewed hope and determination to overcome her weaknesses and pursue her goal. The game will teach players how to read and write a braille code by simulating word to braille and the other way around. 

What is Braille? Braille is the tactile system visually impaired uses understood by physical touch​. Braille consists of 63 different dot patterns, that are placed within six-dots cells. One of the uses of Braille is often seen in public facilities such as elevator buttons, public transportation, ATM machines and others.

<br>

## 🔥Development Process
- **Environment** <br> The game was built in High Definition Render Pipeline (HDRP), ensuring the best graphic our game can provide. For the lighting system, we use realtime global illumination. Then we add a reflection probe and post-processing to set a suitable mood for the game. To create the level design, we use the terrain tools to paint texture such as road and sidewalk textures. The environment assets we used can be bought here: [Unity Asset Store](https://assetstore.unity.com/packages/3d/environments/urban/tokyo-street-228474)
![image](https://github.com/Felixwijaya04/AnotherChoice_readme/blob/main/images/Screenshot%20(539).png)
- **Optimization** <br> Currently the game has been optimized by occlusion culling, draw call batching, LODs.
- **2D Characther** <br> Game ini menggunakan 2D character dengan 3D Environment. 2D character ini menggunakan Sprite Renderer, walaupun menggunakan character 2D tetap menghasilkan shadow menggunakan Shader Graph yang digunakan di Sprite Renderer
<br> ![image](https://github.com/Felixwijaya04/AnotherChoice_readme/blob/main/images/anotherChoice.png) ![image](https://github.com/Felixwijaya04/AnotherChoice_readme/blob/main/images/Shader%20Graph.png)
- **Day & Night Cycle** Sistem Day Night ini menggunakan Scriptable Object yang berisi data Day & Night seperti lighting, Sky.
<br> ![image](https://github.com/Felixwijaya04/AnotherChoice_readme/blob/main/images/SO%20Day%20night.png)


