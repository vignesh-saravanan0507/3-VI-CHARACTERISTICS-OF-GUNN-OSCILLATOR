# 3-VI-CHARACTERISTICS-OF-GUNN-OSCILLATOR

**Aim:**

To study I-V characteristics of Gunn Diode and depth of modulation of modulation of PINdiode.

**Apparatus Used:**

Gunn power supply, Gunn oscillator, PIN modulator, Isolator, Frequency Meter, Variableattenuator, Detector mount, Slotted section, VSWR meter.

**Experimental Setup:**

<img width="880" height="180" alt="image" src="https://github.com/user-attachments/assets/c5e2a20b-5047-4518-886c-c020728660d5" />

**Theory**

The Gunn oscillator is base on negative differential conductivity effect in bulk semi- conductors. Gunn diode has two conduction bands separated by an energy gap (greater than thermal agitation energies). When an electron is moved to the satellite energy band, it will have negative differentialmobility. This produces the negative resistance required for the oscillations.
In a Gunn Oscillator, the Gunn diode is placed in a resonant cavity. In this case the oscillationfrequency is determined by cavity dimension than by diode itself. Although Gunn oscillator can be amplitude-modulated with the bias voltage, separate PIN modulator through is used in this experiment. A square wave modulating signal is applied through the modulator on to the microwave carrier signal.

<img width="740" height="455" alt="image" src="https://github.com/user-attachments/assets/fdb35fd0-f0d0-4d8f-9ae0-24f2057f0694" />


**Procedure:**

1.	Set the components and equipments as shown in figure above.
2.	Initially set the variable attenuator for maximum attenuation.
3.	Keep the control knob of Gunn power supply as below : Meter switch	:	‘OFF’
    Gunn bias knob	:	Fully anti-clockwise Pin bias knob/Mod Amplifier:	Mid position
    Pin mod frequency	:	Mid position
4.	Keep the, control knob of VSWR meter as below:
    Meter switch	:	Normal
    Input switch	:	crystal low impedance/ 200K Range db switch	:	50db
    Gain control knob	:	Fully clockwise
5.	Set the micrometer of Gunn oscillator between 5-7mm for required frequency of operation.
6.	‘ON’ the Gunn power supply, VSWR meter and cooling fan.
7.	Keep the mode switch of Gunn power supply to square wave/internal Modulation.
8.	Turn the meter knob to voltage position and note that, as Gunn bias voltage is varied currentstarts decreasing. This indicates negative resistance characteristic of Gunn diode. Apply the voltage such that the device is in the middle of the negative resistance region.
9.	Connect detector output to SWR meter.
10.	Adjust the square wave modulation frequency to approximately 1KHz.
11.	Change the meter range if no deflection is observed.
12.	Keep the slotted line probe at position where maximum deflection in meter is observed.
13.	Adjust the attenuator setting, gain control knob on VSWR meter and tune the detectorplunger for pointer to indicate VSWR 1.
14.	Move detector probe along the slotted line and note position of probe where pointer comes to extreme left position, which is first minimum. In order to know exact position of minimum note the positions of equal response points on either side of the minimum and then the midpoint of those positions will give position of minimum. The same way note nextminimum positions.
15.	Repeat the above procedure for different settings of micrometer.

**Depth of Modulation of PIN Diode:**

1.	Apply Gunn Bias Voltage slowly so that panel meter of Gunn power supply reads 8V.
2.	Tune the PIN modulator bias voltage and frequency knob for maximum output on theoscilloscope.
3.	Coincide the bottom of square wave oscilloscope to some reference level and note down themicrometer reading of variable attenuator.
4.	Now with help of variable attenuator coincide the top of square wave to same referencelevel and note down the micrometer reading.
5.	Connect VSWR to detector mount and note down the dB reading in VSWR meter for boththe micrometer reading the variable attenuator.
6.	The difference of both dB reading of VSWR meter gives the modulation depth of PINmodulator.

*Note: After tuning the Gunn source, the procedure for VSWR & Impedance measurement depthof PIN modulator.*

**B.Observation:**

| S. N. | Gunn Bias Voltage (V) | Gunn Diode Current (mA) | Observation        |
| :---: | :-------------------: | :---------------------: | :----------------- |
|   1   |          0.0          |           0.5           |                    |
|   2   |          1.0          |           5.2           |                    |
|   3   |          2.0          |           18.6          |                    |
|   4   |          3.0          |           28.0          | **Peak Current**   |
|   5   |          4.0          |           22.4          |                    |
|   6   |          5.0          |           17.0          |                    |
|   7   |          6.0          |           14.2          |                    |
|   8   |          7.0          |           12.0          | **Valley Current** |
|   9   |          8.0          |           13.5          |                    |
|   10  |          9.0          |           17.8          |                    |
|   11  |          10.0         |           23.0          |                    |
|   12  |          11.0         |           30.2          |                    |

Depth of modulation of PIN diode (sample readings & calc.)

Gunn bias used for modulation: 8 V (steady carrier).

Micrometer / attenuator position (carrier at reference level):

Top of square wave: micrometer = 4.5 mm → VSWR meter = -24 dB

Bottom of square wave: micrometer = 7.0 mm → VSWR meter = -30 dB

Difference ΔdB = 6 dB.

Convert ΔdB to amplitude ratio:

<img width="813" height="188" alt="image" src="https://github.com/user-attachments/assets/94971996-d12b-457d-bbb3-b38feabb4f9a" />

Depth of modulation ≈ 50%



**C.Analysis of Results:**
1.The I–V curve shows a rise in current up to a peak (~3 V, 28 mA), then a fall to a valley (~7 V, 12 mA) and a subsequent rise — this is the classic negative differential resistance (NDR) region of a Gunn diode.
2.The device should be biased in the mid-NDR region (between peak and valley) for stable microwave oscillation.
3.From PIN modulator measurements, a Δ of 6 dB between high/low detector readings gives an amplitude ratio ≈ 2, corresponding to ~50% modulation depth, indicating effective amplit

**D.Conclusions:**
The Gunn diode exhibits clear negative differential resistance with a peak around 3 V and a valley around 7 V, confirming conditions required for Gunn oscillation. The PIN diode modulator achieved a modulation depth of ≈ 50%, showing good amplitude modulation of the microwave carrier.

**Precautions:**

•	Check the connections before switching on the kit.
•	Connections should be done properly.
•	Observation should be taken properly.

**Result:**

The Gunn oscillator demonstrates the expected NDR behavior (peak ≈ 3 V, valley ≈ 7 V) and the PIN modulator produced a modulation depth of ≈ 50%.
