# FEM-flyback-model
A finite-element model of a flyback transformer

In this project, a flyback transformer is modelled using ANSYS Maxwell software.
A flyback transformer was initially designed to generate high voltage sawtooth signals at high frequencies. It consists of a ferrite rod, a primary winding that is connected to an ac voltage source and one -or two- secondary windings. A simple electrical equivalent of this transformer is seen in the figure below:
 ![image](https://github.com/Ahsnazari/FEM-flyback-model/assets/118515566/16f293ed-d4d3-4ec4-b696-ae59d1b750f8)

The voltage source discussed here has a frequency of 40KHz and a domain of 35 Volts.
Using Maxwell 3d, this is the model:
 ![image](https://github.com/Ahsnazari/FEM-flyback-model/assets/118515566/e8ec2bf3-d932-46fc-a15d-baf90631b78b)

It is evident that three windings are utilized in this transformer.
This gif represents the magnetic flux:
![flux1](https://github.com/Ahsnazari/FEM-flyback-model/assets/118515566/eb1029b1-6515-41da-aa2b-ae858b1a9577)


This plot represents the inductances between windings: self-inductance of A, AB inductance, AC inductance:
 ![image](https://github.com/Ahsnazari/FEM-flyback-model/assets/118515566/b2e5153d-db70-48f5-9f6b-6938d0907d5a)

Since the winding was assumed to be simple wire there is no fluctuation. It is expected for Litz wire to fluctuate a lot with time.
Currents of each winding:
 ![image](https://github.com/Ahsnazari/FEM-flyback-model/assets/118515566/f87b59fc-82b6-4f8c-aba4-d6e93a0f3739)

The stranded loss:
 ![image](https://github.com/Ahsnazari/FEM-flyback-model/assets/118515566/dd7cd79a-98e8-40a4-ac5e-1a6bab8f77b4)

The induced voltage in secondary windings:
 ![image](https://github.com/Ahsnazari/FEM-flyback-model/assets/118515566/ba18cf6b-c3a6-4d44-a2d8-342893542fba)

