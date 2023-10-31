# IZHV-Exercise05-2021

Solution for the 5th assignment from the course _'[IZHV (Introduction to Game Development)](https://www.fit.vut.cz/study/course/250838/)'_ for the academic year 2021/22 at VUT FIT. \
Řešení 5. úkolu z předmětu _'[IZHV (Základy herního vývoje)](https://www.fit.vut.cz/study/course/250838/.cs)'_ pro akademický rok 2021/22 na VUT FIT.

## Task: Animation in 2D

[Full Assignment Description](http://cphoto.fit.vutbr.cz/ludo/courses/izhv/exercises/e5/)

**Description:**
Create animations for whimsical characters using Unity’s 2D Animation system.

**Instructions:**

1. **Setup:**

   - Download project template from the Materials section.
   - Switch to 2D mode in Unity.
   - Use WASD + Space for character movement.

2. **Controlling Animation:**

   - Use the Animator component to play Animation Clips.
   - Correct the main character's movement animation.

3. **Character Orientation:**

   - Adjust character direction based on movement.
   - Enhance animations for various character states.

4. **Animator Interface:**

   - Explore the SpelunkyAnimationController.
   - Understand Layers, Parameters, and the Main View.

5. **Character Preparation:**
   - Import and prepare a new character sprite.

---

**Animating the Character Guide**

**1. Preparatory Phase**:

- Place `Assets/Prefabs/Characters/Rikr` prefab in the scene.
- Unpack Rikr GameObject.
- Set its position.
- Manage the `RikrSprite`.

**2. Animator Controller Setup**:

- Create `RikrAnimationController`.
- Assign and open Animator UI.
- Add required parameters.

**3. Crafting Animation Clips**:

- Open Animation window.
- Create and complete various animation clips.

**4. Implementation**:

- Convert Rikr GameObject to a prefab.
- Replace in the Character Selector script.
- Test character swapping and set up Animator Controller.

**5. Final Steps**:

- Finalize animations and scene hierarchy.
- Submit the exercise.

**FAQ**:

- **Rikr disappears in-game**: Use the appropriate prefab and remove Player Control components.
- **New animations malfunction**: Check attributes and fix missing ones.

## Result

TBD

## Evaluation

Total points: **6/6**
