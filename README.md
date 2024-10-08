# Embroidery machine sp33d

**On how to use with almost full autonomy the embroidery machine.**

Prerequisite : being at the digital workshop.

Fabrics you can use : less than 1mm of thickness, be careful if the fabric is elastic or too thin.

## Warning

If the machine stops during the embroidery, with an error message asking to check the upper and bobbin thread but the upper thread is fine, please DO NOT RE START THE MACHINE immediatly.
Lift the frame slightly to check underneath the fabric, and make sure the thread isn't tangled, either with itself or in the bobbin compartment.

If it's tangled, cut as much as possible with the stitch ripper or cissors, or take out every stitches that has knots and restart the embroidery from the last clean part.

If it's not tangled at all, check that the bobbin still has thread and is well placed, and if everything is okay, the machine can be restarted.

## Content
* Basic manipulation on the machine
    * [1. Place the fabric on the frame](#1-place-the-fabric-on-the-frame)<br>
    * [2. Placing the frame on the machine](#2-placing-the-frame-on-the-machine)<br>
    * [3. Add a pattern via USB](#3-adding-a-pattern-via-USB)<br>
    * [4. Start the embroidery](#4-Start-the-embroidery)<br>
* Using Ink/Stitch
    * [A. Create a .pes pattern with Inkscape and Ink/Stitch](#A-Creating-a-pes-pattern-with-Inkscape-and-InkStitch)<br>

* Other manipulations on the machine
    * [B. Thread the needle](#B-Thread-the-needle)<br>
    * [C. Filling the bobbin](#C-Filling-the-bobbin)<br>
    * [D. Placing the bobbin](#D-Placing-the-bobbin)<br>
    * [E. Tighten or loosen the top thread](#E-Tighten-or-loosen-the-top-thread)<br>

* [To go further](#To-go-further)



## 1. Place the fabric on the frame

It is advised to ALWAYS add a stabilizer sheet (tear-away or wash-away) underneath the fabric inside the frame.

Take the adequat-sized frame in relation to the size of your pattern, and loosen the screw.
The default frame is the 10*10cm one.

![Premier cadre'](./images/img0_1.jpg)

Place the fabric on top.

![Premier cadre'](./images/img0_2.jpg)

Place on top the largest part of the frame.
Make sure the fabric get stuck in the most straight and tight way possible, by pulling the outside parts carefully.

![Premier cadre'](./images/img0_3.jpg)
![Premier cadre'](./images/img0_4.jpg)

Make sure both parts of the frame are well aligned and pressed against each other, so the fabric is tight on the bottom part of the frame.

![Premier cadre'](./images/img0_5.jpg)
![Premier cadre'](./images/img0_6.jpg)

Tighten the screw while keeping the fabric tight.

![Premier cadre'](./images/img0_7.jpg)

## 2. Placing the frame on the machine

Place the frame with the tight part of the fabric on top.

![Premier cadre'](./images/img0_8.jpg)

Slide the arms of the frame underneath the metal pieces of the arms of the machine.

![Premier cadre'](./images/img0_9.jpg)

Push the frame until both side are interlocked and until the metal buttons of the machine have clicked in the holes of the arms of the frame.

![Premier cadre'](./images/img0_11.jpg)
![Premier cadre'](./images/img0_13.jpg)

## 3. Adding a pattern via USB

**After creating a .pes pattern**

Put the USB key in the machine, on the side of the interface.

![Premier cadre'](./images/img0_14.jpg)

Enter the USB menu.

![Premier cadre'](./images/img0_15.jpg)

Select the pattern to embroider.

![Premier cadre'](./images/img0_16.jpg)

Click `Régler` to choose size and position.

![Premier cadre'](./images/img0_17.jpg)

Make sure the pattern fit the dotted lines, re-size it with the first button on the left with the square, and/or move it with the arrows butttons on the right if needed, then click `Broder`.

![Premier cadre'](./images/img0_18.jpg)

## 4. Start the embroidery

Press the locking button on the screen (if red = the machine is locked).

<!--//photo-->

Press the up arrow button ⬆️ to start the embroidery.

<!--//photo-->

To stop an ongoing embroidery, press the up arrow button ⬆️ again.

# If necessary :

## A. Creating a .pes pattern with Inkscape and Ink/Stitch

Install [Inkscape](https://inkscape.org) and the [Ink/Stitch](https://inkstitch.org/fr/) extension.

Open your image (png, jpeg, svg) with Inkscape.

If the image isn't a svg, you can do `Chemin` > `Vectoriser un objet matriciel` to turn it into a svg.

![Premier cadre'](./images/img3_1.png)

Click `Appliquer` in the window of the right, then only keep the svg by suppressing the image underneath.

![Premier cadre'](./images/img3_2.png)

Select the image and open `Extensions` > `Ink/Stitch` > `Paramètres`.

![Premier cadre'](./images/img3_3.png)

Modify the default settings if needed, and click `Apply and quit`.

![Premier cadre'](./images/img3_4.png)

Before exporting, you can preview the embroidery by opening `Extensions` > `Ink/Stitch` > `Visualiser et exporter` > `Simulateur/ Aperçu réaliste`.

![Premier cadre'](./images/img3_10.png)

To export as a .pes, save the image.

![Premier cadre'](./images/img3_5.png)
![Premier cadre'](./images/img3_6.png)

To adapt the size of the image to the size of the embrodery, you can change the size into cm ou mm:

![Premier cadre'](./images/img3_7.png)

![Premier cadre'](./images/capture11.png)

### Creating a pattern with two or more colors:

Import a svg with multiple colors into Inkscape, and start transforming your image through `Chemin` > `Objet en chemin`.
Then, you can do the same thing than with one color : `Extensions` > `Ink/Stitch` > `Paramètres`, modify the default settings if needed, and click `Apply and quit`, and export in .pes.

![Premier cadre'](./images/homographie.svg)
*The svg image*

![Premier cadre'](./images/img3_8.png)
*The embroidery preview in Inkstitch*

![Premier cadre'](./images/img3_9.jpg)
*The final embroidery, not looking very good because of the quality of the fabric in relation with the stitch of the pattern*

<!--## B. Créer un motif .pes avec le logiciel PE Design

Ouvrir le logiciel PE Design.

![Premier cadre'](./images/Capture1.png)

Aller dans l'onglet `Image` puis cliquer sur `Piqûre automatique` et sélectionner l'image choisie.

![Premier cadre'](./images/Capture2.png)

Rogner le motif si besoin, puis cliquer sur `Suivant` pour lancer le calcul de conversion de l'image en motif de broderie.

![Premier cadre'](./images/Capture4.png)

Après le premier calcul de conversion, on peux changer la sensibilité de la réduction des parasites et de la segmentation pour affiner le rendu. On peux également décider du nombre de couleur max (ici : 2, le tracé et le fond), puis décider de supprimer des couleurs en cliquant dessus dans la partie `Omettre les couleurs des parties`. Ici j'ai supprimé la couleur du fond, qui est barrée.

![Premier cadre'](./images/Capture6.png)

Redimensionner le motif afin qu'il rentre dans le cadre blanc.

![Premier cadre'](./images/Capture7.png)
![Premier cadre'](./images/Capture8.png)

Pour exporter, cliquer le logo du logiciel en haut à gauche, puis `Enregistrer sous...` .

![Premier cadre'](./images/Capture9.png)

Enregistrer en format .pes.

![Premier cadre'](./images/Capture10.png) -->

## B. Thread the needle

**Careful : the machine must be turned off !**

Put the bobbin on the first stick, and pass the thread through the hole 1.

![passage du fil dans le premier trou'](./images/img1_1.jpg)

Then pass the thread through the hole 2, on the top of the machine, and pass it in both little corners next the small wheel.

![passage du fil dans le second trou'](./images/img1_2.jpg)

Following the diagram, pass the thread clockwise around the wheel controlling the thread tension.

![passage du fil dans la molette'](./images/img1_3.jpg)

Pass the thread under the metal piece of the second small wheel.

![passage du fil dans la dernière molette'](./images/img1_4.jpg)

Lower the thread along the right slit, pass it under the 4 part with the arrow, and raise it through the left slit.

![passage du fil dans les fentes'](./images/img1_5.jpg)

Pass the thread from right to left in the hole 5, and lower it through the left slit.

![passage du fil dans le trou devant'](./images/img1_6.jpg)

Pass the thread through the hole 6 on the front of the machine.

![passage du fil dans le dernier trou'](./images/img1_7.jpg)

Push the thread behind the small metal piece on the right of the needle, by pulling the thread along the needle et pushing it with the small tool.

![passage du fil à coté de l'aiguille'](./images/img1_8.jpg)

**At this point, turn the machine on**

To thread the needle, press the `Threading the needle` button on the bottom right corner on the machine.

![passage du fil dans l'aiguille'](./images/img1_10.jpg)

Two small hooks appaears on both side of the needle.
You must pull the thread under both hooks and press the button again for the hooks to pull the thread.

![passage du fil dans l'aiguille'](./images/img1_9.jpg)

If one of these steps has been forgotten or done in the wrong way, the thread can be too tight or not enought, or break.

To change the color of the thread, the easiest way is to unthread the needle, then cut the thread between hole 1 and 2.
Then, place a new bobbin, pass its thread through hole 1 and tie it to the thread out of the machine before hole 2.
Finally, just pull slowly the thread after hole 6 until the knot is through.

<!-- photo !!-->

## C. Filling the bobbin

Get the bobbin from the little trap underneath the needle.

![find the bobbin](./images/img3_0.jpg)

Take it out by lifting the hinge part.

![lift the hinge](./images/img3_01.jpg)

Take the bobbin out of its container.

![take the bobbin out](./images/img3_02.jpg)

Choose the thread for the bobbin (here : lila), and pass it through the numbers that are in circles.

![pass the thread](./images/img3_1.jpg)

![pass the thread](./images/img3_2.jpg)

![pass the thread](./images/img3_3.jpg)

Make some turns with the thread around the empty bobbin, then place the bobbin on the axis on the side of the machine.

![the bobbin with some turns of thread](./images/img3_4.jpg)
![the axis](./images/img3_51.jpg)

Block the thread on the small slit on the side.

![the thread in the slit](./images/img3_6.jpg)

Pull the little bent part on the bobbin.

![the bent part pulled](./images/img3_7.jpg)

On the screen of the machine, the bobbin menu appear.
Click on "Démarrer". The axis will turn until the bobbin is full.

![the screen of the machine](./images/img3_8.jpg)

Pull back the bent part in its default position, cut the thread and take out the bobbin from the axis. You can place the bobbin back in the machine.

## D. Placing the bobbin

**Warning : it is better if the machine is turned off !**

Place the bobbin with the thread going clockwise in the bobbin container.

Pull 5cm of the thread out, and slide it in the little slit on the side of the container.

![the thread in the slit](./images/img4_1.jpg)

Slide the thread on the side and make it go out the hole along the slit.

![the thread out of the hole](./images/img4_3.jpg)

Placer the container with the bobbin in its place.

![the container in the place](./images/img4_4.jpg)

Push it in place until you hear a click, and close the trap.

![the container in the place](./images/img4_5.jpg)

![the container in the place](./images/img4_6.jpg)


## E. Tighten or loosen the top thread

The top thread is too loose if the embroidery looks loose, or if the thread does loops and curls and knots during the embroidery process (the loops get tangled > the knots breaks the thread > the machine stops).

Its too tight if you can see too much of the spool thread on top of the embroidery, or if it breaks during the embroidery process.

You can tighten or loosen the thread by turning both the small top wheel on top of the machine or the big wheel just underneath it.

To tighten the thread : clockwise :

![Premier cadre'](./images/img2_1.jpg)

To loosen the thread : anticlockwise :

![Premier cadre'](./images/img2_2.jpg)

<!--//photo de broderies foirées-->

# To go further

The [Brother machine of the workshop instruction manual](https://download.brother.com/welcome/doch100509/vr_dom01eu_fr.pdf).

List of [embroidery machine tutorials](https://edutechwiki.unige.ch/fr/Catégorie:Guide_de_tutoriels_de_broderie_machine).

The comic [The Dancing Plague](https://www.selfmadehero.com/books/the-dancing-plague).
