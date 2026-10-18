All'inizio ho dichiarato le variabili, poi ho chiesto i km e la zona e la classe.
Poi ho faatto un if per capire se il veicolo era a nord se era vero, assegnato alla tariffa 0.08, se falso un’altro if per sapere se la macchina era nella zona centro, nel vero ho assegnato la tariffa a 0.075 e nel falso, che indica la zona sud, la tariffa è assegnata a 0.065
Poi ho assegnato che il pedaggio è km * tariffa.
Poi ho fatto un if per sapere le classi, èer prima ho chiesto la M2, visto che se è M1 vale la parte sopra, e nel ramo del vero ho assegnaro il pedaggio a pedaggio * 1.10.
Nel falso ho chiesto con un if la classe M3 e ho assegnato il pedaggio a pedaggio * 1.15
Fuori dal if ho chiesto se i km sono minori o uguali a 100 per capire l’impatto ambientale, nel vero ho assegnato il supplemento = 100 * 0.02 e nel falso ho asegnato il supplemento = 100 * 0.02 + (km-100) * 0.01.
Fuori dal if ho assegnato l’imponibile  = pedaggio + supplemento e ho asseganto il totale = imponibile * 1.22.
Poi ho fatto gli output con i km la zona la classe il pedaggio, il supplemento e il totale.
