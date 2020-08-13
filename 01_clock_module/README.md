
# Clock Module

## Bugfixing first attempt

### Symptoms

When switch is set to astable timer, then top two LEDs flash but blue LED does not.  When the switch is in the other position, then nothing flashes at all, even when the button is pressed.

### Changes

- Moved incorrect U1:3 -> U5:2 amended to expected U1:3 -> U5:1.  Did not fix problems.

## Reference materials in brief

---

![Buggy build](./buggy_01.jpg "Buggy build first attempt, with debug LEDs in place.")

**Figure 1**: Buggy board, after first attempt.

---

![Correct build](./correct_minimal.png "Build completed by instructor.")

**Figure 2**: Correct build, completed by instructor.

---

![Correct schematic](./clock.png "Target schematic.")

**Figure 3**: Correct schematic circuit diagram.

---

![555 timer](../pinout_diagrams/LM555_diagram_modified_Fairchild.png)

**Figure 4**: Pinout for 555 Timer unit.

---

![QUAD AND](../

/74LS08.png "Pinout for AND array.")

**Figure 4**: Pinout for 74LS08 QUAD AND unit.

---

![QUAD OR](../pinout_diagrams/74LS32-Quad-2-Input-OR-Gate.png "Pinout for OR array.")

**Figure 5**: Pinout for 74LS32 QUAD OR unit.

---


![HEX Inverter](../pinout_diagrams/74LS04-pinout.jpg "Pinout for hex inverter.")

**Figure 6**: Pinout for 74LS04 hex inverter unit.

---

