# Controle de versão:

|Data         |Versão|Descrição                              |Autor               |
|---        |---   |---                                    |---                 |
|21/03/2018 |0.1   |Abertura do Documento                  | Guilherme Aguiar   |
|27/03/2018 |0.2   |Adição do Tópico 1                     | Adrielly Rodrigues |
|27/03/2018 |0.3   |Adição do tópico 2 com imagens         | Victor             |
|03/04/2018 |0.4   |Adição do tópico 6                     | Guilherme Aguiar   |
|03/04/2018 |0.5   |Adição do tópico 7                     | Guilherme Aguiar   |
|11/04/2018 |0.6   |Adição do tópico 4 | Guilherme Aguiar |
|11/04/2018 |0.7   |Adição do tópico 3                     | Caio César Beleza   |
|11/04/2018 |0.8   |Adição do subtópico 1.5 e correção no tópico 2 | Guilherme Aguiar |
|15/04/2018 |0.9   |Adição do tópico 5 | João Vitor |
|15/04/2018 |1.1   |Adição de mais especificações do tópico 2| Victor |
|15/04/2018 |1.2   |Mudança do nome do projeto| Victor |
|15/04/2018 |1.3   |Corrigir erro do último tópico | Victor  |
|16/04/2018 |1.4   |Corrigir erros ortográficos | João Vitor  |


# Sumário
1. [Introdução](#1)
  * 1.1 [Finalidade](#1.1)
  * 1.2 [Escopo](#1.2)
  * 1.3 [Definições, acrônimos e abreviações](#1.3)
  * 1.4 [Referências](#1.4)
  * 1.5 [Visão Geral](#1.5)
2. [Representação da Arquitetura](#2)
3. [Restrições e Metas de Arquitetura](#3)
  * 3.1 [Metas](#3.1)
  * 3.2 [Restrições](#3.2)
4. [Visão de Casos de Uso](#4)
  * 4.1 [Atores](#4.1)
  * 4.2 [Diagrama de Casos de Uso](#4.2)
  * 4.3 [Descrição dos Casos de Uso](#4.3)
5. [Visão Lógica](#5)
  * 5.1 [Visão Geral](#5.1)
  * 5.2 [Visão de Implantação](#5.2)
  * 5.3 [Pacotes de Design Significativos do Ponto de Vista da Arquitetura](#5.3)  
6. [Desempenho](#6)
7. [Qualidade](#7)

## 1.  Introdução

### 1.1. Finalidade

Neste documento será apresentada a visão arquitetônica sobre a aplicação webapp de Gerencia mais- GM, com a finalidade de elucidar, explicar e formalizar como será modelada a arquitetura do software, tendo como base diferentes características do projeto para justificar as decisões tomadas pelos desenvolvedores.

### 1.2. Escopo

Este documento tem como objetivo documentar a arquitetura a ser implementada no software, guiando os desenvolvedores na construção do projeto que auxilia o gerenciamento de servidores, recursos médicos e recursos físicos do Hospital Regional do Gama - HRG.