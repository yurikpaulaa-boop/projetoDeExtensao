Projeto de Extensão

Página web simples em HTML que apresenta o conteúdo do Projeto de Extensão, com um título principal, um parágrafo de descrição e uma seção adicional de teste.

Começando

Essas instruções vão te garantir uma cópia do projeto funcionando na sua máquina local para fins de desenvolvimento e testes. Veja a seção Implantação para notas sobre como publicar o projeto em um sistema ao vivo.

Pré-requisitos

Para visualizar e editar o projeto, você só precisa de:

Um navegador web moderno (Chrome, Firefox, Edge, Safari)
Um editor de texto ou de código (por exemplo, VS Code)
Opcional: Git para clonar o repositório
Instalação

Passo a passo para colocar o ambiente em funcionamento:

Clone o repositório:

bash
git clone https://github.com/seu-usuario/projeto-de-extensao.git

Entre na pasta do projeto:

bash
cd projeto-de-extensao

Abra o arquivo index.html no navegador (dando dois cliques sobre ele ou pelo terminal):

bash
# Linux
xdg-open index.html

# macOS
open index.html

# Windows
start index.html

Pronto! A página será exibida no navegador com o título Projeto de Extensão e as seções de conteúdo.


Por ser uma página estática, não há testes automatizados configurados. A verificação pode ser feita manualmente.

Testes de validação do HTML

Verifique se a estrutura do documento está correta e sem erros de sintaxe, usando o W3C Markup Validation Service.

Envie o conteúdo do index.html no validador e confira se não há erros.
Testes de compatibilidade

Abra a página em diferentes navegadores e tamanhos de tela (desktop, tablet e celular) para garantir que o conteúdo seja exibido corretamente. As ferramentas de desenvolvedor do navegador (F12) permitem simular dispositivos móveis.

Implantação

Por ser um site estático, o projeto pode ser publicado gratuitamente em serviços como:

GitHub Pages
Netlify
Vercel

Exemplo com GitHub Pages: envie o código para um repositório, acesse Settings → Pages, selecione a branch main e a pasta raiz (/), e salve. O site ficará disponível em https://seu-usuario.github.io/projeto-de-extensao/.

Construído com
HTML5 - Linguagem de marcação utilizada
Contribuição


Versionamento

Usamos o SemVer para versionamento. Para as versões disponíveis, veja as tags neste repositório.

Autores
Yuri Kauan- Trabalho inicial - yurikpaulaa-boop


