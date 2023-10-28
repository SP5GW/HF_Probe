# RF_Probe



## Measuring QRP Transmitter Output Power  

The test setup required to perfrom transmitter output power measurement is depicted below:

Depending on RF probe type formulas used to calculate output power differ slightly.

In this section we will consider half-wave rectifier and full-wave rectifier (prototyped) probes.

In case of both designs we start with generic Power equations (we assume dummy load to fully resistive for 
all frequencies measurements are conducted for):

$P=U*I$

knowing that $R=U/I$, we can express current as: $I=U/R$, which when plugged into power equation above
gives us:

$P=U*2/R$

### Full-Wave Rectifier Probe Formulas

RF probe output voltage can be expressed as:

$Umeas=2*(Upeak - Uf)$, where Uf is voltage drop on single diode (in case of BAT46 Uf=0.45V)

from above equation Upeak can be calculated as:

$Upeak=(Umeas+2*Uf)/2$

Max power can be expressed as:

$Pmax=(Umeas+2*Uf)^2/4*R$

Similarly, RMS power can be expressed as:

$Urms=Upeak/sqrt(2)$, hence:

$Urms^2=Upeak^2/2$

$Prms=Upeak^2/2R$

$Prms=(Umeas+2Uf)/8*R$