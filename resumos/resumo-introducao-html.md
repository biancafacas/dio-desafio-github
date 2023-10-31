# Primeiros passos com HTML

1. [Entendendo Comunicação Client X Server](#entendendo-comunicação-client-x-server)
    1. [Client](#1-client)
    2. [Server](#2-server)
    3. [Linguagens de Programação](#3-linguagens-de-programação)
2. [Introdução ao HTML na Prática](#introdução-ao-html-na-prática)
    1. [Atributos](#21-atributos)
    2. [Texto](#22-texto)
    3. [Listas](#23-listas)
    4. [Links](#24-links)
  
<br>

## Entendendo Comunicação Client X Server:

<br>

### 1.1. Client

----

#### Conceitos

- **Cliente (client)** - Dispositivo que está consumindo a informação (na internet)

- **Servidor (server)** - Serve informações para os clientes

- **Cache** - Armazenamento das informações no client. Evita tráfego desnecessário

- Design Responsivo/Responsividade - Leva em conta os diferentes dispositivos sendo utilizados do lado do client

#### Navegadores:

- Softwares que interpretam os arquivos (e.g. HTML, CSS, Javascript) recebidos do servidor

- Suporte de tags HTML pode variar entre navegadores ([consultar aqui](https://www.w3schools.com/tags/ref_html_browsersupport.asp))

#### Aplicações Web:

- **Conceito:** Soluções criadas que possuem a internet como meio de comunicação entre Client x Server, não sendo necessário a sua instalação

- **Exemplos**:

    >- **Banco de dados (databases)** - Servidores podem se conectar com databases para buscar dados (e.g. informações de login) 

    >- **Aplicativos** - Aplicativos, quando acessados diretamente pelo navegador (e.g. *Youtube, Spotify, Facebook*), se conectam diretamente à internet

<br />

### 1.2. Server

----

#### Conceitos

- **Servidor** - Podem utilizar conexão da internet ou ser um servidor local; Existem diferentes tipos de servidores

    <details>
    <summary>Exemplos de tipos de servidores</summary>

    >- **Servidor de Arquivos** - Centraliza o armazenamento de arquivos
    >- **Servidor de Segurança** (Firewall)
    >- **Servidor de Streaming**
    >- **Servidor de E-mail**
    >- **Servidor Web**

    </details><br>
- **Softwares** - Programas que são instalados no servidor e desempenham algum determinado papel (e.g. Sistemas Operacionais, Servidores Web). Processam requisições HTTP

- **Proxy** - Tipo de servidor que intermedia a conexão entre o client e a internet

- **DNS (Domain Name Service)** - Servidor que detém uma lista de nomes e IPs

- **Web Server** - Pode ser contratado ou instalado por conta própria

- **Conexão FTP (File Transfer Protocol)** - Conexão para envio exclusivo de arquivos. Um provedor de hospedagem fornece credenciais FTP ao servidor

<br />

### 1.3. Linguagens de Programação

----

<br />

- **Linguagem de programação** - Uma linguagem escrita e formal que especifica um conjunto de instruções e regras usadas para criar um software (e.g. Javascript, Python, C#)

- **Linguagem Server-Side** - Linguagens que são executadas no servidor (e.g. PHP, Ruby, Java)

- **Linguagem Client-Side** - Linguagens que são executadas no cliente (i.e. HTML, CSS, Javascript)

- **HTML** - Não é uma linguagem de programação mas sim um arquivo de marcação; Textos delimitados por nomes que o navegador consegue interpretar

<br>

## 2. Introdução ao HTML na Prática - Tags

- [Site de referências](https://www.w3schools.com/tags/default.asp)

### 2.1. Atributos

----

<br>

- id

```html
<strong id="titulo">texto</strong>
```

<br>

- style (CSS)

```css
<strong style="color blue"></strong>
```

<br>

- class (CSS)

```css
<strong class="titulo-principal"></strong>
```

<br>

- type (atributos específicos do input)

```html
<input type="text" />
<input type="number" />
<input type="color" />
```

<br>

- img

```html
<img width="300" src="https://www.havahart.com/media/wysiwyg/hh/cms/lc/rats/hh-animals-rat-1.png" />
```
<br>

### 2.2. Texto

----
<br>

- títulos/subtítulos

```html
<h1>Heading 1<h1/>
<h2>Heading 2<h2/>
<h3>Heading 3<h3/>
...
<hn>Heading N<hn/>
```

<br>

- parágrafos

```html
<p>
Texto blablabla
<p/>
```

<br>

- citações

```html
<blockquote>
    citação
<blockquote/>
```

<br>

### 2.3. Listas

----

<br>

- ordenadas

```html
<ol>
    <li>item 1</li>
    <li>item 2</li>
    <li>item 3</li>
</ol>
```

<br>

- não ordenadas

```html
<ul>
    <li>item 1</li>
    <li>item 2</li>
    <li>item 3</li>
</ul>
```

<br>

### 2.4. Links

----

<br>

- "Âncora"

```html
<a href="https://www.youtube.com/watch?v=9Qmwsg2pyEc">trampoline</a>

```

<br>

- para abrir em outra aba

```html
<a href="https://www.youtube.com/watch?v=9Qmwsg2pyEc" target="blank">trampoline</a>
```

<br>

- para abrir na mesma aba (redirecionar)

```html
<a href="https://www.youtube.com/watch?v=9Qmwsg2pyEc" target="self">trampoline</a>
```

<br>

- para mudar o texto que aparece quando passa o mouse pelo hyperlink (*tooltip*)

```html
<a href="https://www.youtube.com/watch?v=9Qmwsg2pyEc" title="jump!!!">trampoline</a>

```
