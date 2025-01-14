Copyright-free, PII-free collision PoCs

# MD5

## FastColl

- GIF images [md5-1.gif](md5-1.gif) / [md5-2.gif](md5-2.gif)

## UniColl

- JPG images [md5-1.jpg](md5-1.jpg) / [md5-2.jpg](md5-2.jpg)
- PDF documents [md5-1.pdf](md5-1.pdf) / [md5-2.pdf](md5-2.pdf)
- PNG images
  - generic header, not 100% compatible [md5-1.png](md5-1.png) / [md5-2.png](md5-2.png)
  - specific header, common dimensions/colorspace [md5-s1.png](md5-s1.png) / [md5-s2.png](md5-s2.png)
- MP4
  - generic header, 32b length (LTV) [md5-1.mp4](md5-1.mp4) / [md5-2.mp4](md5-2.mp4)
  - generic header, 64b length (TLV) [md5-l1.mp4](md5-l1.mp4) / [md5-l2.mp4](md5-l2.mp4)
  - specific header [md5-s1.mp4](md5-s1.mp4) / [md5-s2.mp4](md5-s2.mp4)

- ZIP [md5-1.zip](md5-1.zip) / [md5-2.zip](md5-2.zip)

## HashClash

- PE executables [md5-1.exe](md5-1.exe) / [md5-2.exe](md5-2.exe)

# SHA1 (Shattered)

- JPG in PDF [sha1-1.pdf](sha1-1.pdf) / [sha1-2.pdf](sha1-2.pdf)

<!--
ffmpeg -i md5-1.png -c:v libx264 -tune stillimage -crf 22 -framerate 1/5 -c:a copy no.mp4 -map_metadata -1
-->
