
# **Pi Zero 2 Mount for Toybox Alpha V2**
**Adapting the Pi Zero 2 to the Toybox Alpha V2 3D Printer**

---

## **Introduction**

Welcome to the **Pi Zero 2 Mount for Toybox Alpha V2** project. This README provides step-by-step instructions for mounting a Pi Zero 2 into the Toybox Alpha V2 3D printer. This modification reuses the existing OEM mounting holes and utilizes an adapter plate, ensuring a seamless fit without the need for additional modifications to the printer's frame.

Please note that while the Pi Zero 2 can be physically wired and powered over the board's UART, it will not have any communication with the stock board because I have been unable to get the stock board to flash.

---

## **Disclaimer**

**Proceed with caution:** This modification may void your warranty and could potentially damage your hardware if not done correctly. Ensure you're comfortable with disassembly and reassembly of your printer before attempting this mod.

---

## **Materials Required**

- **Pi Zero 2**: The central component of this mod.
- **Adapter Plate**: Custom-designed to fit the Pi Zero 2 using the OEM holes.
- **M2.5 5mm Screws (4)**: To mount the Pi Zero 2 to the adapter plate.
- **OEM M3 Screws (4)**: To secure the adapter plate to the base.
- **Basic Tools**: Screwdrivers and pliers for assembly.

---

## **Step-by-Step Instructions**

### **1. Prepare the Printer**

- **Power Off and Unplug:** Ensure the Toybox Alpha V2 is powered off and unplugged.
- **Disassemble as Necessary:** Remove the existing ESP12 board by taking off the internal cover and disconnecting any necessary wiring.

### **2. Mount the Pi Zero 2 to the Adapter Plate**

- **Align the Pi Zero 2:** Position the Pi Zero 2 over the designated holes in the adapter plate.
- **Secure the Pi Zero 2:** Use the M2.5 5mm screws to attach the Pi Zero 2 to the adapter plate. Ensure the Pi Zero 2 is securely mounted.

### **3. Install the Adapter Plate to the Frame**

- **Align the Adapter Plate:** Position the adapter plate, with the Pi Zero 2 attached, over the OEM mounting holes on the frame.
- **Secure the Adapter Plate:** Use the OEM M3 screws to secure the adapter plate to the frame. Ensure it is firmly attached without over-tightening.

### **4. Reassemble the Printer**

- **Reconnect Wiring:** Reconnect any wiring that was disconnected during disassembly.
- **Replace the Internal Cover:** Reattach the internal cover to protect the electronics.
- **Test the Installation:** Power on the printer to ensure the Pi Zero 2 is functioning correctly within the system.

---

## **Side Note**

I, **ProtoRiot**, have been unable to get Klipper to flash on the OEM board, which is why the Pi Zero 2 cannot communicate with the stock board. As a result, I am opting to pair the Pi Zero 2 with an SKR Pico instead.

---

## **Conclusion**

This modification allows you to integrate a Pi Zero 2 into your Toybox Alpha V2 3D printer with minimal effort. By reusing the OEM holes and utilizing a custom adapter plate, this mod maintains the integrity of the printer while enhancing its capabilities.

---

## **Contributing**

If you have suggestions or improvements for this mod, feel free to contribute by forking the repository, submitting pull requests, or opening issues.

---

## **License**

This project is licensed under the GPL v3.0 License - see the `LICENSE.md` file for details.

---

## **Acknowledgments**

- **Community Support:** Thanks to the 3D printing and maker communities for ongoing inspiration and support.
