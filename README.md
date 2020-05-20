# Telus Specific Keyspace Reducer
<b>What's new</b><br>
Big hacked mess of code. but removed hex specific things and added telus specific things<br>
this is such a hack, appended strings may or may not work , it was hacked with no additional appended strings attached.<br>
<br><br>
<b>What is it?</b><br>
changed the character set to: abcdefghjknprt0123456789<br>
Characters not used : ilmoqsuvwy<br>
this reduces a lot!<br>

more details to come... maybe<br>

im new to github and forked this from https://github.com/wpatoolkit/10-Hex-Generator <br>
just giving credit where credit is due, i definitly did not write this from scratch!<br>
<br><br>


To compile on Linux:<br>
`g++ Telus.cpp -o Telus`
To Run with hashcat
`Telus | cudaHashcat64 -m 2500 CAP.hccap`<br>
pipes its output into <a href="http://hashcat.net/oclhashcat/">cudaHashcat</a> (NVIDIA)
