# Pat2-subtask-1
# Morse Code Overview

## What is Morse Code?
Morse code is a method used in telecommunication to encode text characters as standardized sequences of two different signal durations: short signals called **dots (.)** and long signals called **dashes (-)**. It represents letters, numbers, and symbols using these unique combinations, allowing messages to be sent via sound, light, or visual signals.

## Historical Context
Morse code was developed in the early 1830s–1840s by Samuel Morse, Alfred Vail, and others, alongside the invention of the telegraph. It was the primary way to send long-distance messages for over 150 years, revolutionizing communication, trade, and military operations. It remained widely used until digital communication systems replaced it, though it is still used in aviation, amateur radio, and emergency signaling today.

## How It Works
- Every letter, number, or symbol has a unique pattern of dots and dashes.
- A **dot** is the basic unit of time; a **dash** is 3 times longer than a dot.
- Between symbols in a letter: 1 dot-length pause.
- Between letters: 3 dot-length pause.
- Between words: 7 dot-length pause.
- In this project: 
  - Dot = ASCII 46 (`.`) or 250
  - Dash = ASCII 45 (`-`) or 196

### Example Translations:
- `A` → `.-`
- `B` → `-...`
- `C` → `-.-.`
- `HELLO` → `.... . .-.. .-.. ---`
- `WORLD` → `.-- --- .-. .-.. -..`

## References
- International Telecommunication Union. (2024). *Morse Code Recommendation*. ITU-R M.1677.
- Wikipedia Contributors. (2024). *Morse Code*. Wikipedia, The Free Encyclopedia.
