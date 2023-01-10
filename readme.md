![SweetAlert2](https://sweetalert2.github.io/images/SweetAlert2.png)

## Ferramenta que vai te ajudar a criar facilmente Alertas Personalizados

## **Exemplo :**

![exemplo1](https://i.imgur.com/8eyClNC.jpg)
![exemplo2](https://i.imgur.com/ab9gxnm.jpg)

# **Instalação :**

## **1º Forma** : **_Utilizando CDN_**

### **Link da CDN:**

```js

 https://cdn.jsdelivr.net/npm/sweetalert2@11.6.16/dist/sweetalert2.all.min.js

```

### Dentro do Body

```html
<body>
  <script src="https://cdn.jsdelivr.net/npm/sweetalert2@11.6.16/dist/sweetalert2.all.min.js"></script>
</body>
```

### Ou dentro do Head

```html
<head>
  <meta charset="UTF-8" />
  <meta http-equiv="X-UA-Compatible" content="IE=edge" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Document</title>
  <link rel="stylesheet" href="./style.css" />
  <script src="https://cdn.jsdelivr.net/npm/sweetalert2@11.6.16/dist/sweetalert2.all.min.js"></script>
</head>
```

## **2º Forma:** **_Criando um Arquivo Javascript_**

### **Link do Arquivo para ser copiado :**

```js
https://cdn.jsdelivr.net/npm/sweetalert2@11
```

#### **Entre nesse Link e aperte Ctrl + A e depois Ctrl + C em tudo e depois crie um arquivo com o nome que desejar, exemplo:**

![imagemJs](https://i.imgur.com/k4fMZfM.png)

#### **Depois é só importar dentro do Body, igual no Exemplo abaixo :**

```html
<body>
  <script src="./sweetalert.js"></script>
</body>
```

# **Utilização :**

### **Codigo :**

```js
function alerta(type, title, mensagem) {
  Swal.fire({
    icon: type,
    title: title,
    text: mensagem,
    showConfirmButton: false,
    timer: 1500,
    iconColor: "#fff",
    color: "#fff",
    background: "#FA01E8 ",
  });
}

alerta("success", "ok", "Alerta funcionou");
```

### **Explicando propriedades :**

```js

    icon: "O TIPO DE ICONE QUE SERÁ APRESENTADO",
    title: "O TITULO DA MENSAGEM QUE SERÁ APRESENTADA",
    text: "A MENSAGEM QUE SERÁ APRESENTADA",
    showConfirmButton: "Define se um Butão de fechar menu ira ser exibido, podendo ser utilizado apenas false e true",
    iconColor: "DEFINE A COR DO ICONE",
    color: "DEFINO A COR DO TEXTO NO MODAL",
    background: "DEFINE A COR DE FUNDO DO MODAL",

```

### **Se quiser saber mais propriedades e o que mais pode ser feito utilizando o Sweetalert2, só clicar no Link:**

# [sweetart2](https://sweetalert2.github.io/)