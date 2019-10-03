# infidbp5_19
Aufgaben für INFI DBP 19/20

do that 

```JAVA
public class Person{}
```

This could be a table for you

| Code        | Erklärung           | Beispiel  |
| ------------- |:-------------:| -----:|
| 00 00      | Ventil öffnen    | 00 00 |
| 01 00      | Ventil schließen |   01 00 |
| 02 xx      | Ventil öffnen bis xx cm (in HEX)      |    02 60: öffnen bis 96cm erreicht |
| 03 xx | Sendeintervall festlegen. xx in min (HEX) | 03 01: Sende jede Minute|
| 04 xx [yy] [zz] | xx = Sendeintervall, optional yy = Ventil öffnen bis, optinal zz = Ventil 2 öffnen bis | 04 01 60: Jede Minute senden, Ventil öffnen bis 96cm erreicht |
