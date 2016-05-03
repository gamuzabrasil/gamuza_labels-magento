<h1>Módulo de Etiquetas</h1>

**Compatível com a plataforma Magento CE versão 1.6 a 1.9**

[Necessário módulo Gamuza_Utils](https://github.com/gamuzabrasil/gamuza_utils-magento)

Junto com o nosso módulo de fretes, você pode fazer ainda mais.

Imprimir as etiquetas para os seus envios de uma maneira simples e descomplicada. Gerar os relatórios dos Correios em poucos cliques. Tudo funcionando nos padrões dos Correios.

<img src="https://dl.dropboxusercontent.com/s/fu4gj05mct7hqdl/gamuza-etiquetas-box.png" alt="" title="Gamuza Etiquetas - Magento - Box" />

<h2>Instalação</h2>

*Atenção! Sempre faça um backup antes de realizar qualquer modificação! Sempre utilize o módulo em ambiente de testes primeiro!"*

**Instalar usando o modgit:**

    $ cd /path/to/magento
    $ modgit init
    $ modgit add gamuza_labels https://github.com/gamuzabrasil/gamuza_labels-magento.git

**Instalação manual dos arquivos**

Baixe a ultima versão aqui do pacote Gamuza_Labels-xxx.tbz2 e descompacte o arquivo baixado para dentro do diretório principal do Magento

Limpe todos os caches em Sistema -> Gerenciamento de Cache

<h2>Conhecendo o módulo</h2>

**1 - Ajustes padrões**

Neste painel você pode alterar o logotipo da empresa que será impressa na etiqueta,
ou adicionar uma URL customizada para a geração das etiquetas, etc ...

<img src="https://dl.dropboxusercontent.com/s/50edjhj021rhiu1/gamuza-etiquetas-config-admin-padrao.png" alt="" title="Gamuza Etiquetas - Magento - Configuração no Painel Administrativo - Ajustes padrões" />

**2 - Ajustes para transportadoras**

Você precisa preencher as informações obtidas através dos Correios:

    Número do Contrato,
    Número do Cartão,
    Código da Unidade
    Unidade de Postagem

<img src="https://dl.dropboxusercontent.com/s/o2wsxcshww3ywvx/gamuza-etiquetas-config-admin-transportadoras.png" alt="" title="Gamuza Etiquetas - Magento - Configuração no Painel Administrativo - Ajustes para Transportadoras" />

**3 - Gerenciando intervalos de etiquetas**

Nesse painel você configura os ranges que foram obtidos através dos Correios.

No final de cada item cadastrado, selecione a opção **Gerar objetos** para criar os rastreios (objetos de etiquetas) que serão utilizados pelos pedidos.

**OBS: Os rastreios já são gerados com o código verificador.**

<img src="https://dl.dropbox.com/s/1z76jz169hwrw6k/gamuza-etiquetas-gerando-rastreios.png" alt="" title="Gamuza - Magento - Gerando rastreios" />

**4 - Gerenciando objetos de etiquetas**

Neste painel conseguimos alterar manualmente cada rastreio gerado automaticamente pelo sistema.

<img src="https://dl.dropboxusercontent.com/s/7z13g1oos2sh306/gamuza-etiquetas-gerenciando-objetos-etiquetas.png" alt="" title="Gamuza Etiquetas - Magento - Gerenciando objetos de etiquetas" />

**5 - Gerenciando relatórios de etiquetas**

Para imprimir os relatórios, basta selecionar na mesma tela (Gamuza - Gerenciar Relatórios de Etiquetas)
a opção **Gerar Relatório** e enviar o arquivo para impressora ou Gerar um PDF.

<img src="https://dl.dropboxusercontent.com/s/ltzunpay9zyf2c3/gamuza-etiquetas-gerenciando-relatorios-etiquetas.png" alt="" title="Gamuza Etiquetas - Magento - Gerenciando relatórios de etiquetas" />

<h2>Geração de Etiquetas</h2>

Para gerar a etiqueta há 2 formas:

Dentro do pedido no painel administrativo, já faturado, clique no botão **etiqueta**
para utilizar um rastreio gerado anteriormente no painel de etiquetas.

OU:

Acesse: Gamuza -> Gerenciar Relatórios de Etiquetas, marque um pedido
e escolha a opção **Gerar Entregas** (as entregas dos pedidos serão criadas
com os códigos de rastreio já inseridos).
