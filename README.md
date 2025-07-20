100 Years War

A dynamic and strategic sandbox for medieval fantasy warfare built on in-depth physics simulation.

**Overview:**
100 Years war is a game aiming to model medieval battles not through rigid animation scripting, but by simulating real physics. With a focus on things like armor, inertia, leverage, and momentum.

100 Years war is meant to explore how emergent tactics and battlefield chaos can arise from grounded systems.

**Desired Features:**

    Fully Simulated Combat:
    Comabat is physics-driven, with accurate mass, inertia, and impact response.

    Modular AI Behavior:
    Agents make decisions based on local threats, terrain, and formation discipline. Morale and fatigue matter.

    Equipment-Based Outcomes:
    Weapons interact with units realistically: weapons have mass and their impact can proportionally affect enemy formations.

    Dynamic and Mixed Formations & Unit Types:
    Infantry, cavalry, and skirmishers all can be mixed into groups to make unique and dynamic formations.

    Dynamic Terrain & Weather (Planned):
    Mud, hills, foliage, and fog change tactics and influence movement and visibility.

**Tech	Overview:**
Game engine: Unity
Core simulation code: C# / C++	
AI behavior scripting: Based on control systems theory and SLAM path planning
YAML / JSON	Data-driven unit definitions

**Repo Structure:**
/100YearsWar
├── /Physics             # Custom physics engine and logic
├── /GameEngine          # Core logic for how the overall game works on top of the physics engine
├── /Weapons             # Weapns defintions
├── /Units               # Behavior models for units, formations, fatigue/morale, etc.
├── /UI                  # Debug interfaces, camera controls, replay viewer
├── /TestScenes          # Testbeds for different scenarios
└── README.md

 Inspiration

    Mount & Blade – emergent battles and strategic control

    Total War – formation-based warfare

    Robitcs control systems - physics based interaction and path planning
