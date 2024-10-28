👋 Hello there! I'm Jai.

My flagship project is [Samarium](https://github.com/jjbel/samarium), a 2-d physics simulator and rendering engine. It channels my love of computer graphics, high performance computing, and physics simulations. It can simulate particle systems, rigid-body collisions, and softbodies. It is written in modern C++20 (with 23 support upcoming) and runs on 64-bit Windows and Linux.

I'm currently improving Samarium with:
- solving differential equations on a grid, for example fluid simulation
- optimizing short-range forces (gravity/lennard jones), using quadtrees and hash grids
- adding GPU support using OpenGL compute shaders, and CUDA, for all the above
- In future, I plan to support cloth simulations, chemical reactions, and add 3D support.


[rocket-ui](https://github.com/jjbel/rocket-ui) : A telemetry app for [IIT-B's Rocket Team](https://iitbrocketteam.in/), built using samarium.

I've also messed around with [Vulkan](https://github.com/jjbel/HelloVulkan) and [Rust's WGPU](https://github.com/jjbel/learning-wgpu).

My other projects/interests:

Arduino:
- [DIY Exercyle](https://github.com/jjbel/exercycle) : converting a bicycle to an exercycle, with a rev counting app.
- [LED Animations](https://github.com/jjbel/ArduinoLED) : cool RGB animations using LED strips.

Frontend stuff, especially using electron and svelte-js:
- [rocket-ui-js](https://github.com/jjbel/rocket-ui-js) : Svelte version of rocket-ui
- [my personal site/resume](https://github.com/jjbel/resume)
- [a ram and net usage widget](https://github.com/jjbel/watcher)

Scripting utilities in python
- [large-file-finder](https://github.com/jjbel/large-file-finder) : cleanup your disk easily
- [pyreload](https://github.com/jjbel/pyreload) : run scripts when files change
- [thor](https://github.com/jjbel/thor) : yet another build system for C++

I'm currently learning functional programming, particularly in Lean4, Haskell and OCaml.

I love math/sciencey animations, and was inspired by: 
- 3Blue1Brown: manim, Summer of Math Exposition
- Dan Shiffman (legend): Processing and Coding Train
- Mathologer, Minutephysics, Veritasium

---

My philosophies:
1. Open source for the win:
   
    FOSS and the surrounding community and online resources carry me through my developer journey.
    I've followed the development of the linux kernel, and Blender.
3. Keep things simple and lightweight.
   
   As Colin Chapman put it, "Simplify, then add lightness”. Modern apps are way too bloated, slow, and complex.
   
   For the wonders that optimization can work, see [Kaze](https://youtu.be/Ca1hHC2EctY)'s work on Super Mario 64.
   
   [KRAZAM](https://www.youtube.com/c/KRAZAM) and [Programmers are also human](https://www.youtube.com/@programmersarealsohuman5909)
   have some hilarious sketches on microservices and the bane of the javascript ecosystem.
   
4. Memory  bottlenecks are the biggest reason for slow performance in modern apps.

   CPU performance has always been growing (even ignoring "Moore's Law is dead"), but memory speed has saturated.
   Improve your datastructures first to utilize cache locality and branch prediction, before micro-optimizing other aspects.
   
