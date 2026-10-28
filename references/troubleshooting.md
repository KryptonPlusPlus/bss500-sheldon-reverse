# Diário de Reparos: Placa de Potência

**1. Inspeção Visual e Medições a Frio**
- O fusível principal da rede estava ausente, e os fusíveis da placa (**F1** e **F2**) estavam rompidos (abertos).
- Capacitor de poliéster metalizado (*2A104J*) sem referência no *footprint* da PCB.
- **Transistores Q1 e Q4:** Testados fora da placa e estão íntegros.
- **Capacitores C90 e C92:** Testados fora da placa e apresentam medições normais.
- **Resistores R86, R89 e R95:** Testados fora da placa e estão dentro das tolerâncias. 
  - *Observação:* O resistor **R95** estava solda quebrada/fria, soltando-se da ilha apenas ao ser puxado.

**2. Primeiro Acionamento (Diagnóstico Inicial)**
- O teste de acionamento com lâmpada em série e o alto falante desconectado indicou alto consumo de corrente, acompanhado de um estalo na placa.
- O resistor **R95** apresentou aquecimento rápido e anormal.

**3. Intervenções e Novos Sintomas**
- Identificou-se que o diodo **D1** estava montado invertido (possível erro de fábrica ou de manutenção anterior). 
- Após corrigir a polaridade de **D1** e reenergizar, os resistores **R88** e **R87** carbonizaram imediatamente. 
    - *Nota:* O **R88** certamente abriu; o **R87** apenas escureceu pela proximidade e precisa ter a sua resistência aferida novamente.