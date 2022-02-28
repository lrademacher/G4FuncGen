# G4FuncGen
Simple Function Generator based upon STM32G474 Nucleo Board

## Modes:
 - Off
 - Sinus
 - Square
 - Ramp
 - Noise
 
## Parameters:
 - Frequency
   - range: [0.01Hz; ???]
 - Amplitude[V]
   - range: [0; (3V3 / 2)] 
 - Offset[V] 
   - range: [(Amplitude / 2); (3V3 - Amplitude)]
 - Opt: DutyCycle[%] (in square mode) 
   - range: [0; 100]

