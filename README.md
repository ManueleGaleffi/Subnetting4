# Subnetting4

# Obbiettivo

- la rete principale è la 172.130.20.0/24

- si vuole fare subnetting in modo da ottenere 4 sottoreti della stessa dimensione

- 1 router con 4 porte

- 8 PC

- 4 switch

- Ciascuna sottorete ha 1 switch e 2 PC, il router permette la comunicazione tra le 4 sottoreti

# Soluzione
Per realizzare il subnetting di 4 sottoreti delle stessa dimensione utillizziamo come subnetmask 255.255.255.192 in modo da creare 4 sottoreti grandi 64.

Quindi assegnamo a ogni porta del router un host della sottorete e subnetmask 255.255.255.192.

Succesivamente completiamo la configurazione di tutti i pc con un host libero della sottorete e sempre la stessa subnetmask.

Infine completiamo assegando ai pc come default gateway a ognuno l'indirizzo IP della porta del router alla quale sono collegati.
