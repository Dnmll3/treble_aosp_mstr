# Building PHH-based A13 GSIs #


To get started with building AOSP GSI, you'll need to get familiar with [Git and Repo](https://source.android.com/source/using-repo.html), and set up your environment by referring to [LineageOS Wiki](https://wiki.lineageos.org/devices/redfin/build) (mainly "Install the build packages") and [How to build a GSI](https://github.com/phhusson/treble_experimentations/wiki/How-to-build-a-GSI%3F).

---

- First, open a new Terminal window in your home directory, yes, home directory cuz I hardcoded it to my script, then clone this repo with the following commands:
       
       Make directory command

         ```shell 
         mkdir treble_aosp_mstr; cd treble_aosp_mstr 
         
	 git clone https://github.com/mstrbl8r/treble_aosp_mstr.git -b 13 ; cd ./treble_aosp_mstr
	 ```  


---

- If you skipped Phhs GSI building guide then issue this command to set everything up: `bash ./ready-distro.sh <required:git name> <required:git mail>`
- If you *didn't skip* and *actually read it* like anyone who is about to clone **hundreds of gb**, skip to next part.
---

- Finally, start the build script (Will generate arm64-bvn variant by default, edit 62nd line for others):

	```shell
	bash ./build.sh
	```
---

This script is made by someone who learned how to create .patch files overnight just recently.

If you want flexible, reliable and customizable build scripts feel free to edit my stuff or use the sources I used.

Thanks
- [phhusson](https://github.com/phhusson)
- [AndyYan](https://github.com/AndyCGYan)
- [Ponces](https://github.com/ponces)
- [iceows](https://github.com/Iceows)
- [harvey186](https://github.com/LeOS-GSI)
- [sooti](https://github.com/sooti)
- [frax3r](https://github.com/utkustnr)
