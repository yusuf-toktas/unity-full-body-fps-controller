# Full Body First Person Controller for Unity
This project implements a Full Body First Person Controller system in Unity. The controller allows players to see their entire character model (arms, legs, torso) in first-person view, enhancing immersion and interaction with the environment. The system is designed to be customizable, smooth, and realistic, supporting animation, physics, and inverse kinematics (IK).

## Features
* **Full Body Awareness**

  Players can see their entire character body from a first-person perspective, creating a more immersive experience.
  

* **Customizable Controls**
  
  The system allows for flexible control settings for walking, running, jumping, crouching, and other player movements.
  

* **Inverse Kinematics (IK) Integration**
  
  IK is used to enhance the realism of hand and foot placement, ensuring smooth interaction with the environment.
  

* **Animation Support**
  
  Compatible with Unity’s standard and custom animations, enabling easy integration of movement and interaction animations.
  

* **Smooth Camera Transitions**
  
  Designed to provide seamless camera transitions between player states, reducing player discomfort during movement.
  

* **Physics and Collision Detection**
  
  Fully integrated with Unity’s physics engine, ensuring accurate collision detection and interaction with the environment.
  

# Getting Started
## Prerequisites
**Before you can use this system, ensure that you have the following:**

* Unity 2020.3 or newer
* Basic knowledge of Unity's animation and physics systems
  
## Installation
1. Clone this repository:

**``git clone https://github.com/your-username/full-body-fps-controller.git``**

2. Open the project in Unity.

3. Import the necessary assets and packages from the Unity Asset Store (if applicable).

4. Attach the provided FullBodyFirstPersonController script to your player object.

5. Adjust the settings (camera, controls, animations) as per your project requirements.

# Usage
* You can customize the movement settings via the Unity Inspector by adjusting variables such as speed, jump height, and crouch behavior.
* Integrate custom animations by replacing the default animations with your own in the Animator Controller.
* Use IK targets to fine-tune hand and foot placements when interacting with objects or terrain.
  
# Contributing
Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch (``git checkout -b feature/YourFeature``).
3. Commit your changes (``git commit -m 'Add some feature'``).
4. Push to the branch (``git push origin feature/YourFeature``).
5. Open a pull request.
# License
This project is licensed under the MIT License – see the **[LICENSE]()** file for details.
