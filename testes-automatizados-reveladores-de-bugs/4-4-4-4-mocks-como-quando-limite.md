# Mocks: Como, quando e até onde usar

[Neste vídeo](https://youtu.be/pup3dB1rKY8) falamos sobre o uso dos mocks. A ideia de imitar o comportamento de métodos de classes para facilitar a escrita dos testes de unidade é muito tentadora, entretanto, devemos ficar sempre alertas ao seguinte fato: um teste de unidade já tem a tendência a se distanciar da realidade de execução, se você ainda exagerar no uso do mock, ele vai ficar mais distante ainda, beirando a inutilidade.

A utilização de Mocks é uma carta que você tem na manga principalmente quando precisa testar uma unidade que depende de um sistema externo. Mas a ideia é minimizar o uso da utilização das expectativas e minimizar ainda mais o uso dos matchers.

