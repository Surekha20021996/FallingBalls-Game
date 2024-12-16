# Falling Balls-Game
1. Objective
The goal of the Falling Balls game is to provide an engaging and interactive experience where players use their mouse to slice falling balls while avoiding bombs. The game challenges the player’s hand-eye coordination and quick reaction skills, progressively increasing in difficulty.

**<h3>2. Features</h3>**

<br>**2.1 Core Features**

**Ball Slicing**:

Players slice balls by dragging the mouse across the screen.
Successfully slicing a ball grants points, and visual effects such as splitting or disappearing indicate success.

**Bomb Avoidance**:

Red balls act as bombs.
Slicing a bomb ends the game immediately, increasing the difficulty.

**Scoring System**:

Players earn points for slicing balls.
The score is displayed on the screen in real-time.

**Timer**:

A countdown timer is included, challenging players to score as much as possible before time runs out.
Increasing Difficulty:

The game progressively increases in difficulty, with faster falling balls and more bombs appearing over time.

<h3> 2.2 Additional Features</h3>


**Combo System** :

Players can earn bonus points for slicing multiple balls in quick succession.
For example, slicing three balls in a short time grants additional combo points.

**Pause/Resume Functionality**:

The game can be paused and resumed, allowing players to take breaks without losing progress.

<h3> 2.3 Excluded Features</h3> 

Multiplayer mode.

Advanced power-ups like time freeze or bonus points.

Online leaderboards.

Mobile platform implementation.

<h3>3. Scope</h3> 

**Boundaries**:
A single-player game implemented in Java.

Focuses on improving hand-eye coordination and quick reaction times.

Limited to desktop platforms.

**Inclusions**:

Ball slicing, bomb avoidance, scoring, timer, and increasing difficulty.

Combos and pause/resume options for an enhanced user experience.

**Exclusions**:

Mobile and online functionalities, advanced power-ups, and multiplayer modes.



<h3> 4. Technical Requirements</h3>
4.1 **Technology Stack**:

Programming Language: Java.
Frameworks: Java Swing for GUI design and mouse interaction.

**Libraries**:
JUnit for testing game features.
Java Timer for managing timed events.

4.2**Tools**

IDE: Any Java IDE (e.g., IntelliJ IDEA, Eclipse, NetBeans).
Version Control: Git for tracking and managing code changes.

<h3>5. Game Design</h3>

5.1 **Gameplay Flow**:

The game starts with balls falling from the top of the screen.
Players slice balls using the mouse, earning points for each successful slice.
Bombs appear randomly; slicing a bomb ends the game.
The timer counts down, and the game ends when the time reaches zero or the player slices a bomb.

5.2 **Visual Feedback**:

Sliced balls disappear or split in half.
Bomb explosions occur upon slicing, with visual or audio feedback indicating game over.


<h3>6. Scoring and Difficulty</h3>

6.1 **Scoring System**:
+1 point for each ball sliced.
Bonus combo points for slicing multiple balls quickly.

6.2 **Difficulty Progression**:
Balls fall faster as the game progresses.
The frequency of bombs increases over time.

<h3>7. Testing Plan</h3>

**Unit Testing**:

Use JUnit to test core game mechanics like ball slicing, bomb detection, and scoring.

**GUI Testing**:

Validate visual elements, such as ball animations and score display.

**Performance Testing**:

Ensure smooth gameplay even as difficulty increases.


<h3>8. User Manual</h3>

**Starting the Game**:

Run the game application.
Use the mouse to slice balls.

**Controls**:
Drag the mouse to slice falling balls.

**Game Rules**:
Slice balls to earn points.
Avoid slicing bombs to continue the game.

**Winning and Losing**:
Win by achieving a high score before the timer runs out.
Lose by slicing a bomb or when time runs out.
