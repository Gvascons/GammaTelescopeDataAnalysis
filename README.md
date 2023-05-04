# GammaTelescopeDataAnalysis

## O conjunto de dados contém dados simulados de um telescópio gamma Cherenkov localizado em terra, que registra partículas gamma de alta energia usando uma técnica de manipulação e captação de imagem. A radiação Cherenkov, emitida por partículas carregadas produzidas nos "chuveiros eletromagnéticos" iniciados pelos raios gama, é registrada no detector, permitindo a reconstrução dos parâmetros desse chuveiro. O conjunto de dados inclui padrões de fótons Cherenkov, chamados de imagens de chuveiro, que podem ser usados para discriminar estatisticamente entre raios gama primários e chuveiros hadrônicos causados por raios cósmicos.

### O conjunto de dados também inclui os parâmetros de Hillas, um conjunto de parâmetros característicos da imagem que podem ser usados para discriminação, bem como outras características discriminantes, como a extensão do cluster e a soma total de deposições. Este conjunto de dados pode ser usado para desenvolver e testar algoritmos para discriminar entre raios gama e raios cósmicos em telescópios Cherenkov.

### Os dados são distribuídos em 11 colunas, sendo 10 colunas de atributo e 1 coluna de classe. A coluna de classe pode ser gamma ou hadron, e por razões técnicas o número de instâncias hadron está subestimado, 6688 exemplos contra 12332 exemplos gamma.
