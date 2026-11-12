# Stepping off the shortest path: crafting believable character navigation

Slides for the talk by **Richard Kogelnig** ([Havok](https://www.havok.com/)) at the [AI and Games Conference 2026](https://www.aiandgamesconference.com/schedule/stepping-off-the-shortest-path-crafting-believable-character-navigation/).

Presented on 11 Nov 2026.

## Downloads

- [Slides (PPTX, 228 MB)](https://github.com/rikogeln-havok/HavokAig26Presentation-stepping-off-the-shortest-path/raw/main/AIG26%20-%20Richard%20Kogelnig%20-%20Stepping%20off%20the%20shortest%20path%20-%20speaker%20notes.pptx): includes videos and speaker notes (containing references).
- [Slides (PDF, 10 MB)](https://github.com/rikogeln-havok/HavokAig26Presentation-stepping-off-the-shortest-path/raw/main/AIG26%20-%20Richard%20Kogelnig%20-%20Stepping%20off%20the%20shortest%20path%20-%20speaker%20notes.pdf): includes speaker notes (containing references).

## Summary

Shortest-path algorithms come from robotics and produce robotic behaviour when used directly: characters cut corner to corner, walk into danger, and crowds form "conga lines" toward their target. This talk covers how to build believable paths on top of a navigation solution:

- How navmesh face shapes and topology influence pathfinding results
- A* cost modification and filtering, and their performance pitfalls (flood filling)
- Handling many characters sharing paths, and selecting alternative paths
- What string-pulled shortest paths can and cannot provide
- Path smoothing, keeping paths away from obstacles, and better turning behaviour
- Integrating with animation systems such as motion matching: path and trajectory prediction
