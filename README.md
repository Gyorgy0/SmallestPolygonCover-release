This program demonstrates several types of the hill climbing optimization algorithm. The program displays the steps and the fitness of the solution
(in this case the circumference of the polygon). It's written in Rust, using egui and it's framework (eframe).
The webpage is a compiled WASM binary, it uses WebGL, so it's pretty performant.

Implemented hill climbing variants:
- Stochastic
- Steepest ascent (one node)
- Steepest ascent (all nodes) 
- Stochastic + Simulated cooling (iteration limit)
- Stochastic + Simulated cooling (constant)
- Stochastic + Simulated cooling (fitness dependent)
