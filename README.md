# archmid-iso

This is the 64-bit source for the archmid iso.

How to use:
- Download either the zip file or use:  git clone https://github.com/midfingr/archmid-iso
- Extract the archive (if you downloaded the zip file) into your home folder
- Move the customrepo folder to your home folder

Change the permission of the archmid-iso to root
i.e. sudo chown -R root:root archmid-iso

As root open ~/archmid-iso/pacman.conf and change to Server=file:///home/your_user_name/customrepo/$arch (near the botton)

Navigate to ~/customrepo/x86_64
- In a terminal type:
repo-add customrepo.db.tar.gz *.tar.xz

Be sure to edit/build as root or sudo

<<<<<<< HEAD
Feel free to edit, add or remove packages, etc. as you see fit.
=======
Feel free to edit, add or remove packages, etc. as you see fit.
>>>>>>> c9d6834cd1bc356c3071143f64b087832c779c3a
