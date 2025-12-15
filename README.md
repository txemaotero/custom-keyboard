# Custom Split Keyboard Design and Development

## Idea

The initial idea is to decouple the development of the switch capsules from the ergonomic design of the case. This way, both can be prototyped in parallel.

### Switch Capsules

These components should meet the following goals:

- Securely hold the switches. They should snap in using the built-in tabs and offer some resistance (but not too much) when being removed.
- Hold the sockets. Ideally, they should fit snugly. Easy removal is not critical; in fact, they should withstand multiple switch insertions/removals.
- The socket pins must not touch the printed part to avoid melting during soldering.
- Be sufficiently strong. Print orientation will be important for this.

### Case

Things to consider:

- Finger travel → number of keys
- Tilt / inclination
- Palm / wrist rest. Something inspired by the Azeron could be interesting. Maybe a system where the wrist rest and the keyboard can be separated would be interesting. It'd provide portability to the keyboard.
- Trackball position
- Internal support for MCUs and the trackball board/bearings (separate prototype)
- Bottom cover

## Planning

### Initial Prototyping

- [ ] Switch capsules:
    - [x] Switch hole dimensions (snap-fit)
    - [x] Socket hole dimensions (both pins fit and sit flat)
    - [x] Socket retention mechanism
    - [x] Combined switch + socket hole
    - [ ] Polish final version
- [ ] Capsule cutouts: These will be integrated into the case
    - [ ] Test and adjust capsules so they snap in (they could also be glued)
- [ ] Trackball module
    - [x] Bearing holes
    - [-] Hole layout (3) to support the ball
    - [ ] Sensor board mount: review specs carefully
- [ ] MCU mounts
- [ ] Key layout and trackball positioning
    - [ ] Find optimal hand orientation and resting position. Start experimenting with track position.
    - [ ] Distribute and orient keys around the resting position
- [ ] Final assembly...

