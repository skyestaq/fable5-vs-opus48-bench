> Create a physics simulation as a single self-contained HTML file with all JavaScript and CSS inline. No external libraries, no CDN imports, no build step.
>
> The simulation: a large regular hexagon rotating at a constant speed around its center, with 10 balls of varying sizes and colors bouncing inside it.
>
> Requirements:
> 1. Gravity acts on all balls.
> 2. Balls collide with the hexagon walls realistically, accounting for the walls' rotational motion when computing bounce angles.
> 3. Balls collide with each other with momentum transfer based on their sizes.
> 4. Slight energy loss on every collision so the system settles naturally rather than accelerating.
> 5. No ball may ever pass through a wall or another ball.
> 6. Runs at a smooth frame rate using requestAnimationFrame, and remains stable for at least 5 minutes without balls escaping, jittering, or the simulation exploding.
> 7. Include a restart button and a slider that controls hexagon rotation speed live.
>
> Render on an HTML canvas sized to the viewport. Dark background, visually clean. Write the collision math with brief comments explaining your approach. Deliver the complete file, then stop. Do not ask clarifying questions; make reasonable assumptions and state them in a comment block at the top of the file.
