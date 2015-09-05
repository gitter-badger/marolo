Marolo
======

[![Join the chat at https://gitter.im/grupythonUFLA/marolo](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/grupythonUFLA/marolo?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Projeto inicialmente desenvolvido pelo Grupython UFLA, com intuito de
agregar conhecimento aos participantes do grupo e ajudar membros de
um grupo de estudo da universidade, mas com o tempo acabou sendo abandonado.

Hoje, apenas uma ferrramenta de estudo e aprimoramento de conhecimento,
aberta a contribuições. O intuito da continuação do projeto de forma aberta
é servir como referências a iniciantes  em web2py assim como um ótimo
ponto de aprendizado para quem está começando ou está querendo se aprimorar
neste framework.

O que deve conter no projeto
----------------------------

- Home

  - Noticias
  - Divulgação de atividades

- O que é o Projeto

  - Descrição do Projeto

- Membros

  - Fotos, descrição e contatos dos membros

- Eventos

  - informações de eventos realizados

- Contatos
  - infromação do contato com o projeto

- Deve haver uma área para apoiadores, patrocinadores e parceiro
- Área para exposição de materiais desenvolvidos com marolo


![Screenshot](static/images/screenshot.gif?raw=true)



Instalação
----------

- Baixe o repositório git
- Extraia na pasta applications do web2py
- copie o arquivo welcome/private/appconfig.ini
- (sudo) pip install -r requirements.txt
- No diretório raiz do web2py execute: `./web2py.py  -S marolo -M -R applications/marolo/populate_db.py ` para popular o banco de dados (necessário somente uma vez)
- Execute o web2py e a aplicação já estará rodando

Como contribuir
---------------

- Faça um fork do projeto(somente caso vá contribuir com código) 
- Crie uma issue ou escreva PR propondo alguma funcionalidade ou corrigindo algum erro.
- Aguarde aprovação de um dos membros responsáveis pelo projeto.
Caso seja membro do grupython da equipe do Marolo, aguarde aprovação de outro membro que não você próprio.

Dicas
-----

- Crie issues com boa descrição e quando funcionalidade envolvendo o 
- Quando funcionalidade envolver estilo e/ou design do site, tente mandar imagem.
- Quando reverter algum commit ou discordar de alguma funcionalidade, crie discussões apontando seus argumentos.
- Mudanças que podem causar o interrompimento do funcionamento correto do site devem notificar todos os membros da equipe do Marolo.
- Ao criar Issues, marque com tags relevantes. O mesmo vale para PR's.

FAQ
---

**Segui todos passos, iniciando por baixar o .zip no github,
mas a aplicação não aparece?**

**R:** Baixar o repositório compactado, traz uma nomeclatura com traços,
o que faz com que o web2py não reconheça a aplicação. Modifique o nome
da pasta para algo não contendo este caracter. Uma mudança simples é
transforma-lo em `_`.

**Um dos requisitos é a pillow, como proceder a instalação da mesma?**

**R:** A biblioteca pillow pode ser instalada através do gerenciador de
pacotes pip. Ou através de pacote específico como no Ubuntu o python-imaging.
Caso decida instalar via pip alguns problemas podem surgir.
Se utiliza Ubuntu recomendo ler
[este](http://cassiobotaro.github.io/instalando-pillow.html) tutorial,
mas independente da plataforma ao fim deste post, eu aponto links úteis.
