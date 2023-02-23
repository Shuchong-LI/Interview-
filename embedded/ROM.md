# ROM 

Some questions about ROM.

## ROM list

- Mask ROM (MROM): This type of ROM is programmed during the manufacturing process, and its contents cannot be changed. MROM is used to store firmware and other critical system code that needs to remain constant over the life of the product.

- Programmable ROM (PROM): This type of ROM can be programmed after it is manufactured using a device called a programmer. Once programmed, the contents of PROM cannot be changed. PROM is often used in low-volume production runs where customized firmware is required.

- Erasable Programmable ROM (EPROM): This type of ROM can be programmed and erased multiple times using ultraviolet light. To erase the contents of an EPROM, it must be removed from the circuit board and exposed to ultraviolet light for a specified amount of time. EPROM is used for prototyping and development because it allows firmware to be changed and updated.

- Electrically Erasable Programmable ROM (EEPROM): This type of ROM can be programmed and erased electronically. Unlike EPROM, EEPROM can be erased and reprogrammed while it is still in the circuit board. EEPROM is used for storing configuration data, calibration data, and other settings that may need to be changed over time.

- Flash Memory: This is a type of EEPROM that can be erased and reprogrammed in blocks. Flash memory is used in a wide range of applications, including smartphones, digital cameras, and solid-state drives. It is commonly used for storing firmware, operating systems, and other critical system code.

## Chat GPT

**I:**
In PC,what does the ROM contain?

**Chat GPT:**
In a PC, there are several types of ROM (Read-Only Memory) chips that contain critical system information that is required for the computer to boot up and operate properly. Here are some examples of what the ROM chips in a typical PC might contain:

BIOS (Basic Input/Output System): The BIOS chip contains the firmware that initializes the hardware and performs a power-on self-test (POST) when the computer is turned on. It also provides a low-level interface between the hardware and the operating system, allowing the OS to access and control the hardware devices.

UEFI (Unified Extensible Firmware Interface): Some modern PCs use UEFI instead of BIOS to initialize the hardware and boot the OS. The UEFI firmware is stored on a special type of ROM chip called the SPI (Serial Peripheral Interface) flash memory.

Option ROM: Many hardware devices, such as graphics cards and RAID controllers, have their own ROM chips that contain firmware called option ROM. These ROMs provide additional functionality and features for the devices and are loaded by the BIOS or UEFI during the boot process.

CMOS (Complementary Metal-Oxide-Semiconductor): The CMOS chip contains a small amount of non-volatile memory that stores the computer's configuration data, such as the date and time, hardware settings, and passwords. This data is maintained by a small battery even when the computer is turned off.

In summary, the ROM chips in a PC contain critical system information that is required for the computer to boot up and operate properly, including the BIOS/UEFI firmware, option ROMs for hardware devices, and the CMOS configuration data.

**I:**
I can not change the ROM data in my PC? 

**Chat GPT:**
That's correct. Once the data has been programmed into a ROM (Read-Only Memory) chip, it cannot be changed. In a typical PC, there are several ROM chips that store critical system information, such as the BIOS (Basic Input/Output System) firmware, which initializes the hardware and starts the boot process when the computer is turned on. These ROM chips are designed to be permanent and unchangeable.