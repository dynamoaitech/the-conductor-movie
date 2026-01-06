# FOUNTAIN FORMAT QUICK REFERENCE
## Screenplay Writing for "The Conductor"

---

## WHAT IS FOUNTAIN?

Fountain is a **plain text markup language** for screenplays. You write in any text editor, and it converts to properly formatted screenplay PDFs.

**Why use it:**
- Works in any text editor (no special software)
- Version control friendly (Git works perfectly)
- Converts to industry-standard screenplay format
- Free tools to convert to PDF

---

## BASIC SYNTAX

### Scene Headings

Start with INT. or EXT. (all caps)

```fountain
INT. CARACAS BOARDROOM - NIGHT

EXT. CITGO REFINERY - DAY

INT./EXT. PRESIDENTIAL PALACE - CONTINUOUS
```

### Action/Description

Just write normally. Blank line before and after.

```fountain
INT. PALACE - NIGHT

Maduro sits alone in darkness. The weight of the world on his shoulders.

A phone rings. He doesn't answer.
```

### Character Names

All caps, centered automatically. Blank line before dialogue.

```fountain
CHÁVEZ
The people will triumph!

CARLOS
(skeptical)
Will they?
```

### Dialogue

Appears under character name.

```fountain
MADURO
We own it. But we can't touch it.
```

### Parenthetical (Wrylies)

Actions/emotions in dialogue, in parentheses.

```fountain
CARLOS
(hesitating)
The debt service exceeds projections.

CHÁVEZ
(laughing)
You worry too much!
```

### Transitions

Right-aligned, all caps with TO:

```fountain
FADE TO:

CUT TO:

DISSOLVE TO:
```

### Dual Dialogue

Use caret ^ after character name for simultaneous speech.

```fountain
MADURO
We need to act now!

CILIA ^
This is madness!
```

---

## ADVANCED ELEMENTS

### Centered Text

Precede and follow with >...<

```fountain
> FORTY YEARS LATER <
```

### Forced Scene Heading

Use period + space if not starting with INT/EXT

```fountain
.PHONE CONVERSATION
```

### Notes (Not in Output)

Use double brackets [[like this]]

```fountain
CHÁVEZ
The revolution is permanent!

[[NOTE: This is ironic given what comes next]]
```

### Emphasis

*Italics*, **bold**, ***both***

```fountain
CARLOS
We are *trapped*.

MADURO
**Venezuela** is finished.
```

### Title Page

At the very top of the file:

```fountain
Title: THE CONDUCTOR
Credit: Written by
Author: [Your Name]
Draft date: January 2026
Contact: 
    your@email.com
```

---

## EXAMPLE SCENE (Our Movie)

```fountain
Title: THE CONDUCTOR
Credit: Written by
Author: Based on true events
Draft date: January 2026

===

INT. CARACAS BOARDROOM - NIGHT (1986)

A mahogany table stretches before us. CARLOS MÉNDEZ (32), sharp suit, MIT ring visible, sits across from three US INVESTMENT BANKERS in identical dark suits.

Documents spread everywhere. Coffee cups. Ashtrays.

It's 3 AM. This has been going on for hours.

US BANKER #1
(friendly, but firm)
The financing structure is quite generous, Mister Méndez.

CARLOS
Fifteen billion dollars at floating rate is... generous?

US BANKER #2
The collateral is the refinery itself. Standard practice.

Carlos flips through documents. His finger stops on a clause.

CARLOS
This subordination clause. If we default--

US BANKER #1
(interrupting smoothly)
You won't default. Venezuelan crude is the most reliable feedstock in the hemisphere.

Beat. Carlos looks up.

CARLOS
What happens if oil prices fall?

The bankers exchange glances.

US BANKER #2
Oil prices don't fall, Mister Méndez. They fluctuate. Over the long term, the trajectory is invariably upward.

[[NOTE: This is 1986. Oil crash coming in months.]]

A VENEZUELAN OFFICIAL (60s, expensive suit, cigar) enters. Looks at Carlos.

OFFICIAL
Are we done here?

CARLOS
I have concerns about the debt service schedule--

OFFICIAL
(cutting him off)
The oil will pay for it.

He drops a pen on the table in front of Carlos.

OFFICIAL (CONT'D)
Sign the deal.

Carlos stares at the contract. Pages and pages of dense legal text. His hand reaches for the pen.

Hesitates.

US BANKER #1
(quietly)
This secures Venezuela's future, Carlos.

Carlos picks up the pen. His hand shakes slightly.

CLOSE ON: Signature line. Carlos signs: "Carlos Méndez, Chief Negotiator, PDVSA"

The bankers smile.

CUT TO:

EXT. US GULF COAST - DAY (1986)

Massive CITGO refinery under construction. Cranes. Welders. The skeleton of a coking tower rising against the sky.

A BECHTEL ENGINEER (40s, hardhat, blueprints) walks the site with a FOREMAN.

ENGINEER
These coker units are designed for sixteen-degree API crude. Venezuelan heavy.

FOREMAN
What if they run something else?

ENGINEER
(shrugs)
Won't work as efficiently. The economics only pencil with Venezuelan feedstock.

He taps the blueprint.

ENGINEER (CONT'D)
This isn't just a refinery. It's a lock.

CLOSE ON: Blueprint stamp: "CITGO LAKE CHARLES EXPANSION - DESIGNED FOR VENEZUELAN HEAVY CRUDE - PROPRIETARY"

FOREMAN
What's the key?

ENGINEER
Venezuela.

The engineer smiles. Not malicious. Just factual.

ENGINEER (CONT'D)
And they're about to mortgage themselves to buy it.

FADE TO:

> 1992 <

INT. CARACAS HOTEL ROOM - NIGHT

A younger HUGO CHÁVEZ (38), paratrooper fatigues, red beret, watches TV news.

ON TV: Coup attempt footage. His coup. Failed.

NEWSCASTER (V.O.)
...the rebel commander, Lieutenant Colonel Hugo Chávez, surrendered this morning...

Chávez turns off the TV. Sits in darkness.

A knock. The door opens. CILIA FLORES (30s, lawyer, sharp) enters.

CILIA
They're taking you to Yare prison tomorrow.

CHÁVEZ
How long?

CILIA
Two years. Maybe more.

Silence.

CHÁVEZ
I need books. Everything on Bolívar. Everything on the oil industry. Everything on Venezuelan economic history.

CILIA
(curious)
Why?

CHÁVEZ
Because I failed today.
(beat)
I won't fail next time.

He looks at her with absolute certainty.

CHÁVEZ (CONT'D)
Next time, I'll win. And when I do... I'll need to understand what they did to us.

FADE OUT.

END OF SEQUENCE
```

