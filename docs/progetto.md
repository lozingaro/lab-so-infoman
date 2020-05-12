# Descrizione delle componenti del sistema



## I sistemi Peer-to-Peer (P2P)



## Pubblicare e scrivere



## Canali pubblici e messaggi privati



### Messaggi cifrati

Alice e Bob vogliono comunicare - in privato - scambiandosi messaggi l'uno con l'altra, per farlo in sicurezza hanno deciso di usare un protocollo di crittografia asimmetrica:

![crittografia asimmetrica](https://upload.wikimedia.org/wikipedia/commons/thumb/e/e6/Crittografia_asimmetrica_schema.png/310px-Crittografia_asimmetrica_schema.png)

1. Bob cripta il messaggio con la chiave pubblica di Alice;
2. Alice decripta il messaggio di Bob con la sua chiave Privata.

Ovviamente, nel caso in cui sia Alice a voler inviare un messaggio a Bob, ella eseguirà gli stessi passaggi di Bob, il quale invece farà come aveva fatto Alice.

### Messaggi firmati


