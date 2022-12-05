# Another look at the guitar fretboard
  A (simple and logic) look at the guitar fretboard for beginners.  
  
  This simple and straight-foward manual is meant as an introduction for guitar beginners curious about diving into the guitar fretboard (in standard E tuning).  
  It is meant to facilitate the assimilation using memory tricks, colors and visual representation of the relation between notes on the fretboard (the last being respresented as an array).  

## Pre-requisite
  You should understand the simple "12 equally divided" (aka equal-tempered) relationships of notes in the [chromatic scale](https://en.wikipedia.org/wiki/Chromatic_scale) (used in western music), we will cover this briefly.  
  Make you sure that you get the reading direction of strings, the last one being the fattest one, the lower pitched E precedeed by the 5th string A.  
  We could represent the strings ordered from farrest to you to closest (if you play a right-handed guitar) with  
```c
e ||-|-|-|-|-|-|-|-|-|-|-|-| 1
B ||-|-|-|-|-|-|-|-|-|-|-|-| 2
G ||-|-|-|-|-|-|-|-|-|-|-|-| 3
D ||-|-|-|-|-|-|-|-|-|-|-|-| 4
A ||-|-|-|-|-|-|-|-|-|-|-|-| 5
E ||-|-|-|-|-|-|-|-|-|-|-|-| 6
```  
  * __e__ = 1st string, we will use this lowercase e to differs from the 6th string E  
  * the writing D8 means "on the eighth fret of the fourth string"  
  * the writing e1 means "on the first fret of the first string (e)"  

## Quick cheatsheet
* 1 octave = 12 notes *(C-C#-D-D#-E-F-F#-G-G#-A-A#-B)* = 12 semi-tones
* 2 semi-tones = 1 tone
* The 12 notes of the octave are all the black and white keys in one octave on the piano—form the [chromatic scale](https://en.wikipedia.org/wiki/Chromatic_scale) 
![alt text](https://github.com/mirawired/another-look-guitar-fretboard/blob/main/img/octav.png)  

* Going down a string on the fretboard equals to going __higher__ in pitch  
  
## Practical definitions
  Open string : an open string is a string strummed while playing a chord without any finger on that particular string.  
    *ex1: the E Major triad where only 3 fingers are on strings but all strings are played.*  
    *ex2: If you play all your strings of you guitar without any finger on the fretboard, you played only open strings.*  
 We will refers to the open strings as e0/B0/G0/D0/A0/E0

## Key points
  * First, let's focus on the 7 natural notes (aka the white piano keys : C-D-E-F-G-A-B), it will helps reduce the amount of information to grasp.  
  * We will only look at the 12 first frets because at the 12th one, it just start again from the open chords notes (E-A-D-G-B-E) and keep going in the same order.  

## The 2 semi-tones pattern
  The 2 semi-tones pattern simply means that the interval between all natural notes is 2 semi-tones (= 1 tone) apart, __except from B to C and E to F__.   
  
 * 1st/5th/6th strings : "starts" respectively at fret #1 because their previous (root) notes are E - B - E (= starts one semi-tone from the open string note).  
  
 * 2nd/3rd/4th strings : "starts" respectively at fret #2 because their previous (root) notes are A - D - G. (= starts one tone from the open string note).  

## Tones
  This simple array represents the guitar fretboard. We will be using this scheme all manual.  
  
  This particular one displays the intervals between naturals notes.  
  * T : 1 tone  
  * S : 1 semi-tone    
    
  The first and last lines shows frets position and the 3, 5, 7, 9 & 12 frets (marked ones on your fretboard) are light-grey higlighted.  
  *The often circle(s) present at this particulars frets are here to help you find your position down the neck.*
 ![alt text](https://github.com/mirawired/another-look-guitar-fretboard/blob/main/img/inter.png)
 
## Octaves

If we only look at the 6th strings (E), there is one octave between E0 (= E) and E12 (= E, one octave higher).  
So, any octave of any note in the same string can be found 12th frets down.  
More interestingly, finding the octave of a note on the precedant string is done by following the 12th octave rule, after going down, going up 5 frets on the adjacent string (the previous one) gives you the exact same note (the "12th fret down" octave).  

![alt text](https://github.com/mirawired/another-look-guitar-fretboard/blob/main/img/octa1.png)  
The red E (aka E0) is the E open string. Going down 12th fret gives us the octave below.  
The same note is found using the +12/-5(up) semi-tones formula on the A string.  
Both E12 and A7 have the exact same pitch !  

Going a step further, the 7th fret you find the octave of the previous string, __except for the G__, wich is found 1 semi-tone after, on __fret 8__.  

![alt text](https://github.com/mirawired/another-look-guitar-fretboard/blob/main/img/octa2.png)  

## Fretboard as an array
  This array represent the notes sorted by fret apparition (the box underneath just recap the array in a classical reading way).  
  * The break column correspond to the frets at which the 2 semi-tones patterns breaks (so B-C and E-F).  

![alt text](https://github.com/mirawired/another-look-guitar-fretboard/blob/main/img/frets.png)

  Watching it vertically like this helps seeing patterns :
  * the 5th, 10th and 12th frets are all natural notes, respectively the 3rd, 6th and 7th naturals of the strings.

## Fretboard notes
  This array represent all the naturals note with a single color for each.  
![alt text](https://github.com/mirawired/another-look-guitar-fretboard/blob/main/img/notes.png)
