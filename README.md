## Snow Boarder - Unity 2D Game Project

### Overview
This project is a 2D snowboarding game developed using Unity as part of a Udemy course taught by Rick Davidson. The game, titled "Snow Boarder," features a player-controlled character navigating a smooth, challenging track with jumps and obstacles. The primary goal is to reach the finish line without crashing.

### Features
- **Smooth Gameplay**: The game offers a relaxing and smooth player experience with the core mechanic being to avoid crashing.
- **Dynamic Movement**: Players can move along the track, rotate forwards and backwards, and speed up.
- **Particle Effects**: Special effects play when the snowboarder touches the ground, enhancing the visual experience.
- **Crash Detection**: If the player crashes, the level restarts.
- **Finish Line**: Crossing the finish line restarts the level, signaling the player's success.

### Game Mechanics
1. **Movement**: The snowboarder moves along the track with smooth transitions.
2. **Rotation**: Players can control the rotation of the snowboarder to navigate jumps and obstacles.
3. **Speed Boost**: Players can increase their speed using specific inputs.
4. **Particle Effects**: Visual effects triggered upon certain actions, such as touching the ground or crashing.
5. **Crash Detection**: When the snowboarder crashes, the game detects it and restarts the level.

### Technical Implementation
- **Sprite Shapes**: Used to create the level layout, providing a visually appealing and functional track.
- **Edge Colliders**: Implemented to ensure the snowboarder interacts correctly with the track.
- **Cinemachine**: Utilized for camera management, creating smooth camera transitions and following the player character.
- **Surface Effector 2D**: Applied to the track to simulate the snowboarder’s movement along the surface.
- **Torque Rotation**: Implemented to allow the snowboarder to rotate in response to player inputs.
- **Crash Detector Script**: Custom script to handle the logic when the snowboarder crashes.
- **Invoke Method**: Used to create delays and manage timing for certain game actions.
- **Particle System**: Integrated to produce effects like snow trails and crash particles, enhancing the visual feedback.
- **Audio Effects**: Added to create an immersive experience with crash and finish line sounds.

### Development Steps
1. **Character Setup**: Adding and configuring the snowboarder character.
2. **Level Design**: Using sprite shapes to design the initial level layout.
3. **Camera Setup**: Adding and configuring Cinemachine for smooth camera transitions.
4. **Movement Mechanics**: Implementing basic movement and rotation controls.
5. **Crash and Finish Detection**: Creating scripts to handle crashes and level completion.
6. **Particle Effects**: Setting up particle systems for visual effects.
7. **Audio Integration**: Adding sound effects for crashes and level completion.
8. **Polishing**: Regular tuning and testing to improve gameplay feel and visual aesthetics.

