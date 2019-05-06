# Hashing

## O que é hashing?

Hashing é uma técnica usada para guardar e recuperar informação o mais rápido possível. Ele é usado para realizar pesquisas ideais e na implementação de **symbol tables**.

## Por que hashing?

Torna possível que operações de:

- insert
- delete
- search

ocorram em **O(1)**. Lembrando que **worst case** do hashing é **O(n)**, mas o **average case** é **O(1)**

## HasTable ADT

As operações comuns para **hash table** são:

- create: cria um novo hash table
- search: pesquisa uma dada chave no hash table
- insert: insere uma nova chave no hash table
- delete: apaga uma chave no hash table
- deleteHashTable: apaga o hash table

## Entendendo Hasing

Em termos simples nós podemos tretar **array** como um **hash table**. Para entendermos o uso do **hash table**, vamos considerar o seguinde exemplo: Dado um algoritmo para imprimir o primeiro caractere repetido se houver elementos duplicados. Vamos pensar nas possiveis soluções. A simples e bruta forma de resolver é: dado uma **string**, para cada caractere checar se é repetido ou não. O **time complexity** para esta abordagem é **O(n²)**.

Agora, vamos encontrar a melhor solução para esse problema. Uma vez que nosso objetivo é encontrar o primeiro caractere repetido.