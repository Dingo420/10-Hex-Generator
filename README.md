# Telus Specific Keyspace Reducer
<b>What's new</b><br>
Big hacked mess of code. but removed hex specific things and added telus specific things
<br><br>
<b>What is it?</b><br>
changed the character set to: abcdefghjknprt0123456789<br>
Characters not used : ilmoqsuvwy<br>
this reduces a lot!<br>

more details to come... maybe<br>
<br><br>


To compile on Linux:<br>
`g++ 10hex.cpp -o10hex`

`10hex | cudaHashcat64 -m 2500 CAP.hccap`<br>
pipes its output into <a href="http://hashcat.net/oclhashcat/">cudaHashcat</a> (NVIDIA)
