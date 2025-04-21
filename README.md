# AnimationButton 

## Overview
AnimationButton is a Unity project showcasing interactive explosion effects using particle systems. The project features five effects—Flash Burst, Fireball, Debris, Smoke/Dust, and a combined Explosion effect—triggered via UI buttons. _Just as my own intro to particle systems in Unity without any guidelines_.  

**Made by**: Alinur Zhumadil  

## Features
- **Particle Effects**: Flash Burst, Fireball, Debris, Smoke/Dust, and a combined Explosion effect with sound.
- **Interactive UI**: Buttons to trigger each effect individually or the combined explosion.
- **Enhanced Rendering**: Utilizes Universal Render Pipeline (URP) for improved lighting and visuals.
- **Visual Effect Graph**: Includes a placeholder for a shockwave effect (ExplosionShockwave).
- **Scripts**: Custom C# scripts (`EffectController.cs` and `ExplosionController.cs`) to manage effect behavior.

## Project Structure
- **Assets/Scenes/**: Contains `TestScene.unity`.
- **Assets/Prefabs/**: Particle effect prefabs (`FlashBurstEffect`, `FireballEffect`, etc.).
- **Assets/Audio/**: Explosion sound (`ExplosionSound.wav`).
- **Assets/Scripts/**: C# scripts (`EffectController.cs`, `ExplosionController.cs`).
- **Assets/Materials/**: Materials for particle effects.

## Visual Output
This gif animation without audio, but you can still see how it works in total. As you can see I have divided animations on 6 buttons for show every step on creating animation:
- **FlashBurst** - **FireBall** - **Debris** - **SmokeDust** - **Sound** - **Explosion** (combined effect based on previous ones)
- ![Administrator_AnimationTestScene-TestScene-WindowsMacLinux-Unity66000 0 42f1_DX11_2025-04-2116-28-04-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/49c486a5-c2f6-430f-8a26-c5151ceff5d9)
