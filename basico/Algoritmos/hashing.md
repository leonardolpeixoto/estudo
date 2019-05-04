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
