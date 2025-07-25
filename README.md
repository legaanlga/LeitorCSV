# LeitorCSV
Leitor/Formatador de arquivos .CSV

Esse projeto foi desenvolvido visando a melhoria visual de arquivos .csv gerados por ihm's e clp's industriais. Seu intuito é gerar uma representação harmoniosa dos dados presentes em um arquivo .csv sem invalidar o arquivo original. Dentre seus objetivos, além de algo mais simples e bonito ao olhar analitico, investi em filtros, modulos, acessibilidade, proteção de dados, validações licenciadas, conversões de dados, layout aprimorado, importação e exportação entre outras varias ferramentas.

<img width="1332" height="242" alt="image" src="https://github.com/user-attachments/assets/05749985-39bf-4cba-9789-18c1504e06da" />
Um exemplo real de um arquivo .csv com dados reais encontrados.

<img width="1361" height="712" alt="image" src="https://github.com/user-attachments/assets/f61b2915-39c4-4df9-8165-2ce269fa3f3f" />
Um exemplo real do mesmo arquivo na imagem anterior ao ser importado no aplicativo.

O objetivo desde documento é relatar as funções presentes neste projeto, assim como suas possiveis melhorias e implementações futuras.

Do começo então,

Logo no inicio iremos nos deparar com um sistema de validação de licença, que já tem um sistema de validação funcional e operando a todo vapor, com inclusão de validações "offline" e implementação de melhorias contra clones e chaves falsa. Sistema de chaves de acesso temporario, permanente, rastreabilidade e registro de acesso.

<img width="467" height="262" alt="image" src="https://github.com/user-attachments/assets/b329133a-5c15-4986-b2e5-62a84a26bbb1" />

Imagem referente a primeira camada do sistema de licença.

Ainda nesse mesmo sistema, temos um recurso de tentativas invalidas, o que gera bloqueio do aplicativo por tentativa de invasão indevida, com liberação apenas pelo controlador administrador.

<img width="410" height="230" alt="image" src="https://github.com/user-attachments/assets/1c147570-b7ed-41cf-801c-25f5b67ebfa2" />

Imagem referente a aba de login administrativo

Ao acessarmos a parte inicial do aplicativo, temos acesso a importação dos arquivos .csv, onde já tem um sistema de validação da extensão do arquivo.

<img width="465" height="285" alt="image" src="https://github.com/user-attachments/assets/4fca6d2f-5937-498b-8050-b4bdcea32d7a" />

Agora que acessamos definitivamente a tabela da forma que queriamos, vou apresentar-lhes as ferramentes presentes no mesmo.

Primeira ferramenta, um menu suspenso para trabalharmos com o projeto todo em possiveis dispositivos touch.
<img width="244" height="108" alt="image" src="https://github.com/user-attachments/assets/c77b00a1-4fc4-4bbc-8803-6ea3fe780a9c" />

Nele podemos observar 4 figuras, sendo a primeira o botão de importação, para importarmos um novo .csv, o segundo um botão de filtro (que pode ser acessados através de atalhos),

<img width="511" height="501" alt="image" src="https://github.com/user-attachments/assets/01184830-845a-4bd9-a94e-bd48a83318b2" />

onde o mesmo tem diversos tipos de dados para serem filtrados.

A terceira figura é um botão de fechamento de todo o aplicativo, e por fim, o ultimo botão é um botão para exportar todos o dados em pdf! Tal pdf já vem com campos de assinatura em todas as pagina e logos escolhidas pelo usuario.

<img width="994" height="286" alt="image" src="https://github.com/user-attachments/assets/c6aeb627-9a85-4ff6-8aad-430e16063eb8" />

Um ultimo ponto de extrema importancia é o grafico que pode ser gerado com algumas informações especificas, onde podem ser alteradas de acordo com o cliente e a solicitação:
<img width="706" height="294" alt="image" src="https://github.com/user-attachments/assets/cb780693-1e78-44a2-b287-d1a73e1f694d" />

Curtiu a breve explicação do projeto? Caso queira mais informações basta entrar em contato no meu e-mail: leonardodenislga@gmail.com

Nota: todas as informações podems ser editadas e trabalhadas da maneira que for necessaria.
