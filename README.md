# Battle of Trafalgar - San Ildefonso Simulation

An interactive D3.js simulation of the historic Battle of Trafalgar (October 21, 1805) with special focus on the Spanish ship San Ildefonso.

## Features

### Realistic Ship Design
- **Detailed Ship Models**: Each ship features realistic hull designs, multiple masts with sails, rigging, cannon ports, and national flags
- **Fleet Differentiation**: 
  - Spanish Fleet (Red) - Including the flagship San Ildefonso (Gold highlight)
  - French Fleet (Blue) 
  - British Fleet (Dark Blue)
- **Ship Classes**: First Rate ships of the line, Ships of the Line (74-136 guns), with accurate historical data

### Historical Accuracy
- **60 Ships Total**: Based on actual fleet compositions at Trafalgar (27 British, 18 French, 15 Spanish)
- **San Ildefonso Focus**: 74-gun Spanish ship of the line with historically accurate movements and combat role
- **Nelson's Tactics**: British ships attack in two perpendicular columns breaking the Franco-Spanish line
- **Cape Trafalgar**: Accurate coastline representation of the Spanish coast

### Battle Mechanics
- **Real-time Combat**: Ships fire cannons with realistic reload times, accuracy affected by distance and morale
- **Damage System**: Visual health bars, progressive damage affecting ship performance
- **Sinking Animations**: Dramatic explosion effects with debris and ship sinking sequences
- **Morale System**: Combat fatigue affects accuracy and performance over time

### Interactive Features
- **Battle Controls**: Start, pause, reset, and speed control (1x, 2x, 4x)
- **Focus System**: Click any ship or use "Focus San Ildefonso" to zoom in and highlight
- **Ship Information**: Hover over ships to see detailed stats (guns, crew, health, morale, combat status)
- **Real-time Status**: Battle progression, time tracking, casualty reports, and San Ildefonso specific updates

### Visual Effects
- **Water Animations**: Continuous water ripples and wake effects
- **Cannon Fire**: Muzzle flashes, cannonball trajectories, and smoke clouds
- **Combat Effects**: Hit explosions, debris scatter, and battle smoke
- **Wind Indicators**: Visual representation of the southwest wind affecting the battle

## How to Use

1. **Open** `index.html` in a web browser
2. **Start Battle** - Click "Start Battle" to begin the simulation
3. **Focus on San Ildefonso** - Use the dedicated button or click on the golden ship
4. **Interactive Exploration** - Hover over ships for details, click to focus
5. **Control Speed** - Adjust simulation speed for detailed observation or overview
6. **Reset** - Return to initial positions to replay the battle

## Historical Context

The San Ildefonso was a 74-gun third-rate ship of the line of the Spanish Navy, built in 1785. During the Battle of Trafalgar, she was part of the Combined Fleet's line of battle and engaged multiple British ships including HMS Defiance. The simulation accurately represents:

- Her position in the Spanish line
- Combat with British ships breaking through
- The eventual outcome of the battle
- Historical damage and casualties

## Technical Details

- Built with D3.js v7
- SVG-based ship rendering with detailed graphics
- Force simulation for realistic ship physics
- Dynamic combat system with probabilistic outcomes
- Responsive design supporting different screen sizes

## Controls

- **Start Battle**: Begin the historical simulation
- **Pause**: Pause the current battle
- **Reset**: Return to pre-battle positions
- **Focus San Ildefonso**: Center view on the featured Spanish ship
- **Speed Toggle**: Cycle through 1x, 2x, and 4x speed multipliers

Experience one of history's most famous naval battles with unprecedented detail and interactivity!