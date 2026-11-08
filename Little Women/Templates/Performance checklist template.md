---
created: "{{date}} {{time}}"
date: "{{date}}"
tags:
  - performance
curtain:
house open:
curtain speech:
Act I:
intermission:
Act II:
bows:
end of show:
---
# {{date:dddd, MMMM D, YYYY}}

---
## Preflight

- [ ] Open Tech booth
- [ ] Open Equipment room
- [ ] Crestron
	- [ ] Start
	- [ ] Advanced mode
	- [ ] > Video
	    - [ ] PC -> Projector
	    - [ ] PC -> Audio
	    - [ ] Camera -> BOH 1
	    - [ ] Camera -> BOH 2
	    - [ ] Camera -> Lobby
	    - [ ] Camera -> Stream
	  - [ ] > Settings
	    - [ ] Projector screen up
	- [ ] > Volume
		- [ ] Boost dressing room volume
		- [ ] Boost lobby volume
		- [ ] Mute lobby
- [ ] 2nd Crestron
	- [ ] House full
	- [ ] Fixture power: on
	- [ ] Work lights: off
- [ ] Sound
	- [ ] Start sound board
	- [ ] Load showfile
	- [ ] Turn on front fills
	- [ ] Verify front fill levels at 3:00
	- [ ] Turn on booth monitors
- [ ] Lights
	- [ ] Start light board
	- [ ] Load showfile
	- [ ] goto cue `0.1`
	- [ ] Verify lights onstage
- [ ] Primary computer
	- [ ] Start computer
	- [ ] QLab
		- [ ] Load QLab showfile
		- [ ] Preflight cue list
		- [ ] `s0` Verify TheatreMix responds
		- [ ] `0.1` Verify lighting console responds
		- [ ] `v1` Verify projection onstage
	- [ ] TheatreMix
		- [ ] Load TheatreMix showfile
		- [ ] Connect TheatreMix to Sound board
		- [ ] Load cue `0`
		- [ ] Verify soundboard channels changed to actor names
		- [ ] Load cue `0.1`
		- [ ] Verify Main channel strip reads `0.1`
	- [ ] OpenSoundMeter
		- [ ] Start OSM
		- [ ] Confirm reference mic signal
	- [ ] Ardour
		- [ ] Start Ardour
		- [ ] Create new from show template
- [ ] Mics
	- [ ] Get mics from tech closet
	- [ ] Add batteries to all mics
	- [ ] Turn on all mics
	- [ ] Check battery levels
	- [ ] Distribute mics to actors
	- [ ] Sound check

---
## House open

- [ ] goto `1` House open
- [ ] Crestron 1 > unmute lobby
- [ ] Crestron 2 > House out

---
## Curtain speech

- [ ] Booth lights dim

---
## Show
- [ ] Start
- [ ] End
---
## Postflight

- [ ] Mics
	- [ ] Get mics from actors
	- [ ] Remove batteries from all mics
	- [ ] Return mics to equipment room
- [ ] Sound
	- [ ] Turn off sound board
	- [ ] Turn off monitors
	- [ ] Turn off front fills
- [ ] Projector
	- [ ] Turn off projector
- [ ] QLab
	- [ ] Shut down QLab comuter
- [ ] Lights
	- [ ] Turn off lighting console
	- [ ] Cover lighting console
- [ ] Crestron 2
	- [ ] House lights off
	- [ ] Works off
- [ ] Crestron 1
	- [ ] Power off
- [ ] Lock Equipment room
- [ ] Lock Tech booth
- [ ] Lock PAC

## Notes
