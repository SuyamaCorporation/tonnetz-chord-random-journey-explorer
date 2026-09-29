# Tonnetz Chord Random Journey Explorer

Explore music harmony via the Tonnetz lattice with random chord progression suggestions; click to reveal adjacent chords by relationship.

## Features
- Interactive SVG Tonnetz lattice visualizing all 12 pitch classes and their harmonic relationships
- Active chord notes highlighted in purple on the lattice
- Five Neo-Riemannian transformations: Parallel (P), Relative (R), Leading-tone (L), Dominant (D), Subdominant (S)
- Random journey generator producing 5-10 chord progressions via random transformations
- Step-by-step journey log with transformation labels and chord names
- Chord selector to start from any root (C through B) in major or minor
- Journey statistics: steps, unique chords visited, most-used relationship, tonal centre
- localStorage persistence of current journey

## Usage
1. Click "Random Journey" to generate a harmonically connected chord progression
2. Or click any chord in the "Adjacent Chords" panel to manually explore the Tonnetz
3. Use the chord grid on the right to start a new journey from any pitch
4. Watch the Tonnetz lattice highlight the current chord's notes in real time
5. The journey log tracks your path with transformation labels

## Tech
- Tailwind CSS CDN
- Vanilla JS (SVG rendering)
- localStorage
