# Example: Red Mesh Wifi

En este ejemplo se configuraron varios nodos, para que constantemente enviaran informacion de un contador al nodo Root

## GPIO functions:

 * GPIO18: output
 * GPIO19: output
 * GPIO4:  input, pulled up, interrupt from rising edge and falling edge
 * GPIO5:  input, pulled up, interrupt from rising edge.

## Test:
 * Connect GPIO18 with GPIO4
 * Connect GPIO19 with GPIO5
 * Generate pulses on GPIO18/19, that triggers interrupt on GPIO4/5
