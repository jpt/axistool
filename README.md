# axistool

axistool is a tool for axis interpolation and building avar tables ("axis mapping") inside glyphsapp.

# acknowledgements

this is linus romer's [stepinterpolation](https://github.com/linusromer/stepinterpolation) work, written in java and OFL-licensed; all I did was port it from java to python, and am building a glyphs UI on top of it. the `stepinterpolation` project itself is a generalization of [lucas de groot's interpolation theory](https://www.lucasfonts.com/learn/interpolation-theory). see [the typedrawers thread](https://typedrawers.com/discussion/2665/a-generalization-of-lucas-de-groot-s-interpolation-theory) for an explanation. 

# license

axistool is licensed under the SIL open font license (OFL); see the LICENSE file for more information.

# TODO

- actually make the UI lol. have the old family interpolation script for inspiration.
- get this working, using glyphs3 api to taget weight and optical axes (which just mean "any" axes)
- connect the interpolation to axis mapping in glyphs
