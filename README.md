# FGA-Multi-User-Authentification-System-VHDL
Simple digital "combination lock" project implemented using a Basys3 FPGA Board using **VHDL** and **Vivado**.

## Working principle:

Allows two different users to have their own secret button-press combination. By using the directional buttons (Up, Down, Left, Right), users can enter a sequence to unlock the system, which will light a "succes" LED. It also includes a debouncing circuit to make sure every button press is registered cleanly without triggers.