---

## FORMATTING RULES FOR OUR MOVIE

### Scene Headings:
Always include year when jumping time:

```fountain
INT. PALACE - NIGHT (2013)

INT. MADRID APARTMENT - DAY (2026)
```

### Montages:
Use series of scene headings:

```fountain
MONTAGE - CHÁVEZ'S RISE

- INT. CLASSROOM - DAY: Chávez teaching oil economics
- EXT. PLAZA - DAY: Chávez speaking to crowds  
- INT. TV STUDIO - NIGHT: Chávez's weekly show

END MONTAGE
```

### Parallel Action:
Use INTERCUT:

```fountain
INTERCUT - PHONE CALL

INT. MADURO'S OFFICE - NIGHT

Maduro on phone, stressed.

MADURO
We need guarantees.

INT. WASHINGTON DC OFFICE - DAY

US INTERMEDIARY on phone.

INTERMEDIARY
We're offering you your life.
```

### Flashbacks:
Use FLASHBACK TO: and RETURN TO PRESENT:

```fountain
FLASHBACK TO:

INT. CITGO SIGNING - NIGHT (1986)

Carlos signs the contract.

RETURN TO PRESENT:

INT. MADRID APARTMENT - DAY (2026)

Carlos, now elderly, stares at old photo of that signing.
```

### Voice Over:
Use (V.O.) after character name:

```fountain
CARLOS (V.O.)
I thought I was protecting Venezuela.

We see: Young Carlos signing documents.

CARLOS (V.O.) (CONT'D)
I was signing our surrender.
```

---

## STYLE GUIDE FOR OUR SCREENPLAY

### Keep Action Lines Brief
**BAD:**
```fountain
Carlos walks slowly across the long mahogany-paneled boardroom, his expensive Italian leather shoes clicking softly against the marble floor, as he contemplates the momentous decision that lies before him.
```

**GOOD:**
```fountain
Carlos crosses the boardroom. Each step heavier than the last.
```

### Character Introductions
First time we meet someone, ALL CAPS + age + brief description:

```fountain
HUGO CHÁVEZ (44), red beret, paratrooper intensity, addresses the crowd.
```

After that, just name:

```fountain
Chávez smiles.
```

### Camera Directions
Avoid unless essential:

**Avoid:**
```fountain
CAMERA PANS across the refinery
```

**Better:**
```fountain
The refinery stretches to the horizon.
```

**OK when needed:**
```fountain
CLOSE ON: Contract signature line
```

### Sound Effects
Capitalize:

```fountain
The phone RINGS. Maduro doesn't answer.

GUNFIRE erupts outside.
```

---

## CONVERSION TOOLS

### Free Fountain to PDF Converters:

1. **Highland 2** (Mac) - Free version available
2. **Fade In** - Free mobile version
3. **Fountain.io/afterwriting** - Online converter
4. **Wrap** - VS Code extension

### Online Editor:
- **Writer.io** (was Scripped) - Free tier available

