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

