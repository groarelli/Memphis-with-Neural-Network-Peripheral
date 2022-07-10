# Memphis-with-Neural-Network-Peripheral
  The Memphis plaform was developped by Marcelo Ruaro from PUC-RS university. This repository consists in a memphis-adapted source code from the final paper "Neural Networks Modules Integration in a Manycore System: a case study", by Gustavo de Medeiros Roarelli, from University of Brasília, with Prof. Dr. Marcelo Grandi Mandelli as advisor. A link to this final  paper is tbd by the University of Brasília.
  
  All the modified and added  files can be found in the lists below, and the explanation is found in the source codes. 

  The Memphis documentation and the installation tutorial, in english and in portuguese, can be found at https://www.inf.pucrs.br/hemps/memphis.html

Memphis's Software:

  List of modified files:
	
	
	
    .../memphis/software/include/api.h
    .../memphis/software/include/services.h
    .../memphis/software/kernel/slave/kernel_slave.c
    .../memphis/software/modules/packet.h

  List of added files:
	
	

    - .../memphis/software/modules/peripheral_communications.h
    - .../memphis/software/modules/peripheral_communications.c


Memphis's Hardware:
  
  List of modified files:
	
	
    - .../memphis/hardware/sc/memphis.cpp
    - .../memphis/hardware/sc/memphis.h
    - .../memphis/hardware/sc/test_bench.cpp
    - .../memphis/hardware/sc/test_bench.h
    
  List of added files:
	
	
    - .../memphis/hardware/sc/peripherals/neural_peripheral.h
    - .../memphis/hardware/sc/peripherals/neural_peripheral.cpp
    - .../memphis/hardware/sc/peripherals/nn.h
    - .../memphis/hardware/sc/peripherals/nn.cpp
    - .../memphis/hardware/sc/peripherals/network_g.h
    - .../memphis/hardware/sc/peripherals/network_g.cpp
    - .../memphis/hardware/sc/peripherals/neuron_g1.h
    - .../memphis/hardware/sc/peripherals/neuron_g2.h
    - .../memphis/hardware/sc/peripherals/neuron_g3.h
    - .../memphis/hardware/sc/peripherals/activation_function.h
    - .../memphis/hardware/sc/peripherals/activation_function.cpp
    - .../memphis/hardware/sc/peripherals/dfs.h

    
