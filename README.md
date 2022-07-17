# Buffer Overflow - Scripts
Scripts para efectuar la fase de fuzzing y explotación de Buffer Overflow tanto en Windows como en Linux. La base de fuzzer.py y exploit.py son de la room [Buffer Overflow Prep](https://tryhackme.com/room/bufferoverflowprep) de TryHackMe modificados para funcionar en cualquier caso.

Para exploit_linux.py, desarrollé el script de manera tal que es capaz de correr en sistemas Unix tanto de 32 como de 64 bits. La explicación sobre este y cómo ejecutarlo está en la guía para [Brainpan 1]() de mi blog. Únicamente es eficaz contra objetivos dentro de la misma máquina y que reciban una entrada de datos, es decir, no se puede ejecutar de forma remota, ya que al correrlo devuelve una bash como el usuario que inició el servicio en primer lugar.
