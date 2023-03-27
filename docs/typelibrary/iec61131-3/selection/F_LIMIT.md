###  **F\_LIMIT**

  _**Aus IEC 61131-3**_

![F_LIMIT](https://user-images.githubusercontent.com/113907647/227969677-48d51115-5416-4549-a035-b3f48c8c9c7a.png)

<table><tbody><tr><td>MN</td><td>Minimum</td><td>Unterer Wert</td></tr><tr><td>IN</td><td>Input</td><td>Aktueller Wert</td></tr><tr><td>MX</td><td>Maximum</td><td>Maximaler Wert</td></tr><tr><td>OUT</td><td>ANY_Elementary</td><td>Ausgang Min. oder Max.</td></tr></tbody></table>

Minimum bedeutet, unterschreitet IN diesen Wert sendet der Baustein das Signal für Wert unterschritten. 

Maximum genau andersrum.

Wert kann fix eingespeichert werden (durch Eingabe DINT#Wert) Bsp. Motortemperatur unter/überschritten. Oder Kraftstoff auf Reserve.

Vorgabewert kann aber auch individuell vom Anwender eingegeben werden. Über Terminal (Bsp. Zielvorgabe Slurry Tanker)

Bsp. Zapfwellendrehzahl festlegen mit Grenzwerten, Ausbringmenge Höchstwert Minimalwert festlegen .F\_LIMIT

![Textfeld:  
Bsp. individuelle Eingabe
](https://user-images.githubusercontent.com/113907647/227969678-3f0d95fb-4d18-4c0c-b4e1-b9bba3e22698.png)
