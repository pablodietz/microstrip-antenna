<p align="center">
  <img height="300" src="images/logo.png">
</p>

# Microstrip Antenna
Design and implementation of microstrip antenna.

## Radiation Pattern: E and H Planes
The polarization of the microstrip antenna is linear such that the electric field vector is contained in the E-Plane and the magnetic field vector is contained in the H plane. It is observed that the type of power chosen considerably disturbs the radiation pattern of the antenna in Plane E.

<p align="center">
  <img height="300" src="images/EH-planes-ref.png">
</p>

The results of measurements and simulations are shown below.

<table align="center">
    <tr>
      <th align="center">H-Plane</th>
      <th align="center">E-Plane</th>
    </tr>
    <tr>
      <th align="center">
        <img height="300" src="images/H-plane.png">
      </th>
      <th align="center">
        <img height="300" src="images/E-plane.png">
      </th>
    </tr>
    <tr>
      <td align="left">
        Simulation:
        <ul>
          <li>G @ 2.4220 GHz = 3.8 dB</li>
          <li>SLL @ 2.4220 GHz = 16 dB</li>
          <li>Δθ -3dB @ 2.4220 GHz = 82°</li>
        </ul>
        Measurement:
        <ul>
          <li>SLL @ 2.4824 GHz = 6.8 dB</li>
          <li>Δθ(-3dB) @ 2.4220 GHz = 82°</li>
        </ul>
      </td>
      <td align="left">
        Simulation:        
        <ul>
          <li>G @ 2.4220 GHz = 3.8 dB</li>
          <li>SLL @ 2.4220 GHz = 16 dB</li>
          <li>Δθ(-3dB) @ 2.4220 GHz = 93°</li>
        </ul>
        Measurement:
        <ul>
          <li>SLL @ 2.4824 GHz = 10 dB</li>
          <li>Δθ -3dB @ 2.4220 GHz = 105°</li>
        </ul>
      </td>
    </tr>
</table>

## 3D Radiation Pattern

<p align="center">
  <img height="300" src="images/3D-1.png">
  <img height="300" src="images/3D-2.png">
</p>

## References
* C. A. Balanis, Antenna Theory: Analysis and Design, Third Edition, Wiley-Interscience, 2005.
* Warren L. Stutzman, Gary A. Thiele, Antenna Theory and Design, Third Edition, Wiley-Interscience, 2013.
