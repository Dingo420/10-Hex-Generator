# Telus Specific Keyspace Reducer
<b>What's new</b><br>
Big hacked mess of code. but removed hex specific things and added telus specific things<br>
this is such a hack, appended strings may or may not work , it was hacked with no additional appended strings attached.<br>
<br>
Added: more reducer strings to prevent starting with same char eg 11 aa pp <br>
Added : // if any 2 chars in the first 5 are consecutive identical, none of the last 5 are consectutive identical<br>
Added : // no 4 chars are alternating such as: 0101, 2323, etc <br>
Changed : each char cannont appear more than 3 times to 2.<br>
Added : // there must be at least 1 letter in the first 2 characters THIS IS RISKY BUT SEAMS LIKE A GAMBLE THIS SHOULD PROBABBLY BE 3 char <br>
Changed : random output to mode 4 for faster output???   // METHOD 4 - 65,400 H/s <br>
Changed : character set to: abcdefghjknprt0123456789 Characters not used : ilmoqsuvwy<br>
<b>this reduces a lot!</b>

more details to come... maybe<br><br>
<b>known keys</b><br>
<br>
4t6h55ekfh<br>
sxz5rzbxrr<br>
44ef2e92fb<br>
e80c193ce3<br>
984b895c77<br>
943588d93d<br>
7ac4489633<br>
8ae667a9c4<br>
694e7d783b<br>
570734d1db<br>
8bc090fc22<br>
0a171ffba5<br>
<br>
im new to github and forked this from https://github.com/wpatoolkit/10-Hex-Generator <br>
just giving credit where credit is due, i definitly did not write this from scratch!<br>
<br>
<br>
To compile on Linux:<br>
`g++ Telus.cpp -o Telus`
To Run with hashcat
`Telus | cudaHashcat64 -m 2500 CAP.hccap`<br>
pipes its output into <a href="http://hashcat.net/oclhashcat/">cudaHashcat</a> (NVIDIA)<br>
<br>
<b>And dont forget rockyou.txt with rules</b>
