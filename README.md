# axistool

axistool is a tool for axis interpolation and building avar tables ("axis mapping") inside glyphsapp.

# acknowledgements

without linus romer's [stepinterpolation](https://github.com/linusromer/stepinterpolation), written in java and OFL-licensed, this project would not be possible. stepinterpolation is a generalization of [luc(as) de groot's interpolation theory](https://www.lucasfonts.com/learn/interpolation-theory). see [the typedrawers thread](https://typedrawers.com/discussion/2665/a-generalization-of-lucas-de-groot-s-interpolation-theory) for an explanation. 

# license

axistool is licensed under the SIL open font license (OFL); see the LICENSE file for more information.

# TODO

- actually make the UI lmao
- get this working using glyphs3 api (this runs in glyphs3 right now, but applying the axes should consider the API; I have a bunch of old glyphs2 scripts I need to port)
- connect the interpolation to axis mapping in glyphs (similarly have accomplished this in glyphs2 already but want to do "right way" within g3 - coming soon)
