# Ownership Manifest (Pattern S)

This document tracks which module is the **single writer** for each critical resource.

Example:

- WebGL geometry & materials → `WebGLBackground`  
- Stage lifecycle → `TheaterDirector`  
- Global app config → `ConfigStore`  

As systems grow, this doc becomes the “map” for who is allowed to mutate what.

