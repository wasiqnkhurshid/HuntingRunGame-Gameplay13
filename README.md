# Hunting Run — Gameplay13 Shooting Lab

[Play the experiment](https://wasiqnkhurshid.github.io/HuntingRunGame-Gameplay13/) — no installation or login required.

Choose **SHOOTING LAB** on the title screen. Select A Instant, B Timing, C Assisted, D Precision Timing or E Manual Aim; normal generated gameplay; straight/curved road; Range, Accuracy and seed. START / RESTART TEST applies settings. In-run A/B/C/D/E switches restart the same seed. CONFIG returns to setup, RETRY repeats it, RESET LAB restores defaults. The diagnostic overlay shows range/distance, ideal timing, last outcome and cooldown.

A-D: swipe anywhere, including Shoot, for movement; tap Shoot to fire once on release. D allows one timing attempt per animal with an approach countdown and narrow Accuracy-scaled beat. E: drag from Shoot to correct the reticle toward the moving target marker, release to fire, or drag to CANCEL AIM and release to abort without spending ammo. Movement contacts starting elsewhere retain normal swipes. Window width and aim sensitivity are adjustable in CONFIG. Independent fingers may shoot and move. Keyboard: A/D or arrows, Space/W, S, Enter, Escape. Controls remain Gameplay12: 32 m/s, Closer camera, 84 dp Shoot and 18 dp swipes. Every test starts/restarts with 99 arrows and zero shooting cooldown. Each deliberate tap consumes one arrow; holding never repeats. Pickups add two, capped at 99. Normal health, animal motion and obstacles remain active for a 90-second / 2,880 m run.

This is an unfinalized shooting experiment, compiled from private source `7a976fa21f9618f4450bd214bf243aa4b534667f`, branch `codex/gameplay13-shooting-lab`. Stable Gameplay12 remains unchanged at https://wasiqnkhurshid.github.io/HuntingRunGame-WebGL/. No source art is published here. The filesystem database `HuntingRun.Gameplay13:/idbfs`, save key and native filenames are isolated from stable progress. Experimental run rewards/resume snapshots are not committed.

Unity and desktop Chrome touch simulation passed. Physical Android/iPhone, Safari, thumb feel and sustained mobile performance are not validated. WebGL2 and WebAssembly are required; loading and storage availability depend on the browser/device. Automated hit rates are deterministic fixture results, not player-skill or enjoyment measurements.

## Rollback

This independent site can be unpublished in this repository's Pages settings. To restore this release after a future change, restore tag `gameplay13-skill-profiles` into a new main commit and push. Neither operation changes stable Gameplay12. Do not force-push or modify the stable repository.
