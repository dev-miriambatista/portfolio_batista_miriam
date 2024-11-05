# Projeto: Portfólio Pessoal

Este é o código-fonte para um portfólio pessoal, que apresenta seções como cabeçalho, apresentação, sobre mim, habilidades e projetos. O design é responsivo e adaptável a diferentes tamanhos de tela, utilizando CSS Flexbox para layout e animações.

## Estrutura do Projeto

O projeto é dividido em várias seções, cada uma responsável por uma parte do portfólio:

1. **Cabeçalho (`.container_cabecalho`)**: Um cabeçalho fixo que contém o título do portfólio e a navegação. Estilizado com cores e tipografia personalizada.

2. **Apresentação (`.container_apresentacao`)**: Uma seção que exibe uma imagem e uma breve introdução. A imagem possui uma animação suave que a faz flutuar.

3. **Sobre Mim (`.container_sobre_mim`)**: Esta seção fornece informações pessoais e uma descrição detalhada. Inclui um título estilizado e um texto justificado.

4. **Habilidades (`.container_skills`)**: Uma lista de habilidades apresentadas como ícones. Os ícones ampliam ao serem passados com o mouse, proporcionando um efeito visual dinâmico.

5. **Projetos (`.container_projetos`)**: Uma galeria de projetos em que cada item contém uma descrição, imagem e links relevantes. Os itens são dispostos em um layout flexível, permitindo que se ajustem ao espaço disponível.

## Estilos CSS

Os estilos são organizados de forma a serem aplicados conforme o tamanho da tela, utilizando media queries para garantir uma boa apresentação em dispositivos desktop. Aqui estão alguns pontos principais sobre os estilos:

- **Layout Flexível**: Utiliza `display: flex` para a maioria das seções, permitindo uma disposição dinâmica dos elementos.
- **Efeitos Hover**: Muitas das interações são acompanhadas de transições e transformações ao passar o mouse, melhorando a experiência do usuário.
- **Responsividade**: O uso de unidades relativas (como `vw` e `vh`) ajuda a garantir que o layout se ajuste a diferentes tamanhos de tela.
- **Animações**: Inclui animações como flutuação da imagem e efeitos de escala para os itens de habilidades e projetos.

## Tecnologias Utilizadas

- **HTML5**: Para a estrutura do conteúdo.
- **CSS3**: Para estilos e layout, com ênfase em Flexbox.
- **JavaScript** (opcional): Poderia ser integrado para interações mais avançadas.

## Como Executar o Projeto

1. Clone este repositório em sua máquina local:
   ```bash
   git clone https://github.com/dev-miriambatista/AluraPlay.git
