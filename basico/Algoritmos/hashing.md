# Hashing

## O que é hashing?

Hashing é uma técnica usada para guardar e recuperar informação o mais rápido possível. Ele é usado para realizar pesquisas ideais e na implementação de **symbol tables**.

## Por que hashing?

Torna possível que operações de:

- insert
- delete
- search

ocorram em **O(1)**. Lembrando que **worst case** do hashing é **O(n)**, mas o **average case** é **O(1)**

## Hash Table

É uma estrutura de dado que guarda as chaves e seus valores associados, ela usa uma função hash para mapear as chaves para seus respectivos valores. A conveção geral é que usamos uma hash table quando o número de chaves atualmente guardado é relativamente menor que o número de chaves possíveis.

## HashTable ADT

As operações comuns para **hash table** são:

- create: cria um novo hash table
- search: pesquisa uma dada chave no hash table
- insert: insere uma nova chave no hash table
- delete: apaga uma chave no hash table
- deleteHashTable: apaga o hash table
