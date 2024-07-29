# Endless Error Message Script

This repository contains instructions for creating a script that displays an endless error message using `zenity`. The script will continuously show an error dialog until you either reboot your system or stop it manually by pressing `Ctrl + C`.

## How to Set Up the Endless Error Message Script

Follow these steps to create and run the endless error message script:

### 1. Create the Script File

1. Open a terminal and create a new script file:

    ```bash
    nano ~/endless_error.sh
    ```

2. Copy and paste the following content into `endless_error.sh`:

    ```bash
    #!/bin/bash

    # Endless loop to show error messages
    while true; do
        zenity --error --text="THIS IS AN ENDLESS ERROR MESSAGE. Press Ctrl+C to stop or reboot your system."
    done
    ```

3. Save the file and exit the editor:
    - Press `Ctrl + X`
    - Press `Y` to confirm saving
    - Press `Enter` to exit

4. Make the script executable:

    ```bash
    chmod +x ~/endless_error.sh
    ```

### 2. Run the Script

To execute the script and start displaying the endless error message:

1. Open a terminal and run:

    ```bash
    ~/endless_error.sh
    ```

2. The script will start displaying error messages. To stop it, you can either:
    - Press `Ctrl + C` in the terminal where the script is running.
    - Reboot your system.

## License

This project is licensed under the MIT License.

## Contact

For any questions or issues, please contact [Charlieulmanxiv@gmail.com].

