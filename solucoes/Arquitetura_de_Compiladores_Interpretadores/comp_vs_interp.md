# Compilador vs Interpretador
## Q1
  Basicamente, um compilador é um programa (ou um conjunto deles) como qualquer outro, porém seu objetivo principal é o de traduzir todas as suas linhas de código para outra linguagem – normalmente, uma de alto nível para outra de baixo nível. 
  Um interpretador também é um programa, mas, ao contrário do compilador, ele não converte o código todo para linguagem de máquina de uma vez. Ele executa diretamente cada instrução, passo a passo.
  Enquanto um compilador analisa todo o código a fim de traduzi-lo de uma vez, o interpretador faz esse trabalho de conversão aos poucos, sempre que uma declaração ou função é executada, por exemplo.
  Alguns dos passos são: Análise léxica e semântica, pré-processamento, análise e otimização de código e, ao fim, geração do produto final. Porém, uma vez compilado, ele não precisará fazer mais essa tradução – a menos que o código precise ser alterado.

## Q2
  O módulo py_compile fornece uma função para gerar um arquivo de bytecode a partir de um arquivo fonte, e outra função usada quando o arquivo fonte do módulo é chamado como um script.
  https://docs.python.org/pt-br/3.7/library/py_compile.html
