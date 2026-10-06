# Blazium starters

One folder is one loop you can extend. Each starter is its own public repository.

Shared controls: WASD or the left stick moves. Space or the south gamepad button leaps. Escape or Start pauses. F, left click, or the west gamepad button is the primary action.

Editor MCP is http://127.0.0.1:6506/mcp. Game MCP is http://127.0.0.1:6507/mcp. Only one starter can use those ports at a time.

Download the editor from [blazium.app/download](https://blazium.app/download) or `blazium-cli install latest-release`. Open one starter folder.

Support for a starter is that repository's issues. Engine bugs go to [blazium-games/blazium](https://github.com/blazium-games/blazium/issues). Store, account, and payment issues go to [blazium-games/support](https://github.com/blazium-games/support/issues) or [blazium.games/support](https://blazium.games/support). Status: [status.blazium.games](https://status.blazium.games).

| Folder | Use it when |
| --- | --- |
| [template_3d_empty](https://github.com/blazium-games/template_3d_empty) | A blank 3D root. Add a camera and mark it current before you build on this. Next: `scenes/stage.tscn`. |
| [template_2d_empty](https://github.com/blazium-games/template_2d_empty) | A blank 2D root. Add a camera and make it current before you build on this. Next: `scenes/sheet.tscn`. |
| [template_android](https://github.com/blazium-games/template_android) | A blank phone root. A panel under the status bar is rejected. Next: `scenes/panel.tscn`. |
| [template_ios](https://github.com/blazium-games/template_ios) | A blank phone root. A panel under the notch is rejected. Next: `scenes/panel.tscn`. |
| [template_web](https://github.com/blazium-games/template_web) | A blank page root. Input before the page has focus is rejected. Next: `scenes/page.tscn`. |
| [template_platform_menu](https://github.com/blazium-games/template_platform_menu) | One sheet that runs the Android, iOS, and Web rules. An unknown example is rejected. Next: `scenes/board.tscn`. |
| [template_3d_basic](https://github.com/blazium-games/template_3d_basic) | One camera, one light, and one floor. Next: `scenes/annex.tscn`. |
| [template_3d_fps_movement](https://github.com/blazium-games/template_3d_fps_movement) | First-person walk, mouse look, and jump inside a box arena. Shift sprints. Next: `scenes/ramp.tscn`. |
| [template_3d_city](https://github.com/blazium-games/template_3d_city) | A short block street and a walker. Block widths come from a seed. Next: `scenes/cross.tscn`. |
| [template_3d_controller](https://github.com/blazium-games/template_3d_controller) | Orbit a walker and take one shot at a crate. A second shot before the yard refill is rejected. Next: `scenes/yard.tscn`. |
| [template_2d_platformer](https://github.com/blazium-games/template_2d_platformer) | Run and jump one level. The goal does not count while the runner still overlaps the hazard. Next: `scenes/span.tscn`. |
| [template_3d_platformer](https://github.com/blazium-games/template_3d_platformer) | Jump onto one platform and reach the goal. A second jump in the air is rejected. Next: `scenes/rise.tscn`. |
| [template_2d_dungeon](https://github.com/blazium-games/template_2d_dungeon) | Sixteen seeded carvers, from rooms and caves through Prim's and the other mazes. The exit also needs a token. Next: `scenes/inner.tscn`. |
| [template_3d_dungeon](https://github.com/blazium-games/template_3d_dungeon) | The same sixteen carvers drawn as boxes. The exit also needs a token. Next: `scenes/deeper.tscn`. |
| [template_2d_push_puzzle](https://github.com/blazium-games/template_2d_push_puzzle) | Slide one crate onto one plate. A push into a wall or a blocker is rejected. Next: `scenes/board_two.tscn`. |
| [template_3d_fps_combat](https://github.com/blazium-games/template_3d_fps_combat) | Look and shoot one target. Primary fires. Leap reloads only at zero rounds. Next: `scenes/second_mark.tscn`. |
| [template_3d_lan](https://github.com/blazium-games/template_3d_lan) | Local ENet host and join, one spawn marker, and one hit. A port outside 1 to 65535 is rejected. Next: `scenes/pit.tscn`. |
| [template_2d_tower_defense](https://github.com/blazium-games/template_2d_tower_defense) | One lane, one defender, one spend. Primary places. Leap marches. A place you cannot afford is rejected. Next: `scenes/bend.tscn`. |
| [template_2d_survivor](https://github.com/blazium-games/template_2d_survivor) | Move inside a spawn region. Primary admits one foe, grants XP, and upgrades at the threshold. Next: `scenes/pick.tscn`. |
| [template_3d_vehicle](https://github.com/blazium-games/template_3d_vehicle) | Walk a short seeded road and enter one car. A second enter while seated is rejected. Next: `scenes/stretch.tscn`. |
| [template_2d_metroidvania](https://github.com/blazium-games/template_2d_metroidvania) | Two rooms and a gate. Primary takes the dash. Leap crosses only after the dash is owned. Next: `scenes/room_b.tscn`. |
| [template_3d_exploration](https://github.com/blazium-games/template_3d_exploration) | Orbit, walk, and pick up one token into a four-slot pack. Drop the oldest item to store a fifth. A blank id is rejected. Next: `scenes/grove.tscn`. |
| [template_3d_card_battle](https://github.com/blazium-games/template_3d_card_battle) | Elixir regenerates. Primary deploys on your half and strikes the tower. Leap plays the costly card. Next: `scenes/result.tscn`. |
| [template_3d_racing](https://github.com/blazium-games/template_3d_racing) | Drive one oval. Hold stride north. A lap counts only after the mid stripe, then the start stripe. Next: `scenes/finish.tscn`. |
| [template_2d_turn_battle](https://github.com/blazium-games/template_2d_turn_battle) | Three steps north enter a fight. Primary strikes. Leap guards. An action on the other side is skipped. Next: `scenes/fight.tscn`. |
| [template_3d_coop](https://github.com/blazium-games/template_3d_coop) | Two local bodies with different health pools. Primary applies a host hit. Leap tries a client hit and is rejected. Next: `scenes/roster.tscn`. |
| [template_2d_menus](https://github.com/blazium-games/template_2d_menus) | Main, pause, settings, credits, save, and load as separate Control scenes you can copy. Three slots reject a bad index, a bad version, and an overwrite without confirm. Next: `scenes/play_stage.tscn`. |
| [template_3d_menus](https://github.com/blazium-games/template_3d_menus) | The same menus as lit 3D panels with a current camera. Copy one board scene and its script. Slots and prefs match the 2D starter. Next: `scenes/play_yard.tscn`. |

## Blazium Engine

[Blazium Engine](https://blazium.app) is the free MIT game engine. [Blazium Games](https://blazium.games) is a separate store. A game on that store does not have to be made with the Blazium engine, and the engine does not require that store.

## Community

- Official website: [https://blazium.app/](https://blazium.app/)
- Official community: [Discord](https://blazium.app/chat)
- Engine docs: [docs.blazium.app](https://docs.blazium.app)
- Store docs: [docs.blazium.games](https://docs.blazium.games)
