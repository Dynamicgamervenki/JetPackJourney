
# 3D Platformer Game (Unreal Engine 5 - Blueprint Only)

A 3D platformer game created entirely using **Unreal Engine 5** and **Blueprints**. The game includes various platformer mechanics such as jumping, flying using a jetpack, moving objects, and collecting fuel for the jetpack.

## Features

- **Jumping Mechanics**: The player can jump to traverse platforms, avoid obstacles, and reach higher areas.
- **Jetpack Flying**: The player can fly in the air using a jetpack that consumes fuel. The jetpack provides limited flight time, requiring the player to find and collect fuel to keep using it.
- **Moving Objects**: Interact with objects in the environment, such as pushing and pulling to solve puzzles or clear paths.
- **Fuel Collection**: Collect fuel to recharge the jetpack, allowing the player to fly longer distances or reach difficult areas.

## Prerequisites

- **Unreal Engine 5** (latest version recommended)
- **Basic understanding of Unreal Engine 5** and **Blueprints**

## Installation

1. Clone the repository to your local machine:  
   ```bash  
   git clone https://github.com/Dynamicgamervenki/JetPackJourney.git
   ```  

2. Navigate to the project directory:  
   ```bash  
   cd 3DPlatformerGame  
   ```  

3. Generate project files:  
   - If you're using Windows, right-click the `.uproject` file and select **"Generate Visual Studio project files"**.  
   - Alternatively, you can use the command line:  
     ```bash  
     UnrealBuildTool.exe -projectfiles -project="3DPlatformerGame.uproject" -game -engine  
     ```  

4. Open the generated solution file (`.sln`) in your preferred IDE (e.g., Visual Studio or Rider).

5. Open the project in Unreal Engine 5:  
   - Double-click the `.uproject` file to open it in Unreal Engine.

6. Wait for the DerivedDataCache (DDC) files to generate. This may take a few minutes.

7. Play the game:  
   - Press **Play** in Unreal Engine to start testing the game mechanics.

## Gameplay

- **Jumping**: Press the jump button (usually **Spacebar**) to make the player character jump.
- **Jetpack Flying**: While in the air, hold the jetpack button (configured in the game settings) to activate the jetpack and fly. Keep an eye on your fuel gauge!
- **Moving Objects**: Approach movable objects and press the interact button (e.g., **E**) to push or pull them.
- **Fuel Collection**: Fuel pickups are scattered throughout the levels. Collect them to refill your jetpack's fuel.

## Future Features

- Add more levels with complex platforming challenges.
- Implement additional jetpack upgrades (e.g., increased fuel capacity or speed).
- Add new environmental hazards and obstacles for the player to overcome.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Unreal Engine 5 for providing the powerful tools to create this game.
- Community tutorials for helping me learn and implement platformer mechanics and Blueprints in Unreal Engine.