---

## SCREENPLAY PAGE COUNT

**Rule of thumb:** 1 page = 1 minute of screen time

**Our target:**
- 90-120 minute film
- = 90-120 pages of screenplay

**Act breakdown:**
- Act I (30 min) = ~30 pages
- Act II (45 min) = ~45 pages  
- Act III (35 min) = ~35 pages
- **Total: ~110 pages**

---

## SAMPLE TITLE PAGE

```fountain
Title: THE CONDUCTOR
Credit: Based on true events
Author: [Your Name]
Draft date: January 6, 2026
Contact:
    your@email.com
    [Your phone]

Copyright (c) 2026
All Rights Reserved
```

---

## FOUNTAIN RESOURCES

**Official Spec:**
https://fountain.io/syntax

**Tutorial:**
https://fountain.io/_pages/tutorial

**Apps/Tools:**
https://fountain.io/apps

**Forum:**
https://reddit.com/r/Screenwriting (Fountain friendly)

---

## TIPS FOR WRITING OUR SCREENPLAY

1. **Start each writing session by reading the last 5 pages you wrote**
   - Maintains voice consistency
   - Catches continuity errors

2. **Write the dialogue first, action later**
   - Get the voices right
   - Add action descriptions after

3. **Read scenes aloud**
   - Dialogue should sound natural
   - If you stumble reading it, actors will too

4. **Reference character-profiles.md constantly**
   - Ensure character voice consistency
   - Each character has distinct speech patterns

5. **Use the three-act structure from PROJECT_MASTER.md**
   - Don't deviate from core story beats
   - But add detail and nuance

6. **Show the architecture, don't explain it**
   - Let Carlos discover it, we discover with him
   - Visual sequences for complex ideas
   - Trust the audience to connect dots

7. **Keep it lean**
   - First draft will be too long
   - Cut ruthlessly in revisions
   - If a scene doesn't advance plot or character, cut it

---

## COMMON MISTAKES TO AVOID

**1. Overwriting action:**
```fountain
// TOO MUCH:
Carlos enters the boardroom and immediately notices the tension in the air, palpable and thick, as the various executives and bankers regard him with mixtures of curiosity, skepticism, and barely-concealed hostility, their faces masks of corporate neutrality that don't quite hide their true feelings about this young Venezuelan upstart.

// BETTER:
Carlos enters. The room goes quiet. All eyes on him.
```

**2. On-the-nose dialogue:**
```fountain
// TOO OBVIOUS:
CARLOS
As you know, we are here to negotiate the acquisition of CITGO, which will require fifteen billion dollars in financing, which concerns me greatly because of the debt service requirements.

// BETTER:
CARLOS
Fifteen billion. That's a lot of debt.
```

**3. Directing the director:**
```fountain
// DON'T:
CAMERA SLOWLY PUSHES IN on Carlos's face as he SIGNS the contract, the PEN SCRATCHING against paper in EXTREME CLOSE-UP.

// DO:
Carlos signs. His hand shakes slightly.
```

---

## SPECIFIC TO OUR MOVIE

### Hybrid Documentary Sections

For motion graphics / explainer sequences, use:

```fountain
= EXPLAINER SEQUENCE - THE DEBT TRAP =

TITLE CARD: "How the Trap Works"

ANIMATION: Money flowing from US banks to Venezuela

NARRATOR (V.O.)
In 1986, Venezuela borrowed fifteen billion to buy American refineries.

ANIMATION: Debt counter ticking up

NARRATOR (V.O.) (CONT'D)
But the debt was structured to be unpayable.

ANIMATION: Graph showing debt service > profits

= END EXPLAINER SEQUENCE =
```

### Archive Footage Sections

```fountain
= ARCHIVAL FOOTAGE =

TITLE CARD: "February 4, 1992"

Real footage: Chávez in military uniform, coup attempt

CHÁVEZ (ARCHIVE AUDIO)
For now, we have not achieved our objectives...

= END ARCHIVAL =
```

---

## READY TO START?

**Your first scene to write:**

```fountain
FADE IN:

INT. CARACAS - PRESIDENTIAL PALACE - DAY (1976)

[This is where it begins: the nationalization celebration]

[Follow PROJECT_MASTER.md Act I structure]

[Reference character-profiles.md for Chávez's voice]

[Write the scene!]
```

---

## SCENE CHECKLIST

Before moving to the next scene, ask:

- [ ] Does this scene advance the plot?
- [ ] Does it reveal character?
- [ ] Does it show (not tell) the architecture?
- [ ] Is the dialogue natural and character-specific?
- [ ] Is the action description lean and visual?
- [ ] Does it connect to scenes before and after?
- [ ] Does it serve the theme?

---

**Good luck! The story is solid. Now make it sing.**

---

END FOUNTAIN GUIDE
