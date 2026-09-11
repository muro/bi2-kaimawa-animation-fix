# Battle Isle 2 KAIMAWA animation fix

The original ASCR062 animation was too large, so the game immediately closed the in-game animation and never displayed it. This updated version recompresses the animation and fixes the character animation so it matches the camera movement.

![KAIMAWA ASCR062 animation frame](https://raw.githubusercontent.com/muro/bi2-kaimawa-animation-fix/main/ascr062.png)

## Installation

1. Close Battle Isle 2.
2. Find the installed game's `ISLE2` directory — it contains `BATTLE2.EXE`.
3. Back up `ISLE2/ANI/ASCR000.LIB` and `ISLE2/ANI/ABCK000.LIB`, if they are present.
4. Copy this package's two `ANI` files to `ISLE2/ANI`.

Do not copy them to `SCENERY/ANI`: that folder has its own files with the same names.
