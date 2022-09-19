# Neptune2-practical-mods/X-Axis-Belt-Shim

This is an X-axis belt shim for ELEGOO Neptune 2 series 3D printers.
It makes X belt parallel to the X axis (gantry) and equalize the nozzle travel scale over the all position on the axis.
Therefore, the accuracy of the printed model is improved.

|The shim|The shim installed on the toolhead|
|---|---|
|![Shim1](Images/shim-image-001.jpg)|![Shim](Images/shim-image-002.jpg)|


## The theory

If the belt is not parallel to the axis: $\Delta X_{in} \ne \Delta X_1$ and $\Delta X_2 \lt \Delta X_1$.

![Image1](Images/image-001.png)

Correct belt parallel to the axis: $\Delta X_{in} = \Delta X_3$ and $\Delta X_4 = \Delta X_3$.

![Image1](Images/image-002.png)

### Correcting belt path of Neptune 2 series

It is 5mm off at the stepper side and is 3.8mm off at the idler side.

## Installing

You can print two shims and install on the toolhead, one is stepper side the other is idler side, under the gantory.

|Stepper side|Idler side|
|---|---|
|![Installed1](Images/install-001.jpg)|![Installed2](Images/install-002.jpg)|

## Authors

marbocub - Initial work

## License

Copyright (c) 2022 marbocub marbocub@gmail.com, All rights reserved.

This project is licensed under the CC-BY-NC-SA 4.0 - see the [LICENSE](../LICENSE) file for details.
