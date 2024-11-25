# dmenu - Dynamic Menu

dmenu is a fast, lightweight, and dynamic menu for X. Designed with simplicity and efficiency in mind, it provides an intuitive way to launch applications and manage your workflow.

---

## Requirements

To build and run dmenu, you need the following:

- **Xlib** header files and libraries installed on your system.

---

## Installation

1. **Configuration**
   Before building, edit the `config.mk` file to match your local setup. By default, `dmenu` is installed into the `/usr/local` namespace.

2. **Build and Install**
   Run the following commands to compile and install `dmenu`. Use `sudo` if required:

   ```bash
   make clean install
   ```

---

## Usage

To launch dmenu, use the following command:

   ```bash
   dmenu_run
   ```
This will display a menu of all executable commands in your PATH.
For additional options and configurations, refer to the manual page:

   ```bash
   man dmenu
   ```

---

## Customization
dmenu's behavior and appearance can be customized by editing its source code:

Modify the config.h file to set colors, fonts, and other preferences.

Recompile dmenu after making changes by running:

   ```bash
   make clean install
   ```

---

## Credits

dmenu is part of the suckless tools and adheres to their philosophy of minimalism.
It was created by the suckless.org team and is actively maintained by the community.
Current version includes custom modifications by Andrew in 2024, based on the original version.

---

## License

This project is licensed under the MIT/X Consortium License.
See the LICENSE file for more information.