# CPU 8 Bits - Ponderada M11

## 📋 Descrição

Este projeto implementa uma CPU simplificada de 8 bits desenvolvida como parte da ponderada do módulo M11. A CPU foi construída utilizando circuitos digitais e inclui uma Unidade Lógica Aritmética com adição, subtração, shifter, multiplicação, divisão, incremento e decremento.

## 🎯 Objetivos

Implementar uma CPU funcional de 8 bits com:
- ALU com operações aritméticas e lógicas
- Ciclos de fetch e execute
- Sistema de controle unificado
- Saída em displays de 7 segmentos

## ⚙️ Funcionalidades Implementadas

### ALU (Unidade Lógica Aritmética)
- ✅ **Soma** - Adição de operandos de 8 bits
- ✅ **Subtração** - Subtração de operandos de 8 bits  
- ✅ **Multiplicação** - Multiplicação de operandos de 4 bits
- ✅ **Incremento** - Incremento de 1 unidade
- ✅ **Decremento** - Decremento de 1 unidade
- ✅ **Divisão** - Divisão de operandos de 4 bits

### Arquitetura
- **Barramento de dados**: 8 bits
- **Palavra de instrução**: 8 bits
- **Memória**: ROM simulando RAM
- **Clock**: Sinal unificado
- **Saída**: Displays de 7 segmentos

## 📁 Estrutura do Projeto
Principais componentes:

```
src/
├── alu.dig                    # Unidade Lógica Aritmética principal
├── cpu.dig                    # CPU principal
├── controller.dig             # Controlador
├── instruction_decoder.dig    # Decodificador de instruções
├── pc.dig                     # Program Counter
├── rc.dig                     # Registrador de Controle
├── register_8bits.dig         # Registradores de 8 bits
├── register_4bits.dig         # Registradores de 4 bits
├── adder_de_8bits.dig         # Somador de 8 bits
├── subtrator_de_8bits.dig     # Subtrator de 8 bits
├── multiplicador_de_4bits.dig # Multiplicador de 4 bits
├── Divider_8bits.dig          # Divisor de 8 bits
├── incremento_de_8bits.dig    # Incrementador
├── decremento_de_8bits.dig    # Decrementador
```

## 🎥 Vídeo Explicativo
[![Vídeo Explicativo](cpu8bits_Dathmd1O.mp4)](cpu8bits_Dathmd1O.mp4)



