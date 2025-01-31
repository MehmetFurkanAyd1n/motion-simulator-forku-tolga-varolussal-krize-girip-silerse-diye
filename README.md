# 2DOF Motion Simulator
This is a motion simulator that can be used with flight / car / space simulations. It offers 2DOF movement with a relatively cheap build.

Building progress is documented on my YouTube channel (it's in Turkish, but auto subs work quite good)

<a href="https://www.youtube.com/watch?v=YvgvKRb7HTE" target="_blank">Part 1</a>

<a href="https://www.youtube.com/watch?v=mRH1yEFcxOI" target="_blank">Part 2</a>

<img src="https://github.com/tolgaozuygur/motion-simulator/blob/main/sim_photo.jpg" title="Motion Sim" alt="Motion Sim" width="500">

## ELECTRONICS & SOFTWARE
Here is a nice <a href="https://www.xsimulator.net/community/threads/smc3-arduino-3dof-motor-driver-and-windows-utilities.4957/" target="_blank">tutorial</a> to setup the electronics and the software.
I also designed a simple arduino shield PCB (included in this repo). If you get that manufactured it will make the wiring a lot easier. You can easily get it produced with a service like <a href="https://www.jlcpcb.com" target="_blank">Jlcpcb</a>

## MOTORS
You will need 2 motors to move the simulator. Their specs should be:
- 12-24V 
- 200-300W
- 40-70 rpm

For reference, I have used these <a href="https://www.keskinlerelektronik.com/urun/85zy24-245-a-24v-50rpm-korumali-silecek-motoru" target="_blank">motors</a> .

## BUILDING THE SIMULATOR
You can open the source files in Solidworks. assembly_chair.SLDASM includes the fully assembled chair.

Sheet metals to be laser cut: mafsal_mount_base, mafsal_mount_top, motor_mount, motor_mafsal_baglantisi should be at least 8-10mm steel. The rest can be aluminum.

STL files can be 3d printed with any material (I used PLA)

("Mafsal" is a shift rod universal joint, sorry for the weird naming)

## MOTION COMPENSATION
If you will use VR you will need motion compensation. I use a Quest 3 headset and the easiest way to do motion compensation with it is <a href="https://www.infusevr.com/" target="_blank">Infuse VR</a>

Here is a <a href="https://www.youtube.com/watch?v=juNZTGpDjnA" target="_blank">tutorial video</a> to set it up.




