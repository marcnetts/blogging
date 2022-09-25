# Monolitos e microsserviços

Na arquitetura tradicional (monolítica), o sistema é desenvolvido e entregue como uma única entidade, com serviços dependentes entre si. Com a arquitetura de microsserviços, um sistema é fragmentado em componentes menores e independentes mas interligados.

Não se confunda com APIs; estes são uma estratégia para comunicação entre aplicações enquanto os microsserviços focam na divisão de um sistema, mas é comum que APIs para grandes sistemas sejam implementadas por microsserviços.

O nome "microsserviço" também é apenas uma nomeclatura e não implica que exista um "macrosserviço" ou semelhante. 

# Comparações

## Referências de dados
Se uma API lida com vários grupos de dados, cada microsserviço se especializará em um deles; para uma clínica veterinária, por exemplo, um microsserviço cuidará dos dados de animais, enquanto outro dos veterinários e um terceiro de autenticação. Isto permite que as regras de negócio evoluam individualmente e que diferentes tecnologias sejam utilizadas para tratar cada dado.

## Memória
Microsserviços permitem que máquinas e memórias diferentes sejam utilizadas no lugar de serviços compartilharem a mesma memória.

## Monitoramento
Microsserviços exigem mais instâncias de monitoramento, porém é possível identificar melhor qual parte de um sistema está em gargalo ou indisponível.

## Escalabilidade
Um microsserviço com mais carga de trabalho pode ser escalado individualmente ao invés do sistema inteiro.

## Conhecimento
Como sistemas monolíticos são os mais apresentados em cursos de programação, são os mais comuns em habilidades de devs. É por parte o motivo da arquitetura monolítica ser a mais popular.
Microsserviços também exigem uma qualificação maior para assegurar o funcionamento de todas partes, mas a complexidade do sistema é distribuída para cada componente e separa-se a atuação de cada dev em um projeto.

## Desenvolvimento
As IDEs são mais habilitadas a desenvolver sistemas monolíticos, como por exemplo para refatorar o nome de uma variável. Sistemas monolíticos também são implementados em um único "módulo", mas microsserviços permitem que apenas um componente específico fique indisponível durante sua atualização.

## Perfomance
Por usar menos requisições, monolitos são mais rápidos para enviar dados. O compartilhamento de memórias, porém, pode afetá-lo quando um componente é mais utilizado.

## Prazos e custos
Microsserviços inicialmente exigem um tempo e orçamento maior para ser desenvolvidos, mas sua manutenção pode ser mais rápida e barata com o tempo.

# Implementação
Quando se espera que um sistema será de grande escala, aguns autores entendem que é ideal iniciá-lo com microsserviços, mas pode ser justificável iniciar por monolitos se o sistema e a equipe iniciam com baixo porte. Um possível sinal de migrar para microsserviços na complexidade é quando várias pessoas estão trabalhando na aplicação, mas pode existir uma boa modularização dentro dele para compensar e os custos/instabilidades de migração podem não valer a pena.
