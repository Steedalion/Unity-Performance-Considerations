# Unity-Performance-Considerations

1. Use the correct Unity project template.
2. Use URP for mobile, VR, etc.
3. ECS can be better for mobile battery and a high number of agents.
4. For multiplayer instances consider slowing down propogating effects (death).
5. Poor VR performance leads to motion sickness.
6. Stick to target fps (30 mobile, 90 VR)
7. Use Optimize occationally in development cycle. Use profiler.
8. Disable raycast in unused buttons.
9. Don't import unused assets, they seem to find there way into builds.
10. Pool when there are many.
11. Reduce texture and image quality when needed. This can be automated.
12. Stream music from storage.
13. TMPro can be more efficient than unity UI.
14. Use occlusion culling. Design small rooms or screen spaces.
15. Send only information that is needed (via network).
