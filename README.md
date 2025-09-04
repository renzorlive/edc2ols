# edc2ols
EDCSuite is amazing at finding some key maps in EDC15 ECUs, however editing those maps is much more superior in WinOLS. WinOLS will not automatically detect most of EDC15 maps, so some help comes handy.

I created a Python script which will use EDCSuite's map detection logic through its DLL's and create a JSON file that you can simply import to WinOLS, saving you the hasssle of finding the maps manually. The script itself is really simple, I'll make the sources public on GitHub, but in the meantime, I'm also working on compiled .exe versions. Right now, using the script requires some Python knowledge.

It's really important to use the latest released version of EDCSuite (1.0.5) with the patched Parsers.dll. Then you simply copy the lib directory to the project's directory, and you can use it. You have to supply the name of the binary to the script, like ./main.py mod.bin.

https://github.com/krook1024/edc2ols

If you're interested in this project, please leave a comment below to let me know! I'll add a demonstration video today.
