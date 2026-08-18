# Coffee Personality Quiz — Requirements

## Product goal

Build a playful, pop-culture-themed quiz that gives each visitor one coffee personality and one drink recommendation.

## Results

Show a single best-match result. Each answer awards one point to a personality; show the personality with the most points at the end.

| Personality | Coffee recommendation | Tagline | Image |
| --- | --- | --- | --- |
| Bold Adventurer | Double Espresso | You live for intensity. | `public/bold-adventurer-espresso.jpg` |
| Cozy Classic | Medium Roast Drip | Comfort in every cup. | `public/cozy-classic-mug.jpg` |
| Sweet Enthusiast | Caramel Latte | Life's too short for bitter. | `public/sweet-enthusiast-latte.jpg` |
| Practical Pragmatist | Large Drip, Whatever's Fresh | Just make it work. | `public/practical-pragmatist-drip.jpg` |

## Visual direction

- Playful and colorful (style preview 1)
- Bright colors, rounded shapes, friendly oversized typography, and energetic quiz cards
- Include small icons with every answer option
- Use the selected coffee image on each result screen

## Questions and scoring

### 1. Your ideal fantasy quest starts with…

- ⚔️ Charging toward danger — Bold Adventurer
- 🏡 Packing snacks and a map — Cozy Classic
- ✨ Choosing the most enchanted outfit — Sweet Enthusiast
- 🛠️ Checking the route and supplies — Practical Pragmatist

### 2. Pick a movie-night role

- 🎬 “Let’s watch the wildest action movie” — Bold Adventurer
- 🛋️ “Blanket, comfort movie, zero stress” — Cozy Classic
- 🍿 “I brought themed treats!” — Sweet Enthusiast
- 📋 “What’s shortest and best reviewed?” — Practical Pragmatist

### 3. You find a mysterious portal. You…

- 🚀 Step through immediately — Bold Adventurer
- 🔦 Invite trusted friends first — Cozy Classic
- 🌈 Take a selfie beside it — Sweet Enthusiast
- 🧭 Figure out where it leads — Practical Pragmatist

### 4. Your superhero power is:

- ⚡ Super speed — Bold Adventurer
- 🛡️ A protective force field — Cozy Classic
- 💫 Making everything sparkle — Sweet Enthusiast
- 🧠 Instantly solving problems — Practical Pragmatist

### 5. At a wizard-school feast, you choose:

- 🔥 The spiciest-looking dish — Bold Adventurer
- 🥖 Familiar comfort food — Cozy Classic
- 🍰 The most extravagant dessert — Sweet Enthusiast
- 🥗 The filling option that makes sense — Practical Pragmatist

### 6. Your spaceship is running low on fuel. You…

- 🌌 Try an uncharted shortcut — Bold Adventurer
- 🤝 Keep the crew calm and together — Cozy Classic
- 🎨 Make the emergency beacon look fabulous — Sweet Enthusiast
- 🔧 Calculate the safest route home — Practical Pragmatist

## Interaction notes

- Present one question at a time and show progress.
- Let visitors pick one answer per question, then advance.
- Tally points after the final answer and display the best match, its coffee recommendation, tagline, and selected image.
- In a tie, use the first tied personality in the result order above.
