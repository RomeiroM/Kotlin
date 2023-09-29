# Primeiro App DIO
Esse projeto tem o objetivo de realizar um desafio para os alunos do curso de Android na DIO.

Repositório Base: [igorbag](https://github.com/digitalinnovationone/meu-primeiro-app-dio/tree/main)

### O que foi pedido no desafio:

~~~kotlin
 //O desafio sera criar uma valor dentro do string.xml
 // E trocar o texto do xml e tornar internacional (Ingles, Espanhol, etc...)
~~~

### Alterações que foram realizadas para concluir o desafio:

#### ➡️Alterações na /res/values/strings.xml

##### ✅ Para criar um valor dentro da string:

- [Antes](https://github.com/digitalinnovationone/meu-primeiro-app-dio/blob/main/app/src/main/res/values/strings.xml)

~~~~kotlin
<resources>
    <string name="app_name">MeuPrimeiroAppDio</string>
</resources>
~~~~

- [Depois](/DesafiosDIO/meu-primeiro-app-dio/app/src/main/res/values/strings.xml)
~~~~kotlin
<resources>
    <string name="app_name">Internacionalização do App</string>
    <string name="bem_vindo">Bem-Vindo!</string>
</resources>
~~~~

#### ➡️Trocar o texto do xml e tornar internacional (Inglês e Espanhol)

- No [projeto base](https://github.com/digitalinnovationone/meu-primeiro-app-dio/tree/main/app/src/main/res/values) só havia a string.xml em português(br).

- Depois foi implementado as versões em Inglês e Espanhol no App do desafio. 

    - [Padrão](/DesafiosDIO/meu-primeiro-app-dio/app/src/main/res/values/strings.xml)
    ~~~~kotlin
    <resources>
        <string name="bem_vindo">Bem-Vindo!</string>
    </resources>
    ~~~~

    - [Inglês(en)](/DesafiosDIO/meu-primeiro-app-dio/app/src/main/res/values-en/strings.xml)
    ~~~~kotlin
        <string name="bem_vindo">Welcome!</string>
    ~~~~

    - [Espanhol(es)](/DesafiosDIO/meu-primeiro-app-dio/app/src/main/res/values-es/strings.xml)
    ~~~~kotlin
    <string name="bem_vindo">Bienvenido!</string>
    ~~~~
    
