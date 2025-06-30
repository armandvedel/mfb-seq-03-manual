# mfb-seq-03-manual
Updated and imporoved users manual for the MFB SEQ-03 eurorack sequencer module

mfb

PRESS TRACK TO TOGGLE MUTE / PATTERN

${\color{green} I. \space Mute \space Mode \space (track \space light \space green)}$

	Step keys toggle mute for each track
 
${\color{red} II. \space Pattern \space (global \space / \space all \space tracks) \space mode \space (track \space light \space red)}$

	SHIFT + 1-2, 8-16
	
	1. Last step (affects all Bars)
	2. clock division
	|	
	|	(3-7 are track functions, see below)
	|
 	Bar length 
	Bar up/down
	8. rem(ove) bar
	9. clr pattern
	10. init pattern
	11-13. Seq mode (default, 1 bar, cv+gate)
	14. (sync) start mode (mfb or dinsync)
	15. sync I/O
		1. internal clock / i/o output 16ths clock
		2. internal clock / i/o output 24ppq clock
		3. external clock bipolar 16ths / i/o input =  start / stop
		4. external clock bipolar 24ppq / i/o input =  start / stop
		5. external clock unipolar 16ths / i/o input =  reset
		6. external clock unipolar 24ppq /  i/o input =  reset
	16. shuffle
	Save Pattern (hold save + 1-16)
	Load Pattern (hold load + 1-16)
	change Bank (hold shift + load patt)

${\color{red} III. \space Track \space [per \space output] \space (track \space + \space 1-12) \space (track \space light \space red)}$

	SHIFT + 3-7

	3. Track Mode
		a. note (shift+1)
		b. gate (shift+2)
		c. env. (shift+3)
		d. lfo (shift+4)
	4. Direction
		1. Forward
		2. Backwards (Can be used with Last Step (shift + step 1) to Ease programming)
		3. Pingpong
		4. Random
	5. Quantize
		1. 3 Octaves
		2. 5 Octaves
		3. 7 Octaves
		4. Unquantized
	6. LFO type
		1. Sawtooth Rising
		2. Sawtooth Falling
		3. Sine
		4. Square
	7. Clr bar
        
${\color{red} IV. \space Step \space Edit \space (press \space select \space step(s) \space selected \space blink(s) \space (track \space light \space red))}$
${\color{red} IV. \space Step \space Edit \space (press \space select \space step(s))}$

	SELECT

	Selected steps will blink. Press steps you want to edit
	Track Mode / Knob function
		Note:	
			Para 1 = CV
			Para 2 = Portamento
		Gate 
			Para 1 = Gate Intensity
			Para 2 = Gate Length
		Env
			Para 1 = Attack
			Para 2 = Release
		LFO 
			Para 1 = LFO Speed
			Para 2 = LFO Depth
	Press select again to leave edit mode 

