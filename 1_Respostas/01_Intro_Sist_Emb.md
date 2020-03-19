#*1*. O que são sistemas embarcados?

    Combinações de hardware e software que eventualmente podem ter partes mecânicas e elétricas, sendo que 
    desempenham uma função específica. Além disso, podem também fazer parte de um produto ou sistema maior.

#*2*. O que são sistemas microprocessados?
    
    Assim como sistemas embarcados, são combinações de hardware e software, além de um firmware (programa armazenado na ROM 
    associado a um sistema microprocessado específico). Ademais, os principais componentes são: CPU, ROM, RAM, periféricos de           
    saída e entrada, decodificador de endereços, circuit reset e clock. A linguagem usada para este tipo de sistema é de baixo 
    nível, ou seja, mais próxima da linguagem de máquina.

#*3*. Apresente aplicações de sistemas embarcados: 

    (*a*) Para a indústria automotiva; 
    Freio ABS, painel do carro.

(*b*) Para eletrodomésticos; 

    Ar condicionado, máquina de lavar.

(*c*) Para automação industrial.

    CNC (Comando Numérico Computadorizado), CLP (Controlador Lógico Programável).

#*4*. Cite arquiteturas possíveis e as diferenças entre elas.

    -As arquiteturas de microprocessadores mais conhecidas são de Von Neumann, instruções e dados compartilham a mesma unidade física de memória; e Havard, instruções e dados são compartilhados em memórias diferentes.
    -GPP (General Purpose Processors) é um processador que não apresenta finalidade única.
    -ASP (Application Specific Processors) processador otimizado para uma função única, podendo ainda dividir-se em: DSP (Digital Signal Processors), ASIC (Application Specific Integrated Circuits) chip construído para uma atividade exclusiva.
    -SoCs (System on Chip): chip que apresenta todos os componentes de um computador, podendo conter funções digitais, analógicas e de radiofrequência.

#*5*. Por que usamos o Raspberry Pi na disciplina, ao invés de outro system-on-chip?

    Apesar do desempenho excepcional de um system-on-chip, este apresenta a arquitetura RISC (Reduced Instruction Set Computing),   
    computação onde um número reduzido de instruções etão disponíveis; contudo, este tipo de arquitetura não é compatível com a maior partes dos pragramas que utilizam instruções de 32 ou 64 bits.
