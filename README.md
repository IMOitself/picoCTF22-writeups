# picoCTF 2022 writeups
every challenges i answered. with actual screenshots and recordings :D

the answers on how to get the flag are highlighted on the screenshots.

dont need to explain that much, goodluck :>

## Web Exploitation
<details>
<summary>- Local Authority - easy</summary>

**solution:**
- just check the **Network** on developer tools. check the js file. and look in the 'Response' tab
- ![](<web-exploit/local-authority/Screenshot 2026-08-12 150831.png>)

<br>

![](web-exploit/local-authority/Screenshot%202026-08-12%20151034.png)

</details>
<details>
<summary>- Inspect HTML - easy</summary>

**solution:**
- ![](<web-exploit/inspect-html/Screenshot 2026-08-12 151236.png>)

<br>

![](web-exploit/inspect-html/Screenshot%202026-08-12%20151308.png)

</details>
<details>
<summary>- Includes - easy</summary>

**solution:**
- ![](<web-exploit/includes/Screenshot 2026-08-12 151553.png>)
- ![](<web-exploit/includes/Screenshot 2026-08-12 151448.png>)

<br>

![](web-exploit/includes/Screenshot%202026-08-12%20151617.png)

</details>

<br>

## Cryptography
<details>
<summary>- Vigenere - medium</summary>

**solution:**
- ![](<crypto/vigenere/Screenshot 2026-08-12 151952.png>)

<br>

![](crypto/vigenere/Screenshot%202026-08-12%20152014.png)

</details>

<br>

## Reverse Engineering
<details>
<summary>- unpackme.py - medium</summary>

**solution:**
- ![](rev/unpackme.py/recording.gif)
- <details><summary>(as video player)</summary><video controls src="rev/unpackme.py/recording.mp4" title="Title"></video></details>

<br>

![](rev/unpackme.py/Screenshot%202026-08-12%20164222.png)

</details>
<details>
<summary>- unpackme - medium</summary>

**solution:**
- i opened it on ghidra. i found the exact hex that the program compare against to spit out the flag.
- ![](<rev/unpackme/Screenshot 2026-08-12 172148.png>)
- ![](rev/unpackme/recording.gif)
- <details><summary>(as video player)</summary><video controls src="rev/unpackme/recording.mp4" title="Title"></video></details>

<br>

![](rev/unpackme/Screenshot%202026-08-12%20172720.png)

</details>

<br>

## Forensics
<details>
<summary>- St3g0 - medium</summary>

**solution:**
- i use [aperisolve](https://www.aperisolve.com/). i only do the terminal just to show what tool worked.
- ![](forensics/st3g0/recording.gif)
- <details><summary>(as video player)</summary><video controls src="forensics/st3g0/recording.mp4" title="Title"></video></details>

<br>

![](forensics/st3g0/Screenshot%202026-08-15%20153500.png)

</details>
<details>
<summary>- Packets Primer - medium</summary>

**solution:**
- <video controls src="forensics/packets-primer/Screen Recording 2026-08-15 154103.mp4" title="Title"></video>

<br>

![](forensics/packets-primer/Screenshot%202026-08-15%20154024.png)

</details>
<details>
<summary>- Eavesdrop - medium</summary>

**solution:**
- i searched for the port 9002 as said on the conversation. the port is not visible by default on wireshark, just search for it on how to add it as a column.
- <video controls src="forensics/eavesdrop/Screen Recording 2026-08-15 160923.mp4" title="Title"></video>
- ![](forensics/eavesdrop/recording.gif)
- <details><summary>(as video player)</summary><video controls src="forensics/eavesdrop/recording.mp4" title="Title"></video></details>

<br>

![](forensics/eavesdrop/Screenshot%202026-08-15%20160719.png)

</details>
<details>
<summary>- File types - medium</summary>

**solution:**
- ![](forensics/file-types/recording.gif)
- <details><summary>(as video player)</summary><video controls src="forensics/file-types/recording.mp4" title="Title"></video></details>

<br>

![](forensics/file-types/Screenshot%202026-08-15%20192427.png)

</details>
<details>
<summary>- Redaction gone wrong - medium</summary>

**solution:**
- ![](<forensics/redaction-gone-wrong/Screenshot 2026-08-15 193452.png>)

<br>

![](forensics/redaction-gone-wrong/Screenshot%202026-08-15%20193527.png)

</details>
<details>
<summary>- Enhance! - medium</summary>

**solution:**
- ![](forensics/enhance!/recording.gif)
- <details><summary>(as video player)</summary><video controls src="forensics/enhance!/recording.mp4" title="Title"></video></details>

<br>

![](forensics/enhance!/Screenshot%202026-08-17%20174657.png)

</details>
<details>
<summary>- Lookey here - medium</summary>

**solution:**
- ![](forensics/lookey-here/recording.gif)
- <details><summary>(as video player)</summary><video controls src="forensics/lookey-here/recording.mp4" title="Title"></video></details>

<br>

![](forensics/lookey-here/Screenshot%202026-08-17%20155750.png)

</details>
<details>
<summary>- Torrent Analyze - medium</summary>

**solution:**
- <video controls src="forensics/torrent-analyze/Screen Recording 2026-08-17 165049.mp4" title="Title"></video>

- **DISCLAIMER**
  when u search the hash on google.

  it will spit out tons of spoilers.

  i did tried searching for the original linuxtracker.org page

  ITS NOT EVEN ON THE SITE ANYMORE

  this is what it should spits out [ctto](https://sutharnisarg.medium.com/picoctf-2022-write-up-torrentanalyze-495f13242bf8):
  ![](<forensics/torrent-analyze/Screenshot 2026-08-17 165324.png>)

  <br>

  **this is what the website now in 2026:**
  ![](<forensics/torrent-analyze/Screenshot 2026-08-17 165501.png>)

<br>

![](forensics/torrent-analyze/Screenshot%202026-08-17%20165922.png)

</details>
