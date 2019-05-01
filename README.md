# opencv

This repository contains some simple tasks I've done using opencv lib.

### They are:

* **Binarization_sign.ipynb**
* **Photo_2_Scan.ipynb** 

Use this two to make easier your bureaucratic routine.

* **Бинаризация руки (кожи) на плохом фоне.ipynb**

It has some exp of hand / skin shape extraction (segmentation) from part of image that definitely contains such object (comes from hand detector). 

As I saw it is creative / experimental task to segment the skin. So I choose to test the idea of thresholding in HSV and some other color spaces + a set of filter transformations.

It works pretty nice, but not for the production (go deeper and stack layers xoxoxo).

Main problems here were the background that is so similar in every color space to the skin and the existance of other skin structures (as neck, face, etc) in some set of images.

* **Подсчет домов на снимке со дрона.ipynb**

This ntbk solves buildings counting task in the images provided by a drone. It is the most simplified solution that could ever be, I just wasn't interested in developing the real thing for free for *that* guys >:D
