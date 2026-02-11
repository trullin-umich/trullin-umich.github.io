(Trent Mullin)
# The Legend of Zelda – First Dungeon Recreation (Unity)

A recreation of the first dungeon from the original *The Legend of Zelda*, built in Unity as a top-down 2D adventure game inside a 3D environment — featuring a custom gameplay mechanic: **Keese Mode**.

> Game Portfolio Project  
> EECS 494 – Introduction to Computer Game Design  
> University of Michigan  

---

## About the Project

This project is a faithful recreation of the first dungeon from the original NES *Legend of Zelda* game, rebuilt in Unity using C#.

Our three-person team divided responsibilities across:

- **Player systems**
- **Enemy systems**
- **Environment & dungeon mechanics**

I was primarily responsible for:

- Implementing coroutine-based room transitions between dungeon chambers  
- Designing and implementing environmental mechanics  
- Creating power-up systems  
- Contributing to the logic behind our custom **Link → Keese transformation system**
- Designing and building a custom demo map to showcase the Keese mechanic

---

## Custom Feature: Keese Mode

A unique mechanic we added to the classic formula.

When equipped, Link can transform into a Keese (bat):

- Fly over water
- Access vent-based passageways
- Evade enemies from above
- Navigate with restricted visibility using a “blind bat” effect

This mechanic required custom collision logic, layer manipulation, sprite transitions, and coroutine-driven transformation effects.

---

## Technical Details

- **Engine:** Unity  
- **Language:** C#  
- **Version Control:** Git (GitHub Desktop) with GitLab repository  
- **Project Management:** Jira sprint planning  
- **Architecture Highlights:**
  - Coroutine-driven room transitions
  - Layer-based physics control for flying mode
  - State-based transformation system
  - Tilemap slicing and environment reconstruction

---

## What I Learned

This project strengthened my understanding of:

- Real-time game state management
- Coroutines for visual and mechanical transitions
- Collaborative version control workflows
- Structuring gameplay systems in Unity
- Designing mechanics that extend classic gameplay without breaking balance

Working in a team environment on a structured milestone schedule provided valuable experience in collaborative development and production pacing.

---

## Play the Demo

You can try the finished build here:

https://trullin.itch.io/trullin-zelda-dungeon

Thank you for checking it out!
