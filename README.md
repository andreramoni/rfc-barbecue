# rfc-barbecue
Proposal of a Barbecue compliance rules

In pt_BR for now:

Essa é a especificação de um protocolo ao qual todo churrasco deve estar em conformidade para poder ser considerado um bom churrasco.
Note que, alem de um protocolo (conjunto de regras) o churrasco tambem é um processo, e como nenhum processo melhora sua matéria prima (muito pelo contrário, a cada etapa voce pode piorá-la), diferenciar o que faz parte do protocolo (RFC proposal) ou ficará apenas como melhores práticas (BCP) precisa ficar claro.



Pelo modelo OSI (https://pt.wikipedia.org/wiki/Modelo_OSI#6_-_Camada_de_Apresenta%C3%A7%C3%A3o)

O Barbecue é um protocolo de camada 6, já que claramente todos os participantes precisam se transportar antes (camada 4 transporte) e assim que chegam ao local fazem o tcp handshake uns com os outros (camada 5 sessao).

Já a apresentação da carne servida, é obviamente a camada de apresentação (camada 6).

Contudo, é necessário que todos estejam no mesmo local fisico, que nao importa onde seja, e chamaremos entao de 127.0.0.1.



