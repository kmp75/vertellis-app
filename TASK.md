Build a beautiful Vertellis card game webapp (single HTML file, no dependencies, no build step).

Vertellis is a card game with conversation-starter questions. Build a mobile-first webapp.

## Features
- Multiple decks: 🏠 Familie, ❤️ Paare, 👥 Freunde, 🧒 Teens, 🎉 Party
- Each deck has 20-30 questions in German
- Full-screen card display with beautiful typography
- Swipe left/right OR tap arrows to navigate cards
- Card flip animation (question on front, blank/reflection prompt on back)
- Deck selector screen at start
- Progress indicator (card 3/25)
- Dark mode by default, matches Apple aesthetic
- Shuffle button
- "Zurück" button
- Current card number displayed
- Beautiful gradient backgrounds per deck (different color per deck)
- Cards have elegant typography, rounded corners, subtle shadows

## Design
- Font: system-ui / SF Pro
- Colors: dark background, white cards with colored accents per deck
- Familie: warm orange/amber gradient
- Paare: rose/pink gradient  
- Freunde: blue/teal gradient
- Teens: purple/violet gradient
- Party: green/lime gradient
- Smooth CSS animations for card transitions (slide or flip)
- Touch/swipe support for mobile

## Questions (German, authentic Vertellis style)
Include real-feeling deep questions like:
- "Welcher Moment in deinem Leben hat dich am meisten verändert?"
- "Was würdest du tun, wenn du wüsstest, dass du nicht scheitern kannst?"
- "Wann hast du dich zuletzt richtig lebendig gefühlt?"
- etc. — 20+ per deck, all in German

## Output
Single file: index.html — self-contained, works offline, no external dependencies.

When completely finished, run:
openclaw system event --text "Done: Vertellis webapp fertig in /tmp/vertellis-app/index.html" --mode now
