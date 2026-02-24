# Charge Shot - Game Bible

## Identity
- **Name**: charge-shot
- **Tagline**: Hold. Aim. Fire. Anticipate.
- **What is the player?**: A lone gunship pilot defending humanity against alien swarm fleets
- **World feel (2 sentences)**: Deep space battlefield where glowing amber hive-ships drift in shifting formations. The void is dark, but enemy clusters burn with ominous amber light—a beautiful, deadly dance.
- **Emotional experience**: Tension and satisfaction—building charge creates anticipation; perfect shots deliver cathartic destruction; misses feel costly
- **Reference games**: R-Type (beam weapons, formations), Ikaruga (polarized aesthetics, timing focus)

## Visual DNA
- **Color palette**: 
  - Void Black (#000000) - deep space background
  - Amber Glow (#FFB347) - enemy formations (warm, dangerous)
  - Charge Green (#00FF88) - player charge aura
  - Beam White (#FFFFFF) - pure energy beam
- **Visual reference**: R-Type meets Ikaruga—clean geometric enemies against dark space, with intense bloom on energy effects
- **Post-processing**: UnrealBloomPass (intensity 1.2), subtle vignette (darkness at edges)
- **Player silhouette (5 words)**: Sleek, angular, armored, glowing, predatory

## Sound DNA
- **Music identity**: Dark ambient synth pad with pulsing bass—evocative of vast space, building tension. Uses Tone.PolySynth with reverb.
- **Music ↔ gameplay relationship**: Music pulses faster during charge-up, becomes triumphant on hits, dissonant on miss
- **Key sound effects**:
  1. Rising charge tone (pitch increases with charge)
  2. Sharp beam crack (release fire)
  3. Layered enemy pings (each hit)
  4. Deep bass miss (formation escape)
  5. Formation shift whoosh
  6. Level complete chime

## Mechanics
- **Core loop (1 sentence)**: Hold to charge beam, release to fire at enemy formations—match beam width to formation density for maximum destruction.
- **The one thing to master**: Anticipating formation movement—reading whether a cluster will tighten or spread, and pre-charging to the exact power level needed.
- **Controls**: 
  - Pointer down: Begin charging
  - Pointer up: Release/fire beam
  - (Optional) Pointer move: Aim (ship follows horizontal position)
- **Win/lose condition**: Clear all 5 levels to win; lose when all 3 lives depleted

## Progression
- **Level 1**: "First Contact" - Sparse static formations, teach beam width matching
- **Level 2**: "Tightening Web" - Formations slowly tighten, introduce timing
- **Level 3**: "Expanding Grid" - Formations spread out, require higher charge
- **Level 4**: "Shifting Patterns" - Mixed tightening/spreading, faster movement
- **Level 5**: "The Hive" - Dense clusters with erratic shifts, final challenge

**What changes each level**: Formation density, movement speed, shift patterns (tighten/spread/random), enemy count

**The moment**: Level 5 boss formation—massive dense cluster that pulses and shifts unpredictably

## World & Lore
- **3-sentence premise**: Humanity's first contact with the Swarm was not a war—it was a harvest. The player is the last pilot of the Ember Squadron, the only one who learned to fight the Swarm's shifting formations. Each destroyed cluster releases captured human signals... they're not just ships, they're prisons.

- **2 environmental storytelling details**:
  1. Destroyed enemies release brief radio static bursts—voices of the consumed
  2. Background shows distant ember-like lights—other captured ships, still alive in the Swarm
