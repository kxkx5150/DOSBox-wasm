# DOSBox-wasm

<br>

Windows10 WSL2 ubuntu 20.04  
python 2.7.18  
node 14.15.5  
emscripten 1.37.5  
fastcomp-clang-e1.37.5-64bit  

<br><br>

1. ./autogen.sh
2. emconfigure ./configure --enable-wasm
3. make
4. src (dosbox.html)

<br>

Demo  
https://kxkx5150.github.io/DOSBox-wasm/

<br><br><br><br>
Windows 95 emulated in the browser via DOSBox  
https://archive.org/details/win95_in_dosbox  

1. download package.zip
2. mkdir win95
3. AUTOEXEC.BAT and drive-c.img into win95
4. win95 into images/
5. ./packager.py win95 images/win95 AUTOEXEC.BAT
6. open http://localhost/DOSBox-wasm/docs/win95.html

<br><br><br><br>

DOSBox-wasm is based on em-dosbox  
https://github.com/dreamlayers/em-dosbox


# Credits
Most of the credit belongs to the DOSBox crew. They created DOSBox and made it compatible with a wide variety of DOS games. Ismail Khatib got DOSBox to compile with Emscripten, but didn't get it to work. Boris Gjenero started with that and got it to work. Then, Boris re-implemented Ismail's changes a cleaner way, fixed issues and improved performance to make many games usable in web browsers. Meanwhile, Alon Zakai quickly fixed Emscripten bugs which were encountered and added helpful Emscripten features.
