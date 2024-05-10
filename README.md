# Desafio Dio - Criando seu Primeiro Site Completo com HTML
Este projeto demonstra como criar um site completo e funcional usando HTML e CSS. O site é bem estruturado, acessível e otimizado para mecanismos de pesquisa. Os códigos fornecidos são apenas exemplos e podem ser personalizados para atender às necessidades específicas do projeto.,



## Conceitos Básicos  - Módulo 02 - HTML I 

Este desafio tem como objetivo, criar um site "quase" completo, com tudo o que vimos neste módulo. Os temas que deverão ser abordados são:
- Formulários
- Estruturação e formatação de texto
- Mídias
- Tabelas

## **Requisitos**

### **Estrutura do Site**

- O site deve ser dividido em várias páginas, como uma página inicial, uma página sobre, uma página de contato e uma página de blog.
- As páginas devem ser conectadas por meio de um menu de navegação.
- O site deve ter um rodapé que inclua informações de direitos autorais e links para as redes sociais.

### **Acessibilidade**

- O site deve ser acessível a todos os usuários, incluindo aqueles com deficiências.
- O site deve usar tags semânticas para melhorar a acessibilidade.
- O site deve fornecer texto alternativo para todas as imagens.

### **Otimização para Mecanismos de Pesquisa (SEO)**

- O site deve ser otimizado para mecanismos de pesquisa para melhorar sua visibilidade nos resultados de pesquisa.
- O site deve usar títulos e meta descrições otimizados.
- O site deve usar cabeçalhos para estruturar o conteúdo.

## Instruções
1. Você deve criar um site de uma clínica médica (você escolhe a especialidade)
2. Este site deve conter o seguinte menu de navegação:
    - Página Principal
    - Sobre a clínica
    - Horário de Atendimento
    - Contato
3. Deve, obrigatoriamente, utilizar todas os assuntos abordados nas aulas.

Abaixo como cada página deve ser criada e estruturada.

### Estrutura das páginas

Todas as páginas terão que seguir um padrão pré-definido. Como não aprendemos sobre CSS ainda, utilize o arquivo `template.html` para utilizar como base. Ele segue uma estrutura semelhante a image abaixo.

![Estrutura](https://i.stack.imgur.com/9jI6f.gif)

\* _No template tem algumas cores mas é apenas para melhor visualização. Fique a vontade para alterar da melhor forma._

No **Menu**, ficará localizado o menu de navegação (ah vá!), no **Header** de cada página ficará uma imagem, no **Footer** informações de contato, e o **Content** é o conteúdo de cada página.



### Página Principal

1. Deve ter uma imagem no **Header**.
2. Em **Content** uma breve descrição sobre a clínica.
3. **Menu** e **Footer** padrões em todas as páginas.

### Sobre a clínica
1. Deve ter uma imagem diferente no **Header**.
2. Em **Content** um texto falando sobre a clínica.
3. **Menu** e **Footer** padrões em todas as páginas.

### Horário de Atendimento
1. Deve ter uma imagem diferente no **Header**.
2. Em **Content** um pequeno texto falando sobre os serviços, e uma tabela de preços, onde cada linha é um serviço, com o preço de cada um de acordo com os dias da semana.

|Serviços |Segunda a Sexta | Sábados | Feriados |
|---|---|---|---|
|Clínica geral | 08h - 19h  | 08h - 14h | 08h - 14h  |
|Psicologia | 08h - 19h  | 08h - 14h | 08h - 14h  |
|Pediatria | 08h - 19h  | 08h - 18h | - |
|Oftalmologia | 08h - 19h  | 08h - 18h | - |
|||||

3. **Menu** e **Footer** padrões em todas as páginas.


### Contato
1. Deve ter uma imagem diferente no **Header**.
2. Em **Content** deve ter:
    - Os telefones de contato (celular e whatsapp)
    - Endereço completo da clínica
    - Um Iframe com o Google Maps apontando o endereço da clínica
    - Um formulário de contato com:
        - Nome (type="text")
        - E-mail (type="email")
        - Assunto (type="text")
        - Mensagem (textarea)
        - Botões de envias e limpar formulário

3. **Menu** e **Footer** padrões em todas as páginas.



