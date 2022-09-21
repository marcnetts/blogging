# Resumo Tópicos Especiais

# Paradigmas de programação

Em engenharia de software, paradigmas são formas de classificar as linguagens de programação baseadas em suas funções.

## Abordagem imperativa e declarativa

Programação imperativa é a que instrui à função sobre como seu estado mudará; em outras palavras, o programador descreve “como” algo deve ser feito. Já a programação declarativa é a que o programa declara o estado desejado de uma função, “o que“ a função deve fazer.

Paradigmas de programação procedural incluem a procedural e orientada a objetos. Já paradigmas de programação declarativa incluem a funcional, lógica, matemática, reativa e crítica.

Harper e Krishamurthi defendem em suas publicações que é difícil definir uma linguagem como puramente declarativa, funcional etc; a linguagem Go, por exemplo, é considerada multi-paradigma. e seus autores propõem que a linguagem é boa em integrar estilos lógicos, funcionais e imperativos. Pode se deduzir que embora as linguagens antigas possuíam uma paradigma plausível, é quase impossível indicar um único tipo a muitas linguagens; tentar simplificar o paradigma de uma risca viciar seus usuários em menos padrões de programação.

É normal que a maioria das linguagens populares foquem na programação imperativa, como as voltadas à web, mas abordando alguns conceitos de programação declarativa.

# CI/CD

O ***CI***/***CD*** (Continuous Integration/Continuous Delivery/Continuous Deployment) é uma prática de desenvolvimento para entregar programas com frequência aos clientes.

Antes do Continuous Integration, era comum que softwares fossem vulneráveis a conflitos de arquivos entre colaborações dos membros do grupo. Para evitar a violência entre colegas devs, o CI traz os conceitos de branches, resolução de conflitos e entrega de commits em um repositório de código.

Continuous Delivery foca em produzir partes do software em ciclos curtos, enquanto o Continuous Deployment é relacionado à entrega do programa em ciclos curtos.

Práticas comuns relacionadas a CI/CD são manter um repositório de código, automatizar a compilação, usar uma branch separada para o desenvolvimento e só mergir à principal após testes (como em um servidor de homologação), automatizar a compilação e testes, e ter acesso a builds antigos do código.

Vimos em aula como entregar um projeto em dupla no Github, site de repositório de aplicativos, demonstrando a facilidade de criação de projetos com o CI/CD.

# Sistemas Distribuídos

A computação distribuída é um campo da ciência da computação para distribuir o processamento entre máquinas diferentes, não utilizando as mesmas memórias como na computação paralela.

Estes sistemas trazem mais necessidade de infraestrutura e complexidade mas garantem eficiência, escalabilidade, confiabilidade e velocidade de resposta, com a possível redução de custos do sistema a longo prazo; por isso, são comuns em sistemas que exigem evitar falhas centrais e gargalos de disponibilidade, como redes telefônicas e de internet, jogos, computação científica e IoT.

Exemplos de arquiteturas de sistemas distribuídos são a arquitetura cliente-servidor, n-tier, three-tier (mais conhecida como MVC) e peer-to-peer.

Alguns desafios dos sistemas distribuídos são recuperação de falhas de envio de mensagens entre componentes, escala de testes e segurança de dados transmitidos.