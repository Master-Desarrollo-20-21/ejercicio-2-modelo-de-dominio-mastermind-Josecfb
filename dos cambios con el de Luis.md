# Dos cambios

Humildemente desde mi posición de aprendiz, es posible que esté equivocado, pero propongo dos cambios en el diagrama de clases de Luis:
La relación entre BreakerPlayer y ProposedCombination sería de agregación de 0 a 10, creo que es por un error tipográfico, es decir ``BreakerPlayer o-- "0..10"`` ProposedCombinationun BreakerPlayer puede tener de 0 a 10 combinaciones propuestas
También crearía una relación entre MakerPlayer y Result de agregación de 0 a 10, es decir ``MakerPlayer o-- "0..10"`` Result por el mismo motivo que antes un MakerPlayer puede tener de 0 a 10 resultados.