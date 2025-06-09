# FleetMind 🚁🧮

*Where Vector Math Meets Virtual Drones*

A mesmerizing real-time simulation that brings Craig Reynolds' classic **boids algorithm** to life with a military twist! Watch hundreds of AI-powered UAVs dance through the sky using nothing but pure mathematics and emergent behavior.
[![Watch the FleetMind Demo](https://img.youtube.com/vi/7OG-RNmxKbE/maxresdefault.jpg)](https://www.youtube.com/watch?v=7OG-RNmxKbE "Click to watch FleetMind in action!")

## The Math Behind the Magic ✨

This isn't just pretty pixels moving around – it's computational biology in action! FleetMind implements several fascinating mathematical algorithms:

### **Reynolds' Flocking Algorithm** 
The heart of the simulation uses three fundamental vector calculations:
- **Cohesion**: Each drone calculates the center of mass of nearby neighbors and steers toward it
- **Separation**: Inverse-square distance calculations create repulsive forces to prevent collisions  
- **Alignment**: Velocity vector averaging helps drones match their neighbors' direction and speed

### **Hierarchical Command Structure**
Building on top of basic flocking, we've added military-inspired hierarchy using:
- **Weighted steering forces** that vary by rank (commanders > squad leaders > drones)
- **Distance-based authority gradients** with different influence radii for each command level
- **Multi-layered seek algorithms** for chain-of-command following

### **Advanced Vector Mathematics**
Every frame processes thousands of 2D vector operations:
- Vector normalization and magnitude calculations
- Distance-weighted force interpolation
- Velocity limiting using vector projection
- Real-time obstacle avoidance using repulsive force fields

## Why It's Fun 🎮

- **Interactive playground**: Click to add targets, watch the swarm intelligently coordinate
- **Real-time parameter tweaking**: Adjust the math coefficients and see instant behavioral changes
- **Multiple mission modes**: From tight formations to chaotic scatter patterns
- **Emergent complexity**: Simple rules create surprisingly sophisticated group behavior

## Quick Start

Just open `index.html` in your browser and watch the mathematical ballet unfold! No installation needed.

---

*Built for the pure joy of watching algorithms come alive. Perfect for anyone who finds beauty in computational emergence.*
