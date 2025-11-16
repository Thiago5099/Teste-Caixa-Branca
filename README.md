# **Notação de Grafo de Fluxo**

O grafo de fluxo de controle baseado na imagem é composto pelos seguintes nós:

-   **Nó 1:** Início do fluxo.
    
-   **Nó 2:** Ponto de divisão do fluxo (segue para N3 ou N4).
    
-   **Nó 3:** Caminho alternativo que termina aqui.
    
-   **Nó 4:** Continuação principal vinda de N2.
    
-   **Nó 5:** Prosseguimento sequencial após N4.
    
-   **Nó 6:** Novo ponto de decisão (segue para N7 ou N8).
    
-   **Nó 7:** Caminho que leva ao nó final N9.
    
-   **Nó 8:** Caminho alternativo que termina aqui.
    
-   **Nó 9:** Nó final do ramo vindo de N7.
    

### **Arestas (ligações entre os nós):**

-   N1 → N2
    
-   N2 → N3
    
-   N2 → N4
    
-   N4 → N5
    
-   N5 → N6
    
-   N6 → N7
    
-   N6 → N8
    
-   N7 → N9

## Caminhos Básicos
- 1 → 2 → 3  
- 1 → 2 → 4 → 5 → 6 → 8  
- 1 → 2 → 4 → 5 → 6 → 7 → 9  

## Complexidade Ciclomática
Fórmula:  
**M = E – N + 2P**

Onde:  
- **E = 8** (arestas)  
- **N = 9** (nós)  
- **P = 1** (componentes conectados)

Cálculo:  
- M = 8 – 9 + 2×1  
- M = -1 + 2  
- **M = 1**
