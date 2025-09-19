# Diário de Bordo: Projeto de Agendamento em Figma

Este documento resume as etapas principais do design de um protótipo de aplicativo de agendamento de salão de beleza, utilizando o Figma. Meu objetivo foi aprender os conceitos de **componentes**, **variantes**, **auto layout** e **prototipagem**.

---

### **1. A Base do Design**

* **Configuração do Ambiente:** Eu criei um novo arquivo no Figma e defini as telas (`Frames`) para o projeto, como a **`Tela de Login`** e a **`Tela de Agendamento`**.
* **Guia de Estilos:** Eu defini as cores (`Marsala-Principal`, `Rosa-Destaque`, `Branco-Fundo`) e os estilos de texto (`H1 - Título`, `Corpo-Texto` e `Corpo-Texto-Semibold`) para garantir a consistência visual.

---

### **2. A Mágica dos Componentes**

* **Componentes Principais:** Eu criei "moldes" reutilizáveis para os elementos mais importantes do aplicativo:
    * `Botao-Principal`
        * `Campo-de-Entrada`
            * `Cartao-Servico`
                * `Botao-Data`
                    * `Botao-Horario`
                        * `Filtro-Horario`
                        * **Variantes:** Eu aprendi a criar diferentes "estados" para um mesmo componente. Por exemplo, o `Botao-Horario` tem um estado `Ativo` (disponível) e um estado `Inativo` (agendado), e o `Filtro-Horario` tem os estados `Manhã`, `Tarde` e `Noite`.

                        ---

                        ### **3. Organização com Auto Layout**

                        * **Organização de Listas:** Para organizar a lista de serviços e os horários, eu utilizei o **`Auto Layout`** para alinhar e espaçar os elementos automaticamente. Isso garante que, ao adicionar ou remover itens, o design se ajusta sozinho.
                        * **Design Responsivo:** Eu apliquei a rolagem horizontal (`Horizontal scrolling`) e o "recorte de conteúdo" (`Clip content`) para criar a navegação da semana. Isso permite que a faixa de datas, que é maior que a tela, possa ser deslizada, otimizando o espaço na tela do celular.

                        ---

                        ### **4. Dando Vida ao Protótipo**

                        * **Conexão de Telas:** Eu usei a aba **`Protótipo`** (`Prototype`) para conectar os cliques dos botões a outras telas ou a outras ações.
                        * **Interações Dinâmicas:** Eu adicionei a lógica para que os botões de filtro (`Manhã`, `Tarde`, `Noite`) mudem de estado ao serem clicados.

                        ---

                        ### **Resumo Final**

                        Este projeto me ensinou a pensar como um designer e a construir um protótipo funcional do zero. Eu aprendi que dominar o uso de componentes e auto layout é fundamental para criar designs eficientes e escaláveis.
