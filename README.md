# Player Controls in Xogot (Xogot 3D Tutorial)

This project contains the example scenes and assets used in the
**Xogot 3D Modular Series - Player Controls** tutorial by **Erin Uptegrove**.

It demonstrates how to set up basic 3D player movement in **Xogot** - the iPad and iPhone port
of the Godot Engine - using the virtual controller, custom input actions, a CharacterBody3D
movement script, and exported variables for tuning movement settings.

The project shows how to create a simple controllable 3D player that can move, strafe, and jump,
then adjust movement values while the game is running.

---

## Features

* Enable Xogot’s **Virtual Controller**
* Choose which onscreen controls to display
* Create a player movement script from the built-in **Basic Movement** template
* Understand the default **CharacterBody3D** movement script
* Use `_physics_process()` for smooth physics-based movement
* Handle gravity and jumping
* Read player movement from input actions
* Use `move_and_slide()` to move the player
* Create custom actions in the **Input Map**
* Add keyboard inputs such as W, A, S, and D
* Add joypad axis inputs for the left stick
* Use clear action names such as `move_forward`, `move_backward`, `move_left`, and `move_right`
* Update the movement script to use custom input actions
* Check the player’s facing direction and movement orientation
* Adjust the player collider
* Convert movement constants into exported variables
* Tune speed and jump velocity from the Inspector
* Use Remote view to adjust values while the game is running

---

## Notes

This project focuses on **introductory 3D player control workflows** in Xogot, not advanced
character controllers, camera-relative movement, combat controls, or full gameplay systems.

Key ideas demonstrated include:

* The virtual controller can be used to test touch-friendly controls directly in Xogot
* Input actions let a script respond to many input types without rewriting movement code
* Custom action names make scripts easier to understand and maintain
* Keyboard, controller, and virtual joystick inputs can all map to the same actions
* Player movement depends on the direction the character is facing
* Exported variables make it easy to tune gameplay values from the Inspector
* Remote view can be used to adjust values while previewing the running game

---

## Video Tutorial

Watch the full walkthrough on the [Xogot YouTube Channel](https://youtube.com/@xogot):
[Introduction to Player Controls in Xogot - Game Development in Godot on iPad](https://youtu.be/gpPGShiO64k)


---

## How to Use

1. Download or clone this repository:

   ```bash
   git clone https://github.com/xogot-projects/Xogot-Controls.git
   ```

2. Open the project in [Xogot](https://apps.apple.com/us/app/xogot-make-games-anywhere/id6469385251) on iPad or iPhone.

3. Explore the example scene and player setup.

4. Open the Project Settings and review the virtual controller and Input Map configuration.

5. Preview the project and test moving, strafing, and jumping.

6. Select the player in Remote view and experiment with movement values such as speed and jump velocity.

7. Review the player script to see how the input actions drive CharacterBody3D movement.

## Learn More

[Xogot](https://xogot.com)
[Documentation](https://docs.xogot.com/documentation/xogot/)
[Tutorials](https://docs.xogot.com/tutorials/xogot-tutorials/)

Built with Xogot on iPad
