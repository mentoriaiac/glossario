# Glossário da MentoriaIaC de A a Z

Este projeto se destina a ter um glossário das principais palavras para auxiliar os participantes da Mentoria IaC.

- O termos estão em ordem alfabética sendo eles em Português, Inglês ou Aportuguesados
- O significado do termo está em Português
- Cada termo terá um link de referencia e se for contundente terá um artigo sobre no blog da Mentoria IaC que será linkado também no verbete

## Escolha a letra do Alfabeto

[A](#a) | [B](#b) | [C](#c) | [D](#d) | [E](#e) | [F](#f) | [G](#g) | [H](#h) | [I](#i) | [J](#j) | [K](#k) | [L](#l) | [M](#m) | [N](#n) | [O](#o) | [P](#p) | [Q](#q) | [R](#r) | [S](#s) | [T](#t) | [U](#u) | [V](#v) | [W](#w) | [X](#x) | [Y](#y) | [Z](#z) |

## A

### [Ansible](https://docs.ansible.com/)

Ansible é uma ferramenta de [Código Aberto](###Código-Aberto) para automação de TI que automatiza o provisionamento em nuvem, o gerenciamento de configurações, a implantação de aplicativos e a orquestração intra-serviços.

### [AWS](https://aws.amazon.com/pt/)

AWS é o acrônimo para Amazon Web Services, é o provedor de serviços na nuvem da Amazon

### [Azure](https://docs.microsoft.com/pt-br/azure/?product=featured)

Azure, ou Microsoft Azure, é o provedor de serviços na nuvem da Microsoft

## B

## C

### [Container](https://computerworld.com.br/plataformas/na-era-da-conteinerizacao-afinal-alguem-sabe-o-que-e-container/)

Metodologia utilizada para empacotar aplicações para que possam ser executadas/disponibilizadas com o seu subconjunto de dependências de maneira isolada e eficiente no intuito de segregar e facilitar a portabilidade dessas aplicações.

### [Containerd](https://containerd.io/)

Containerd é um ambiente de execução de containers disponível como um daemon em ambientes Linux e Windows. É responsável por gerenciar todo o ciclo de vida de containers em seu host incluindo: armazenamento e transferência de imagens, execução e supervisão de containers, armazenamento de dados em baixo nível, etc.

### [Copy-on-Write](https://pt.wikipedia.org/wiki/C%C3%B3pia_em_grava%C3%A7%C3%A3o)

Copy-on-Write ou Cópia em gravação é uma técnica de gestão de recursos usada na programação de computadores para implementar eficientemente uma operação "duplicar" ou "copiar" em recursos modificáveis.


### [cri-o](https://cri-o.io/)

cri-o é um ambiente de execução de containers usando os padrões da [OCI](###OCI). É uma alternativa de implementação de interface de execução de containers para o [Kubernetes](###Kubernetes). 

### [Código Aberto](https://pt.wikipedia.org/wiki/C%C3%B3digo_aberto)

Código Aberto é um termo que se refere a um software cujo código está disponível para download por qualquer pessoa e a uma filosofia de criação de aplicativos voltada para a colaboração entre desenvolvedores.

## D

### [Deploy](https://www.youtube.com/watch?v=gJw7l2JKpuQ)

No contexto de desenvolvimento de software, significa implantar, colocar em posição ou disponibilizar para uso. O deploy pode ser manual, parcialmente automatizado ou completamente automatizado, sendo este diretamente relacionado ao conceito de Integração Contínua (CI).

## E

## F

## G

### [GCP](https://cloud.google.com/docs?hl=pt-br)

GCP é o acrônimo para Google Cloud Platform, é o provedor de Infraestrutura da Google

## H

### [Helm](https://helm.sh/)

Helm é análogo a um gerenciador de pacotes e visa tornar mais fácil a distribuição de aplicações conteinerizadas voltadas para o [Kubernetes](###Kubernetes). O Helm é responsável por empacotar os recursos e manifestos do Kubernetes na forma de um Chart, controlando versões de recursos e simplificando a aplicação destes em clusteres Kubernetes.

## I

### [IaC](https://pt.wikipedia.org/wiki/Infraestrutura_como_C%C3%B3digo)

IaC, Infraestrutura como Código ou em inglês Infrastructure as Code, é o gerenciamento do provisionamento de Infraestrutura utilizando arquivos versionáveis e auditáveis.

## J

## K

### [Kubernetes](https://kubernetes.io/pt-br/docs/home/)

Kubernetes é uma ferramenta open source de orquestração de containers mantido pela Cloud Native Computing Foundation ou [CNCF](https://www.cncf.io/), com a finalidade de automatizar a entrega, escalonamento e manutenção de aplicações conteinerizadas.

## L

### [LGTM](https://www.abbreviationfinder.org/pt/acronyms/lgtm_looks-good-to-me.html)

LGTM é o acrônimo para "*Looks good to me*" (em tradução livre: *está bom para mim*), é utilizado na revisão de código para informar que o que foi proposto está correto para quem está revisando.

## M

## N

## O

### [OCI](https://opencontainers.org/)

OCI é o acrônimo para Open Container Initiave. É uma estrutura de governança aberta que visa a criação de padrões a serem adotados na indústria de containers, tanto relativo a formato, quanto a execução de containers.

## P

### [Packer](https://www.packer.io/docs)

Packer é uma ferramenta de [Código Aberto](###Código-Aberto) utilizada para construir imagens no provedor de cloud. Ela é uma das referencias para a [Infraestrutura Imutavel](###Infraestrutura-Imutavel)

## Q

## R

## S

## T

### [Terraform](https://www.terraform.io/intro/index.html)

Terraform é uma ferramenta de [Código Aberto](###Código-Aberto) utilizada para construir, modificar e versionar infraestrutura de forma segura e eficiente. Ela é uma das referencias para a Infraestrutura como Código ou [IaC](###IaC)

## U

## V

### [Volume](https://www.youtube.com/watch?v=htqWxw8VTb4)

Volume é uma forma de colocar um filesystem dentro do container. Ele está montado no container, mas não faz parte do container, ficando armazenados dentro do host Docker.

## X

## Y

## Z

## Como contribuir

- Fork o projeto
- Clone o fork projeto no seu usuário
- Crie uma branch para realizar a modificação
- Adicione o termo sugerido em ordem alfabética
- Suba as modificações com `git push`
- E crie um PR para o repositório [github.com/mentoriaiac/glossário.git](https://github.com/mentoriaiac/glossário.git)
