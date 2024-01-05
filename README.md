# audioMixer (WIP)
Active audio mixer with powerful headphone amp. Current iteration is for 2 analog inputs, 1 output, but future plans include an integrated USB DAC and microphone feedback.

# Features
- Gain knobs for each channel
- Trimpot for setting max gain (necessary for decent volume control on easy-to-drive headphones)
- Capable of driving 600 ohm headphones

# Current Progress
- Built up a v0 board, here's the issues:
-- Input volume control is backwards, so the volume control is pretty bad. Primary gain control seems to work fine.
-- Multiple inputs causes various bad noises
--- This is probably some sort of ground loop issue, since I have 3 ground connections back to the PC. Next revision will have some options to disconnect grounds from jacks to see if that helps.
--- More power input filtering might help as well.
-- It doesn't seem to really drive my HD600s any better than my Fiio BTR3k, at least not in a way I can notice
--- I'm gonna have to add a proper +- 12V supply and use a much stronger opamp next time to see if that helps
