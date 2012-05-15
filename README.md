Cheetah Texture Packer
------------------------------

Just best texture packer:)

If you know Russian - welcome: http://www.gamedev.ru/projects/forum/?id=161714

Watch me if you want to see changes:)

This program uses UBFG's algorithm: https://github.com/scriptum/UBFG

Format of .atlas file (same as UBFG's .fnt):

	Arial 9pt -- font name and size
	Name  X pos   Y pos   Width   Height   Xoffset  Yoffset  Orig W   Orig H   Rot
	32    0       0       0       0        3        14       3        14
	97    90      36      5       7        1        4        7        14       r
	98    0       41      5       9        1        2        7        14


Here:

* Name - name of packed image with full path
* X pos - x position of image on texture
* Y pos - y position of image on texture
* Width - width of image on texture (images are cropped and Width and Orig Width aren't equal)
* Height - height of image on texture
* Xoffset - distance on the x-axis, on which image must be shifted
* Yoffset - distance on the y-axis, on which image must be shifted
* Orig W - original width of image
* Orig H - original height of image
* Rotation - if r - image rotated

![Help image](https://github.com/scriptum/UBFG/raw/master/readme.png)

Screenshot:

![Screenshot](https://github.com/scriptum/Cheetah-Texture-Packer/raw/master/screen.png)