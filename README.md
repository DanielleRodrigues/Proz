# 🎵 Desafio: Configuração de Rede para o Show da Banda de Miguel

Este repositório contém a solução para o desafio de criar uma rede de computadores para a equipe de produção do show da banda de Miguel. A rede foi configurada utilizando o **Cisco Packet Tracer**, garantindo que todos os membros da equipe possam se comunicar de forma eficiente durante o evento.

---

## 📋 Cenário

Durante o show, os membros da equipe de produção, espalhados pelo teatro, precisarão de comunicação constante para assegurar o controle e a organização. Para modernizar essa infraestrutura, foi projetada uma **topologia de rede em estrela** que conecta todos os membros da equipe a um **switch central**.

---

## 🛠️ Passos Realizados

### 1. Definir o Cenário
- A equipe de produção conta com **quatro computadores** (um para cada membro).
- A comunicação entre os computadores é essencial para a execução do evento.

---

### 2. Montar a Topologia
- Uma nova topologia foi criada no **Cisco Packet Tracer**.
- Um **switch** foi posicionado no centro da área de trabalho.
- **Quatro PCs** foram dispostos ao redor do switch, simbolizando os membros da equipe.

---

### 3. Conectar os Dispositivos
- Cada computador foi conectado a uma porta diferente do switch utilizando **cabos Ethernet**.
- A topologia resultante forma uma estrutura de **rede em estrela**, ideal para centralizar a comunicação.

---

### 4. Configurar os Endereços IP
- Cada computador recebeu:
  - Um **nome identificador** (PC1, PC2, PC3, PC4).
  - Um **endereço IP** exclusivo dentro da mesma sub-rede, por exemplo:
    - PC1: `192.168.1.1/24`
    - PC2: `192.168.1.2/24`
    - PC3: `192.168.1.3/24`
    - PC4: `192.168.1.4/24`
- O switch foi configurado para operar como intermediário na comunicação, sem necessidade de endereçamento IP.

---

### 5. Testar a Comunicação
- Para validar a configuração:
  - O comando **`ping`** foi executado de cada computador para os demais.
  - O sucesso do ping confirmou a comunicação plena entre os dispositivos.

---

## 📂 Conteúdo do Repositório

- **Arquivo da Topologia**: O arquivo `.pkt` gerado no Cisco Packet Tracer com a configuração completa.
- **Prints de Tela**:
  - **Topologia da Rede**: Imagem mostrando a rede em estrela configurada.
  - **Testes de Comunicação**: Prints do comando `ping` executado com sucesso em todos os computadores.
- **README.md**: Este arquivo, explicando o processo e o propósito do projeto.

---

## 🚀 Como Executar o Projeto

1. Baixe o arquivo `.pkt` do repositório.
2. Abra-o no **Cisco Packet Tracer**.
3. Teste a comunicação:
   - Acesse o prompt de comando em qualquer computador.
   - Execute o comando:
     ```bash
     ping 192.168.1.X
     ```
     Substitua `X` pelo final do endereço IP dos outros computadores.





