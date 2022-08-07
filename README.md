# Minion-Flasher


Projekt pozostáva z plošného spoja, ktorý pripomína mimoňa (Dave), ktorému sa rozsvietia oči po dotknutí sa oblasti brucha, respektíve vytvorením vodivej cesty medzi kladným pólom batérie a vstupom mikroprocesora. To je predpokladom správnej funkčnosti detekcie dotyku. Napájaný je jednou gombíkovou batériou, ktorá môže byť formátu CR2032, CR2025 alebo CR2016. Projekt by mal s jednou batériou vydržať niekoľko mesiacov v pohotovostnom režime. Odporúča sa použiť batériu potiahnutú vrstvou horkej príchute, aby odradila od prehltnutia. Rezistory sú v puzdre 2512, a teda o veľkosti 3,2mm x 1,6mm. LED je v cezdierovom puzdre s roztečou 2.54mm. Mikrokontrolér je v puzdre SOIC-14, a teda o veľkosti 8.95mm × 6.0mm.
Pôvodná verzia má rezistory v puzdre 1206, a teda o veľkosti 3,2mm x 1,6mm.

Projekt sa odporúča, vzhľadom na rozmery použitých súčiastok, dať osádzať trpezlivejším deťom, ak nemajú predchádzajúce skúsenosti, alebo deťom, ktoré už majú základné skúsenosti. 


# Programovanie dosky
Doska sa má osádzať mikrokontrolérom ATtiny3224/ATtiny204, ktorý je možné programovať v jazyku Wiring, respektíve prostredí Arduino. Programovanie je možné priamo uchytením mikroprocesora do kliešťového adaptéra alebo použitím plôch na to určených na zadnej strane dosky plošného spoja.

# Alternatívne súčiastky

## Mikrokontróler
Doska je kompatibilná s inými typmi mikrokontrolérov, napríklad z rodiny Microchip PIC, avšak kvôli kompatibilite s prostredím Arduino sa odporúča použitie mikrokontrolérov z rodiny Microchip tinyAVR.

## Luminiscenčné diódy
Doska je kompatibilná s viacerými puzdrami LED, avšak odporúča sa použitie s roztečou 2.54mm a antiparalelným zapojením. Aby bolo možné programovo meniť farbu očí.
