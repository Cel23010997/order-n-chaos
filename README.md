# Order N Chaos

**A tactical team game built with a custom C++ engine.** This repository presents Celeste Tong’s editor-tool and player-guidance contributions.

[Play the team-hosted browser game](https://tanukifurhire.com/play/order-n-chaos/) · [Portfolio case study](https://Cel23010997.github.io/projects/order-n-chaos.html)

**My role:** C++/ImGui hierarchy and animation tools; Lua tutorial and tooltip interfaces. **Team:** GGPals, nine collaborators. **Project period:** September 2025–April 2026.

## Start with these samples

- [Hierarchy panel](samples/GGEditor/src/Core/HierarchyNode.cpp): entity creation, duplication, selection and parent–child reorganisation.
- [Animation panel](samples/GGEditor/src/EditorAnimator/AnimationNode.cpp): sprite-sheet slicing, animation states, preview and export.
- [Tutorial manager](samples/GGProjects/Order%26Chaos/Assets/Scripts/m6_scripts/TutorialManager.lua): staged player guidance.
- [Tooltip scripts](samples/GGProjects/Order%26Chaos/Assets/Scripts/m5_scripts/AbilityTooltip): contextual ability information and visibility handling.

These are selected source samples, not a standalone engine checkout. They depend on the original team engine, assets and project configuration and cannot be compiled or run independently. Use the browser link to experience the game. The browser build is hosted by the team; this repository is my own contribution showcase.

## An example of iteration

In original commit `50d3db13`, pausing disabled tooltip hover and called its hide routine. That routine faded over time. Follow-up `b8e2d427` cleared the visible ability and fade state immediately and moved the tooltip off-screen, addressing the tooltip that could linger after hovering and pressing Escape. This describes the code change, not a measured usability result.

The original local history is preserved separately. This repository begins with an honest, privacy-reviewed source snapshot; original commits have not been recreated or backdated. Personal email addresses and student identifiers have been removed from public comments while authorship and copyright notices remain.

## Team and credits

GGPals: Tai Xiao Xuan (technical lead/networking), Abhishek Akilandeswari Patchamuthu (graphics), Zafir Haqqym (tools), Tan Jia Qi Trish (factory), Celeste Tong Jia Xuan (physics/animation editor and the contributions described here), Tok Duan Jie Nelson (input), Sim Wei Jun (product/mechanics), Xia Sirui (design/audio), and Quak Wen Xuan Rhonda (art).

The original DigiPen copyright notices remain applicable. This showcase does not grant an open-source license to the full team game or its assets.
