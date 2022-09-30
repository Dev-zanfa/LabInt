# Introduzione

In questo laboratorio analizziamo come poter stimare la velocita' di trasmissione a
livello fisico tramite misure di RTT. Esaminando 4 diverse possibili configurazioni

# Configuazione utilizzata punto 1 (2 host 1 switch in mezzo)

In questo primo caso utilizziamo una virtual machineLinux e un pc con una Live
USB Linux collegato al primo tramite un router.
Abbiamo effettuato l'accesso remoto dal primo al secondo host tramite il comando SSH. 
Per la connessione si e' utilizzato un cavo ethernet (cat 5e).
Abbiamo settato dal PC_Live Linux tramite il comando "sudo ethtool -s eth0 speed 
10 duplex full autoneg on" la velocita' di trasmissione con lo switch a 10 Mb/s.
Mentre non si puo' stabilire la reale velocita' che abbiamo tra virtual switch
e porta ethernet della virtual machine e USB, come si puo' notare dalla
figura che rappresenta la configurazione.

- disegno schema della rete 

## Risultati



- grafici