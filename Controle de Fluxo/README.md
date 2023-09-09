# Controle de fluxo e Coleções

Conteúdo desenvolvido durante o Bootcamp Santander em parceria com a [DIO](https//:www.dio.me).

## 📌Índice

- [Controle de Fluxo](https://github.com/RomeiroM/Kotlin/tree/main/Controle%20de%20Fluxo#%EF%B8%8Fcontrole-de-fluxo---control-flow)
  - [When](https://github.com/RomeiroM/Kotlin/tree/main/Controle%20de%20Fluxo#%EF%B8%8Fwhen)
  - [Loops](https://github.com/RomeiroM/Kotlin/tree/main/Controle%20de%20Fluxo#%EF%B8%8Floops)
  - [Ranges](https://github.com/RomeiroM/Kotlin/tree/main/Controle%20de%20Fluxo#%EF%B8%8Franges)
  - [Verificação de Igualdade](https://github.com/RomeiroM/Kotlin/tree/main/Controle%20de%20Fluxo#%EF%B8%8Fverifica%C3%A7%C3%A3o-de-igualdade)
  - [Expressões condicionais](https://github.com/RomeiroM/Kotlin/tree/main/Controle%20de%20Fluxo#%EF%B8%8Fexpress%C3%B5es-condicionais)
- [Coleções](https://github.com/RomeiroM/Kotlin/tree/main/Controle%20de%20Fluxo#cole%C3%A7%C3%B5es)
  - [Listas](https://github.com/RomeiroM/Kotlin/tree/main/Controle%20de%20Fluxo#listas)
  - [Conjuntos](https://github.com/RomeiroM/Kotlin/tree/main/Controle%20de%20Fluxo#conjuntos)
  - [Mapas](https://github.com/RomeiroM/Kotlin/tree/main/Controle%20de%20Fluxo#mapas)
  - [Extencion Functions (filter, map,flatmap, etc)](Controle%20de%20Fluxo#extencion-functions-filter-mapflatmap-etc)

## 🔄️Controle de Fluxo - Control Flow

### 🔄️When

Ver código:


[![Badge](https://img.shields.io/badge/Comentado-30A3DC?style=for-the-badge)]()
[![Badge](https://img.shields.io/badge/Kotlin%20Playground-9000D3?style=for-the-badge)]()

~~~kotlin
fun main(){
  cases(“Hello”)
  cases(1)
  cases(0L)
  cases(MyClass())
  cases(“hello”)
}

fun cases (obj: Any){
       When (obj) {
       1 → println(“One”)
       “Hello” → println(“Greeting”)
      is long → println(“Long”)
       !is String → println(“Não é uma String”)
       else → println(“Desconhecido”)
       }
}

class MyClass
~~~

### 🔄️Loops

Ver código:


[![Badge](https://img.shields.io/badge/Comentado-30A3DC?style=for-the-badge)]()
[![Badge](https://img.shields.io/badge/Kotlin%20Playground-9000D3?style=for-the-badge)]()

### 🔄️Ranges

Ver código:


[![Badge](https://img.shields.io/badge/Comentado-30A3DC?style=for-the-badge)]()
[![Badge](https://img.shields.io/badge/Kotlin%20Playground-9000D3?style=for-the-badge)]()

### 🔄️Verificação de Igualdade

Ver código:


[![Badge](https://img.shields.io/badge/Comentado-30A3DC?style=for-the-badge)]()
[![Badge](https://img.shields.io/badge/Kotlin%20Playground-9000D3?style=for-the-badge)]()

### 🔄️Expressões condicionais

Ver código:


[![Badge](https://img.shields.io/badge/Comentado-30A3DC?style=for-the-badge)]()
[![Badge](https://img.shields.io/badge/Kotlin%20Playground-9000D3?style=for-the-badge)]()



## 📚Coleções

### 📚Listas

Ver código:


[![Badge](https://img.shields.io/badge/Comentado-30A3DC?style=for-the-badge)]()
[![Badge](https://img.shields.io/badge/Kotlin%20Playground-9000D3?style=for-the-badge)]()

### 📚Conjuntos

Ver código:


[![Badge](https://img.shields.io/badge/Comentado-30A3DC?style=for-the-badge)]()
[![Badge](https://img.shields.io/badge/Kotlin%20Playground-9000D3?style=for-the-badge)]()

### 📚Mapas
Ver código:


[![Badge](https://img.shields.io/badge/Comentado-30A3DC?style=for-the-badge)]()
[![Badge](https://img.shields.io/badge/Kotlin%20Playground-9000D3?style=for-the-badge)]()

### 📚Extencion Functions (filter, map,flatmap, etc)

Ver código:


[![Badge](https://img.shields.io/badge/Comentado-30A3DC?style=for-the-badge)]()
[![Badge](https://img.shields.io/badge/Kotlin%20Playground-9000D3?style=for-the-badge)]()

-------
Em construção 🛠️⚒️⛏️

