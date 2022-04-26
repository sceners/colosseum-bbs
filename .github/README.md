# Colosseum BBS advert

For MS-DOS from 1994 created by Goblin and Shayde from Neural Image Syndicate.

[Original package](https://defacto2.net/f/b22fe7e)

![image](https://user-images.githubusercontent.com/513842/165212777-129fb47f-ced5-467b-a9db-4b6eba485652.png)

---

### Music player, Reality Adlib Tracker

```
▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓
          ·
          . ███▀▀█▄  ▄██▀▀▀▀  ▄█▀▀▄  ███     ███ █████▄  ██  ███ ·
          : ███▄▄█▀  ███▄▄   ▐██▄▄█▌ ███     ███    ▀██▌ ▀█▄▄███ :
          │ ███ ▀██▄ ███     ███  ██ ▐██▄    ███     ███     ███ |
  ┌ ─ ─═─═╝ ▀▀▀   ▀▀▀ ▀▀▀▀▀▀ ▀▀▀  ▀▀  ▀▀▀▀▀▀ ▀▀▀     ▀▀▀ ▀▀▀▀▀▀  └── ─ -───┐
  │ ▄█▀▀▄ ██▀▀▄ ██    ██ ██▀▀▄   ▀▀▀█▄ ██▀▀▄ ▄█▀▀▄ ▄█▀▀▄ ██  █ ▄█▀▀▀ ██▀▀▄ :
  | ██▀▀█ ██  █ ██    ██ ██▀▀▄      ██ ██▀▀▄ ██▀▀█ ██  ▄ ██▀▀▄ ██▀   ██▀▀▄ .
  : ▀▀  ▀ ▀▀▀▀   ▀▀▀▀ ▀▀ ▀▀▀▀       ▀▀ ▀▀  ▀ ▀▀  ▀  ▀▀▀  ▀▀  ▀  ▀▀▀▀ ▀▀  ▀ ·
                       Play-routine Code  version 1.1a

                        by SHAYDE/REALITY Feb, Apr 95

                                    - * -

 Feel free to use/hack this code about as much as you like.  In the good old
 dayz of Amiga, ALL tracker writers gave away player source-code so that the
 coder could do what he/she wanted with it.  On PC every tracker writer thinks
 their player code should be protected and they either don't release a player
 or they release it in .OBJ format which means if you need to make changes to
 the code to fit in with your demo/intro you're fucked!!!  So message to all
 tracker writers out there:
 FOR THE SAKE OF CODER SANITY, ALWAYS RELEASE PLAYER CODE FOR YOUR TRACKERS!!
 OTHERWISE WOT'S THE POINT OF WRITING A TRACKER?!?!??!?!  And release it in
 source-code form to reduce head-aches!

				     - * -

 This source-code doesn't contain any segment directives so it is only
 INCLUDEable in other source-code.  Also it requires a minimum of a 286
 to run.  I avoided using ASSUMEs so that the code that INCLUDEs this code
 doesn't lose it's ASSUMEs, hence variables are accessed via CS:.  You can
 save a few bytes by dropping them (which you'll need to do if you want to
 use this player in protected-mode), although I use DS: to reference the
 tune segment.

				     - * -

 Hey, 'scuse the ugliness of the listing.  I'm a coder, not an artist!

				     - * -

 INSTRUCTIONS FOR USE:

	To initialise the player, call "InitPlayer".
	To stop play, call "EndPlayer".
	To play music, call "PlayMusic" 50 times a second (18.2/sec for a
					"slow-timer" tune).

				     - * -
```
