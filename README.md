<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Estudo Sobre HTML</title>
</head>

<body>
    <h1 id="inicio"><u>HTML Básico</u></h1>
    <hr />
    <h2>Indice</h2>
    <ul>
        <li><a href="#cliente">Cliente-servidor</li></a>
        <li><a href="#estrutura">Estrutura do Html</a></li>
        <li><a href="#Lista">Lista ordenadas e não ordenadas</li></a>
        <li><a href="#Links">Links de referências</li></a>
    </ul>
<h2><u>Cliente-servidor</h2></u>
<small><a href="#inicio">voltar</a></small>
<p><strong>Cliente-servidor</strong><sup>1</sup> são conceitos fundamentais na comunicação de redes e internet. No modelo Cliente-Servidor, a interação ocorre através de uma troca de mensagens. O cliente envia uma requisição ao servidor, especificando o recurso ou serviço desejado. O servidor recebe, processa e retorna uma resposta com os dados solicitados ou confirmação do serviço.
</p>
<strong>Modelo Cliente-Servidor</strong>
<ul>
    <li><strong>Cliente:</strong> <i><mark>Um dispositivo (computador, smartphone, tablet) ou software que solicita recursos ou serviços a um servidor.</mark></i></li>
    <li><strong>Servidor:</strong> <i><mark>Um dispositivo ou software que fornece recursos ou serviços aos clientes.</mark></i></li>
</ul>
    <p> Essa comunicação é regulamentada por protocolos de rede, como:</p>

<strong>Protocolos de Comunicação</strong>
<ul>
<li>HTTP (Hypertext Transfer Protocol) - sites e aplicativos web.</li>
<li>SMTP (Simple Mail Transfer Protocol) - serviços de e-mail</li>
<li>FTP (File Transfer Protocol) - transferência de arquivos.</li>
<li>SSH (Secure Shell) - acesso remoto seguro</li>
</ul>
<h2 id="estrutura"><u>Estrutura do Html</h2></u>
<small><a href="#inicio">voltar</a></small>
    <p>O HTML não é uma linguagem de programacao; é uma linguagem de marcação utilizada para criar páginas web. Sua estrutura básica inclui:</p>
    <h3><strong>Elementos principais</strong></h3>
    <dl>
        <dt>
            <b>!DOCTYPE html</b>
        </dt>
        <dd>
            A primeira tag presente em nosso código é necessária para indicar aos navegadores que o documento presente se trata de um arquivo HTML. Essa lógica precisa estar sempre presente no começo dos arquivos
        </dd> 
        <dt>
            <b>HTML</b>
        </dt>
            <dd>
                Essa tag representa o início dos elementos de uma página. Todos os demais elementos precisam ser descendentes dessa tag, seja diretamente ou indiretamente

            </dd>
        <dt>
            <b>HEAD </b>
        </dt>
            <dd>
                A tag de cabeçalho <b>(Head)</b> contém o conteúdo que é visualizado pela máquina, tal como os scripts, links externos e metadados. Não é um elemento visual.
            </dd>
        
        <dt>
            <b>BODY</b>
        </dt>
            <dd>
                É uma das tags mais populares e importantes do HTML, dentro dela adicionamos os conteúdos que podem ser visualizados pelo usuário final. É uma tag única e pode ser considerada a tag pai de todos os elementos de conteúdo
            </dd>
    </dl>
    
    <h2 id="Lista">Lista ordenadas e não ordenadas</h2>
    <small><a href="#inicio">voltar</a></small>
    
    <p>Utilizamos as tags &lt;nome_da_tag&gt; e termina com &lt;/nome_da_tag&gt;. Existem tipos de listas no HTML, sendo a ordenada, não ordenada. As duas primeiras utilizam as tags &lt;ol&gt; e &lt;ul&gt;, respectivamente, e também usam a tag &lt;li&gt; para descrever cada elemento da lista. <mark>Lista ordenada</mark> tem por padrão sequencia por numeros. Porem podemos mudar o tipo dentro da tag &lt;ol&gt;. Utilizando o atributo <b>type=""</b> para escolher o tipo de sequencia que queremos. (a, A, I, i). <mark>Lista não ordenada</mark> tem por padrão a separação por ponto </p>
    <ol>
        <li>lista ordenada</li>
        <li>lista ordenada</li>
        <li>lista ordenada</li>
    </ol>
    <ul>
        <li>lista nao ordenada</li>
        <li>lista nao ordenada</li>
    </ul>
    <ol type="A">
        <li>lista ordenada utilizando &lt;ol type="A"&gt;</li>
        <li>lista ordenada</li>
        <li>lista ordenada</li>
    </ol>
    
    <h2 id="Links">Links de referências</h2>
    <small><a href="#inicio">voltar</a></small>
    <ol>
        <li><a href="https://www.controle.net/faq/cliente-servidor-uma-estrutura-para-a-computacao-centralizada" title="client-servidor" target="_blank">Cliente-Servidor</a></li>
        <li><a href="https://www.w3schools.com/html/default.asp" title="Html" target="_blank">Estrutura do HTML</a></li>
        <li><a href="https://blog.betrybe.com/html/input-html/estrutura-html-pronta-estrutura-basica-de-uma-pagina-html/" title="Lista-ordenada-e-nao-ordenada" target="_blank">Lista ordenadas e não ordenadas</a></li>
    </ol>   
</body>
</html>
