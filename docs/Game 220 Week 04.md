- [[GAME 220 Syllabus|Home]]
- [[Game 220 Week 02|Previous Week]]
- [[Game 220 Week 05|Next Week]]

# Week 4 - 2/4/22
- After week break for Game Jam
- [Exercise 2](https://github.com/APUGames/Game-220-Exercise-2/tree/main) due

## Lecture Notes
Sound Design for User Interfaces (file formats; editing techniques; menu interface sound design; unified soundscapes; synthesized interface sounds) 

### Reading 
_25 minutes_

- [[The Essential Guide to Game Audio Book Notes#Intro]]
- [[The Essential Guide to Game Audio Book Notes#Level 1 - Animation Art Audio]]
- [[The Essential Guide to Game Audio Book Notes#Level 2 - Brief History of Games]]
- [[The Essential Guide to Game Audio Book Notes#Level 3 - Audio for Interactive Evironments]]
- [[The Essential Guide to Game Audio Book Notes#Level 5 - Sound Design in Games]]

### Help and Questions about Using Audition

### Explain Assignment

### Cover Missed EQ section
- [[Game 220 Week 02#EQ]]

### Advanced Sound Editing Concepts
#### Speed and Pitch
- related by default
	- dropping both results in lower EQ range
- can be separated with digital algorithms
	- time stretch: slowed without changing pitch
	- pitch effect: raise pitch without speed

#### Reverb / Delay aka "time based"
- delay is repition of sound
	- usually at decresing volume
	- sometimes decreasing EQ
	- simple delay is one regular repeat over fixed time
	- "spacey" 
- reverb
	- many delays all so close together they "blur"
	- "breathy"
	- "wet"
	- "cold"

#### Compression / Gate
- Gate more important

#### Noise Reduction
- complex algorithm

#### Distortion
- complex harmonic interaction

#### Effects order matters	
This will sound different
```mermaid
graph LR;
source(Source signal) -- Dry singal --> EQ;
EQ -- EQ'd signal --> Reverb;
Reverb -- Reverb'd signal --> Output(Output);
```
Than this	
```mermaid
graph LR;
source(Source signal) -- Dry singal --> Reverb;
Reverb -- Reverb'd signal --> EQ;
EQ -- EQ'd signal --> Output(Output);
```

### Creative sound techniques
- slow it down
- speed it up
- creative EQ
- reverse it
- put attack of one sound to decay of another
- put lots of reverb on it
- distort it

### Sound Design Inspirations
- Ben Burt hitting high tension wire
- marble drop iphone sound
- ratched iphone sound

## Assignments
### Exercise 3: UI Sound Library  - due week 5
- create sounds for a menu UI
  - "open" section
  - "select"
  - "cancel"
  - "error"
  
### Reading
- [[The Essential Guide to Game Audio Book Notes#Level 4 - Styles and Genres]]