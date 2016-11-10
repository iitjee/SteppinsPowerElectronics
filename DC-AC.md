/*  Read this only along with Ned Mohan and Watch NPTEL https://www.youtube.com/watch?v=Dg5AIy0bY1A */






Say, when your power supply is failed and all the loads(appliances) are AC type. So what do you do?
You have a DC Battery and then we use an INVERTER, right!(to feed our AC appliances)

A simple example:
-----------------
Connect a load across DC source for certain time (say 10ms) and reverse connect it for another 10ms. Repeat the task.
You get a bipolar(+ve -ve) square wave voltage across the load.
Now if you decompose this square wave using Fourier series, you get a beautiful fundamental sine wave! :)

Therefore, the requirements on the switching network are:
1. Connect the load directly across the DC source (i.e +Vdc) &
2. Reverse connect the load across the DC source (i.e -Vdc)  &
3. Short the load

(In the DC-DC converters, we'd only 1 and 3 but in AC-AC converters we want all 3)











