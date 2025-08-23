# :material-controller: Controls

!!! danger "Do not confuse hardware setup with button mapping for games/systems!"

    Do not confuse controller setup with **game-** or **core-specific** button remapping! This section is about the **global** controller setup to make the **hardware** work. If you want to remap the controls for a specific **game** or **emulator**, follow the guide for the respective emulator (e.g. [Retroarch](../retroarch/controls)).

Even though it was designed for handheld devices, KNULLI still supports various types of USB and Bluetooth controllers. Additionally, Knulli also supports other types of input devices, such as mice and keyboards.

If a controller does not work with your KNULLI-device out of the box, it might be necessary to map its buttons and directional controls to the corresponding game inputs, as explained in the sections below.

## The built-in controls

Most KNULLI-compatible devices are handhelds with built-in controls. They usually consists of a **directional pad** (:material-gamepad:, short: **D-pad**), the so called **face buttons** (:material-gamepad-circle:), some **shoulder buttons** (++"L1"++, ++"R1"++) and/or **shoulder triggers** (++"L2"++, ++"R2"++) and some buttons for ++"Start"++ and ++"Select"++. Additionally, your device will most likely have **power switch** and a **function button** (++"Function"++) which will be used for hotkey shortcuts. **Optionally**, your device might also have **analog sticks** and a **reset button**. If you do not know where those buttons are located on your device, please have a look at the manual of your device.

KNULLI comes with a set of pre-defined **hotkey shortcuts** which allow you to save, load, and quit your games, take screenshots, etc. We strongly recommend to **learn** the hotkey shortcuts. You will find a list of all default hotkey shortcuts in the [Hotkey Shortcuts](../../play/hotkey-shortcuts) section.

!!! info "Controller names"

    Depending on your device, your built-in controls have a distinct name. For example, on the Anbernic RG40XX H, the built-in controls are called `Anbernic RG40XX-H Controller`.

## Assigning controllers

After connecting a controller, the controller will be **automatically assigned** to the **next player** in line: The first controller you connect will be automatically assigned to player 1. If you connect a second controller, it will be automatically assigned to player 2 and so on. If a controller drops out (e.g., because it is turned off, disconnected, or runs out of battery), all other controllers automatically "move up": If the controller of player 1 is disconnected, to controller of player 2 will be reassigned to player 1 and so on.

### Use the built-in device controls for player 1

In case you want to always use the built-in controls as a controller for player 1, even if other controllers are connected,

* press ++"Start"++ to bring up the main menu
* go to *Controller & Bluetooth Settings*
* make sure that *Use Handheld Controls for Player 1* is *enabled*

!!! danger "Controller cannot be reassigned while in-game"

    Please **be aware** that controller assignments **do not work in-game** (except for a few ports, e.g. *TMNT: Shredder's Revenge*). Consequently, you need to **connect** your controllers **before** launching a game and you need to exit a game before you can have a controller drop out.

## Controller mapping

!!! danger "Do not attempt to remap the built-in controls"

    Each KNULLI build is **optimized** for the specific device it was designed for. Specifically, all built-in controls are **already mapped** for you. Do **not** attempt to remap the built-in controls in the *Controller & Bluetooth Settings* menu. By doing so, you might **break** any hidden virtual controls (e.g. the **D-pad-to-virtual-stick mapping** for devices without analog sticks, which usually can be toggled with ++"Function"+++++"Select"++). If you want to remap controls for certain *games* or *systems*, please do it within the respective game or emulator settings. The *Controller & Bluetooth Settings* menu is **not** the right place to map game- or system-specific controls!

To map the buttons and directional inputs of a controller, press the ++"Start"++ button to bring up the main menu, find *Controller & Bluetooth Settings* and select *Controller Mapping*. On-screen instructions will ask you to press and hold a button on the controller you want to map. Once the controller was detected, you will be guided through the process: Simply press the button on your controller which corresponds best to the button/function displayed on screen.

If you press a wrong button, don't worry: You will always be able to return to this menu and remap the controller again.

!!! danger "Face buttons are indicated by direction!"
    KNULLI supports several different controllers from different brands. Depending on your controller, labels on the face buttons might differ. Therefore, KNULLI names face buttons not by their label but by their direction.
    
    For example, out of the four face buttons, the **north** button (:material-gamepad-circle-up:) is labeled ++"X"++ on the standard SNES controllers. The same button is labeled ++"Y"++ on Xbox controllers and ++"△"++ on PlayStation controllers.
    
    Make sure that you do **not** confuse the directional **face buttons** (:material-gamepad-circle-up: :material-gamepad-circle-right: :material-gamepad-circle-down: :material-gamepad-circle-left:) with the **D-pad** directions (:material-gamepad-up: :material-gamepad-right: :material-gamepad-down: :material-gamepad-left:)! You will find more information about face buttons in the [Hotkey shortcuts](../../play/hotkey-shortcuts) section.
