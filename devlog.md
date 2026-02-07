# Ball Rush League — Launch Devlog

## 🚀 v6.1 Release — The League Is Open!

Ball Rush League is live! A physics-based arcade slot where balls bounce around a football field, scoring goals in corner pockets. But this isn't your typical slot — there's no reels, no paylines. Just pure physics and strategy.

### What Makes It Different

Every ball has a life of its own. Normal balls spawn with value 9 and slowly lose it over time — unless they pass through the center zone, which recharges them back to full. Then there are the special ones:

🥇 **Golden balls** — never lose value, carry a ×3 multiplier, and you can spot them by the spinning ring of light around them.

💣 **Explosive balls** — never lose value either, but when they score a goal, they detonate everything in the upper half of the field. Every destroyed ball pays out. Chain reactions happen.

The **progressive multiplier** grows with each goal and can reach ×5. But five timeouts in a row and it resets. Risk and reward.

### The League

This isn't just a single-player game anymore. Ball Rush League has a **weekly leaderboard** powered by Firebase. Your best RTP (Return to Player) gets recorded — play at least 500 balls to qualify. Same RTP? The player who fired more balls takes the lead. New rankings every week.

Pick your randomly generated nickname — NitroBlинчик, CosmicOwl, 雷霆猫咪 — and climb the board.

### 5 Languages, One Game

English, Russian, German, Portuguese, Chinese. Everything translates — UI, stats panel, game rules, nicknames. Switch languages on the start screen with flag buttons.

### Sound Design

Three distinct audio signatures for goals:
- Normal goals get a crowd cheer
- Golden goals trigger a sparkle arpeggio rising through a major chord
- Explosive goals hit with a deep boom, noise burst, and sub-bass rumble

Background ambient crowd noise loops during gameplay.

### Under The Hood

The physics engine runs deterministic simulation with seeded RNG (Java-compatible). Every game can be replayed with a seed URL — share your lucky run with friends. The math has been verified across 400 million simulated spins.

### What's Next

- More special ball types
- Tournament mode
- Achievement system
- Mobile optimization

Play it now and see if you can top the weekly board.

⚽ **Ball Rush League v6.1** — constrik.itch.io/ball-rush-league
