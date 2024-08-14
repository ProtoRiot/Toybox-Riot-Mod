
# **Pi Zero 2 Mount for Toybox Alpha V2**

## **Project Overview**

This project documents the process of replacing the ESP12 board in the Toybox Alpha V2 with a Pi Zero 2. The Pi Zero 2 offers enhanced capabilities and flexibility compared to the factory ESP12 board. This modification involves removing the display/internal cover, disconnecting the UART wiring, and designing a custom mount to fit the Pi Zero 2 in the place of the ESP12.

## **Steps Involved**

1. **Remove the Display/Internal Cover:**
   - The 4 panel screws, located at the wider pattern at the 4 corners, need to be removed first.
   - After removing these screws, carefully angle the panel to remove it from the frame.
   - Disconnect the ribbon cable for the display from the controller board (not pictured).

   ![Factory Board](https://github.com/ProtoRiot/Toybox-Riot-Mod/PiZero2-Mount/images/esp12.jpg)

2. **Remove the ESP12 Board:**
   - The ESP12 board is approximately 23mm x 43.5mm with a mounting pattern of approximately +/- 0.1mm.
   - Disconnect the UART wiring from the controller board to the WiFi/host controller.

   ![Bottom of Printer Showing ESP12 holes](https://github.com/ProtoRiot/Toybox-Riot-Mod/PiZero2-Mount/images/factory_holes.jpg)

3. **Prepare the Pi Zero 2 Mount:**
   - The Pi Zero 2 has dimensions of 23mm x 58mm, slightly longer than the ESP12 board.
   - Two of the four factory holes are reusable, making the installation straightforward.

   ![Pi Zero Sitting with Wires Plugged In](https://github.com/ProtoRiot/Toybox-Riot-Mod/PiZero2-Mount/images/pi_zero_UartMock.jpg)

4. **Print the Pi Zero 2 Mount:**
   - Use the CAD file provided in the `/CAD` folder to print the mount.
   - Ensure the mount fits securely in place using the existing holes and any additional screws or supports.

   ![3D Printed Mount](https://github.com/ProtoRiot/Toybox-Riot-Mod/PiZero2-Mount/images/Pi_Zero_Mount.jpg)

5. **Install the Pi Zero 2:**
   - Place the Pi Zero 2 onto the custom mount.
   - Secure it in place using the existing screws or additional supports.

   ![Pi Mounted with Adapter](https://github.com/ProtoRiot/Toybox-Riot-Mod/PiZero2-Mount/images/Final_Mount.jpeg)

## **Additional Resources**

- **Images:**
   - Photos of the removal and installation process can be found in the `/images` folder.
   - These images will guide you through each step visually.

- **CAD Files:**
   - The CAD file for the Pi Zero 2 mount is available in the `/CAD` folder.
   - Use this file to print your custom mount.

## **Disclaimer**

This modification is intended for experienced users who are comfortable with disassembling and modifying electronics. Proceed with caution, as modifying your Toybox Alpha V2 may void warranties and carries the risk of damaging your hardware. Ensure that you have a backup plan in case issues arise during the modification process.

## **License**

This project is licensed under the GPL v3.0 License - see the `LICENSE.md` file for details.

## **Acknowledgments**

Special thanks to the 3D printing and maker communities for their ongoing support and inspiration.
