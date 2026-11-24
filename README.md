# Legends Ronin

**My action-figure shelf, brought to life on my Mac.**

A playful macOS desktop companion: familiar characters wander, grapple, fly, open portals, and get into tiny crossover fights around your windows. A little 1998. A lot of chaos.

Built on **[Klipnok Ronin](https://klipnok.com/ronin/)**. The original desktop companion and its movement engine are the work of Klipnok; Legends Ronin adds the character artwork and crossover behaviors. Please visit the original Ronin project and support its creator.

[**Download for Mac — DMG**](https://github.com/doctor-ew/legends-ronin-downloads/releases/latest)

![Legends Ronin action montage: saber fights, pogo hops, and a green portal](assets/desktop-action-montage-v2.gif)

[Open the 12-second action GIF directly](assets/desktop-action-montage-v2.gif) · Saber flips, pogo hops, and portal trouble.

## What it does

- **Mix and match:** add up to 12 guests alongside your selected cast.
- **Desktop playground:** jumping, grappling, window traversal, flight, and portals.
- **Crossovers:** saber duels, blaster exchanges, dodges, and character encounters.
- **Personality:** pizza breaks, pogo hops, gear checks, and other idle antics.
- **Big visitors:** transforming robots, ships, KITT, and the TARDIS.
- **Randomizer:** switch casts automatically every 10–30 minutes.

The cast includes Star Wars and Rebels, the turtles, Rick and Morty, Doctor Strange and Doom, X-Men, G.I. Joe, Lower Decks, Cartoon Planet, and more.

## New in 0.27.0

- **Grimlock:** articulated robot-to-T. rex transformation, prowling, snapping jaw, and fire breath.
- **Soundwave:** robot-to-cassette-deck transformation and a chest that deploys **Laserbeak**, **Ravage**, and **Rumble**. The tapes unfold into a flying bird, prowling panther, and piledriver-equipped robot, then fold up and return.
- Add either through **Mix & match guests · up to 12 → Visitors**. Click Grimlock to transform; click Soundwave to deploy his crew when he is ready. Both act automatically, too.
- Soundwave has one trio at a time. His tapes use his guest slot and return between outings.

## Guest upgrades in 0.26.0

- **Guest upgrades:** Strange and Doom alternate flights and their colored portals; Rick uses green portal travel; Nightcrawler flips, backflips, handstands, and bamfs; Boba uses his jetpack.
- **Transformer guests:** add **Optimus Prime** or **Starscream** from **Mix & match guests · up to 12 → Visitors**. They transform independently alongside your existing cast.
- New guest powers have staggered cooldowns, with at most three active at once. The 30 fps lower-CPU default remains available.

## Requirements

- An **Apple silicon Mac**.
- **macOS 13 or later**.

This build has been tested locally on Apple silicon. Intel Macs and other operating systems are not supported by this package.

## Install

1. Download the `.dmg` from the [latest release](https://github.com/doctor-ew/legends-ronin-downloads/releases/latest).
2. Open it and drag **Legends Ronin** onto **Applications**.
3. Eject the disk image, then open Legends Ronin from Applications.

The app lives in the menu bar. Look for **Legends** at the top of your screen.

**Signing status:** this is an experimental, ad hoc signed build. It is not Developer ID signed or notarized. If macOS blocks the first launch and you choose to trust this download, follow [Apple’s instructions for opening an unnotarized app](https://support.apple.com/en-us/102445). Keep macOS security protections enabled.

## Controls

| Action | How |
| --- | --- |
| Choose a cast | Open the **Legends** menu, or right-click a character |
| Add or remove guests | **Mix & match guests · up to 12** |
| Add a Transformer guest | **Mix & match guests · up to 12 → Visitors → Optimus Prime / Starscream / Grimlock / Soundwave** |
| Trigger a special | Give a character a quick click |
| Move a character | Click and drag |
| Start a fight or encounter | **Skirmish now** or **Encounter now** |
| Try a desktop mission | Choose a **Mission** item |
| Rotate casts automatically | Enable **Randomizer: every 10–30 minutes** |
| Reduce CPU use | **Animation frame rate → 30 fps · lower CPU** |
| Prefer smoother animation | **Animation frame rate → 60 fps · smoother motion** |
| Exit | **Quit Legends Ronin** |

Specials vary by character and current activity. Guests can overlap with your main cast. More characters and effects increase CPU use; 30 fps is the default.

## Characters and specials

These profiles describe each character in their main cast. Mixed guests also have dedicated specials for Boba, Doom, Strange, Rick, Nightcrawler, the Rebels, astromechs, and Lower Decks; some other cast-specific routines remain simplified. Most specials also happen automatically; a quick click requests a reaction when the character is available. Weapons listed here are the equipment drawn in this build, not a promise that every character has a separate projectile animation.

### Teenage Mutant Ninja Turtles

Selecting a turtle brings all four brothers. They keep the original Ronin traversal and grappling; mixed guests also have pizza breaks.

| Character | Equipment and specials |
| --- | --- |
| Leonardo | Twin katana, grappling, acrobatic traversal, and melee encounters |
| Raphael | Twin sai, grappling, acrobatic traversal, and melee encounters |
| Donatello | Bo staff, grappling, acrobatic traversal, and melee encounters |
| Michelangelo | Animated nunchucks, grappling, acrobatic traversal, and melee encounters |

### Star Wars

| Character | Equipment and specials |
| --- | --- |
| Darth Vader | Force jumps and flips, returning red saber throws, and a paired Jedi duel; visiting Vader alternates flips and saber throws |
| Jedi | Blue saber, Force traversal, returning saber throws, and a paired Vader duel |
| Mandalorian | Amban rifle, grapple and swing traversal, cartoon Jawa disintegration encounters, and Grogu following in his pram |
| Boba Fett | Blaster, grappling, jetpack flight, and gear-checking idle behavior |
| Darth Maul | Double-ended red saber and acrobatic three-way combat against Qui-Gon and Obi-Wan; visiting Maul alternates flips and saber throws |
| Qui-Gon Jinn | Green saber, flips, parries, and coordinated combat against Maul; visiting saber throws |
| Obi-Wan Kenobi | Blue saber, flips, parries, and coordinated combat against Maul; visiting saber throws |

### Rebels

Selecting the Rebels brings all seven together.

| Character | Equipment and specials |
| --- | --- |
| Kanan Jarrus | Returning saber throw alternating with a Force flip |
| Sabine Wren | Jetpack flight alternating with grappling; blaster attacks |
| Ezra Bridger | Lightsaber that switches to blaster mode for ranged shots |
| Zeb Orrelios | Staff combat and acrobatic flips |
| Hera Syndulla | Blaster shots |
| Chopper | Two upper arms waving upward and an electrical zap |
| Ahsoka Tano | Twin white blades, an offhand reverse grip, and acrobatic Force flips |

### Astromechs

| Character | Specials |
| --- | --- |
| R2-D2 | Jet-assisted flight |
| R5-D4 | Motivator blowout, smoke, and a wobble |
| BT-1 | Blaster fire and missiles |

### The Bad Batch

The six share a cast and participate in cross-cast ranged combat. Their equipment and movement differ; they do not each have a separate elaborate power animation.

| Character | Equipment and specials |
| --- | --- |
| Hunter | Blaster, melee encounters, and jump flips |
| Tech | Blaster fire and hopping traversal |
| Wrecker | Heavy blaster, melee encounters, and hopping traversal |
| Crosshair | Long rifle, ranged attacks, and hopping traversal |
| Echo | Blaster, melee encounters, and jump flips |
| Omega | Bow-style ranged weapon and hopping traversal |

### Comics and Eternia

| Character | Equipment and specials |
| --- | --- |
| Batman | Batarang equipment, grappling, and melee encounters |
| Spider-Man | Web-style guest grapple, native traversal, and melee encounters |
| Doctor Doom | Levitation, green portals, and green thrown energy shards |
| Doctor Strange | Flight, orange portals, and orange thrown energy shards |
| He-Man | Sword of Power, sword-raised lightning, and a paired Skeletor duel |
| Skeletor | Havoc Staff and a paired He-Man duel |

### X-Men

Selecting an X-Man brings all seven together.

| Character | Equipment and specials |
| --- | --- |
| Wolverine | Claw-assisted window-edge climbing and melee encounters |
| Nightcrawler | Smoky “bamf” teleportation, flips, backflips, and a handstand variant |
| Storm | Flight, lightning effects, and a thundercloud-and-zap special |
| Jean Grey | Flight, orbiting energy effects, and ranged energy attacks |
| Gambit | Charged-card throws |
| Cyclops | Optic beams |
| Magneto | Flight, orbiting metal effects, and ranged energy attacks |

### Rick and Morty

| Character | Specials |
| --- | --- |
| Rick | Portal gun, green portal travel, and a Morty companion |
| Morty | Accompanies Rick, native traversal, and panicky idle gestures |

### G.I. Joe and Cobra

The confrontation cast combines Snake Eyes and Scarlett with Cobra Commander and Destro.

| Character | Equipment and specials |
| --- | --- |
| Scarlett | Crossbow-style ranged weapon and grappling |
| Snake Eyes | Katana, grapples, flips, and smoke effects in the confrontation cast |
| Cobra Commander | Blaster attacks, evasive movement, and a speech routine as a mixed guest |
| Destro | Blaster attacks and jet-assisted evasive movement |

### Powerpuff Girls

| Character | Specials |
| --- | --- |
| Blossom | Horizontal flight, turns, window-ledge landings, and behind-window passes |
| Bubbles | Horizontal flight, turns, window-ledge landings, and behind-window passes |
| Buttercup | Horizontal flight, turns, window-ledge landings, and behind-window passes |

Behind-window visibility depends on the other app’s transparency.

### Cartoon Planet and Flaming Carrot

| Character | Specials |
| --- | --- |
| Space Ghost | Horizontal flight, window perching, and wrist beams |
| Zorak | Articulated hopping and melee encounters |
| Brak | A dance with floating musical notes |
| Flaming Carrot | Pogo-stick hops and melee encounters |

Space Ghost, Zorak, and Brak appear together in their main cast.

### Danger Mouse

| Character or vehicle | Specials |
| --- | --- |
| Danger Mouse | Gets out of the shared car, grapples to ledges, and returns to the car |
| Penfold | Gets out, clambers around the car or ledges, and returns to the car |
| Danger Car | Drives with Danger Mouse and Penfold seated inside |

### Lower Decks

Selecting a crew member brings all four.

| Character | Specials |
| --- | --- |
| Mariner | Phaser burst and an acrobatic flip |
| Boimler | Panicky scrambling and an “Oh no” caption |
| Tendi | Tricorder-style scan beams |
| Rutherford | A repair drone with sparks |

### Vehicles and transforming visitors

| Character or vehicle | Specials |
| --- | --- |
| Millennium Falcon | Flight, laser exchanges, and a clickable speed boost |
| X-wing | Flight and laser exchanges |
| TIE fighters | Flight and laser exchanges |
| AT-AT | Walks along the bottom of the screen and fires lasers |
| Optimus Prime | Transforms between robot and truck; also available as an individual Visitor guest |
| Starscream | Transforms between robot and jet; lands before changing back; also available as an individual Visitor guest |
| Grimlock | Robot and T. rex forms, jaw animation, prowling, and fire breath; individual Visitor guest |
| Soundwave | Robot and cassette-deck forms; deploys and recalls Laserbeak, Ravage, and Rumble; individual Visitor guest |
| Laserbeak / Ravage / Rumble | Soundwave’s transforming tapes: flight, prowling, and piledriver shockwaves; supporting crew, not separate guest slots |
| KITT | Moving scanner light and Turbo Boost jumps |
| TARDIS | Flight, fading dematerialization and rematerialization, and a Doctor who exits and re-enters |
| The Tenth Doctor | Walks outside the TARDIS and makes a sonic-style glow gesture |

### Supporting cameos and shared interactions

**Grogu** follows Mando in a hovering pram, including when Mando is a mixed guest. **Jawas** appear in Mando’s brief cartoon rifle encounters. These are supporting figures rather than separate cast selections.

Eligible characters can take part in cross-cast melee or ranged encounters, dodges, and recoverable hit reactions. The menu also offers a ledge retrieval, a Cobra chase, and a grapple rescue. These are shared encounters rather than a unique special for every character.

## About this build

Legends Ronin is a fan-made character and behavior layer built on the supplied **[Klipnok Ronin 1.0.9](https://klipnok.com/ronin/)** desktop engine. Credit for the original application and engine belongs to Klipnok. Character names and likenesses belong to their respective owners. This project is not affiliated with or endorsed by those owners.

This public repository contains the README and demo media. Packaged app downloads are attached to [Releases](https://github.com/doctor-ew/legends-ronin-downloads/releases). Source code is not included, and this repository does not grant rights to third-party code or characters.

The release includes a SHA-256 checksum file so you can verify the downloaded disk image. Updates are distributed through this release page.
