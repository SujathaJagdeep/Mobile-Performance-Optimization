# Tic-Tac-Toe Starter Project

This project is part of [Udacity](https://www.udacity.com "Udacity - Be in demand")'s [VR Developer Nanodegree](https://www.udacity.com/course/vr-developer-nanodegree--nd017).

## Versions
- Unity 2018.4.0
- GVR Unity SDK v1.170.0

### GVR SDK for Unity
- `GoogleVR` > `Demos` is not included.
- `GoogleVR` > `GVRVideoPlayer.unitypackage` is included.
- The `Max Reticle Distance` value for the `GvrReticlePointer` used in the scene is set to `20` instead of the default `10`.
- Scripts applicable to the course have been updated to reflect Unity's API change from `UnityEngine.VR` to `UnityEngine.XR`.

>**Note:** If for any reason you remove and re-import GVR SDK for Unity v1.170.0, make sure you accept any API update pop-up prompts triggered by Unity. Alternatively, you can manually run the API updater (Unity menu `Assets` > `Run API Updater...`) after the import has completed.

### Description of the Maze Project 
The core tic-tac-toe gameplay mechanic still functions with start, restart, and AI moves. 
I have verified it by playing the game myself to check if it displays the "You Won", "You Lost", and "Draw", along with instructing the player to "Play Again".
Also, I see that the Robot moves its head while the player is playing the game and displays various emotions based on the final result of the player at the end of the game.

### Scripts
I do not see any infinite loops in the scripts. So, I think that the scripts are working fine. 

### Art
The project scene is completely optimized for mobile as the tris and verts range between 10,000k to 20,000k.

### Other (FPS)
The project scene is completely optimized for mobile as the game runs at 60FPS on my Android phone.

### Core Gameplay Mechanics
The core tic-tac-toe gameplay mechanic still functions with start, restart, and AI moves.

### Optimize Models
All high polygon models have been swapped for low polygon models.

### Optimized Textures
All individual materials for each object have been replaced with the provided atlas.

### Optimized Lighting
Non-moving models in the scene have been set to static, and the lighting in the scene to baked.

### My Reflection and Conclusion
- It took almost a week for me to complete the "Tic-Tac-Toe" project, as I worked very closely on it to ensure that it meets all the project specifications.
- I love working in Unity 3D, as I have keen interest to learn using it inside out. Therefore, I liked almost everything about the project.
- I really enjoy the fact that I was able to optimize the "Tic-Tac-Toe" project, along with learning some useful tactics to optimize the C# code for enhancing the FPS on mobile devices while playing the game.
