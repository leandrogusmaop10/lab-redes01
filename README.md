![GitHub License](https://img.shields.io/github/license/leandrogusmaop10/lab-redes01)

# Laboratório de redes 01 - projeto de rede local 
projeto desenvolvido na diciplina de redes de computadores no curso técnico de informatica do SENAC

Aluno:Leandro Gusmão

Professor: José de assis

Data: 09/03/2026


---

## 1. Objetivo
Implementar uma rede local simpres conectando 3 notbooks a 3 roteadores wireless com switch integrado e uma impressora de rede.

O projeto será realizado em duas etapas:

1. Simulação dad rede no cisco packt tracer
2. Implementação de rede no laboratório real

---


## 2. Equipamentos utilizados neste laboratório

-3 notebooks
- 1 roteador wirelless com 1 porta WAN e 4 portas LAN
- 1 impressora de rede
- cabos de redes

---

## 3. topologia da rede

Diagrama lógico da rede utilizada neste laboratório

```mermaid
graph TD

WAN[ Internet / WAN de Provedor]

Router[Roteador Wireless<br>1 porta WAN<br> 4 portas LAN]

PC1[Notebook 1]
PC2[Notebook 2]
PC3[Notebook 3]

Printer[Impressora de Rede]


WAN -->|Porta WAN|Router

Router -->|LAN 1| PC1
Router -->|LAN 2| PC2
Router -->|LAN 3| PC3
Router -->|LAN 4| printer


