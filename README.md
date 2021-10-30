# Glossário da Mentoria IaC de A a Z


Este projeto se destina a ter um glossário das principais palavras para auxiliar os participantes da Mentoria IaC.

- O termos estão em ordem alfabética sendo eles em Português, Inglês ou Aportuguesados
- O significado do termo está em Português
- Cada termo terá um link de referência e se for contundente terá um artigo sobre no blog da Mentoria IaC que será linkado também no verbete

## Escolha a letra do Alfabeto

[A](#a) | [B](#b) | [C](#c) | [D](#d) | [E](#e) | [F](#f) | [G](#g) | [H](#h) | [I](#i) | [J](#j) | [K](#k) | [L](#l) | [M](#m) | [N](#n) | [O](#o) | [P](#p) | [Q](#q) | [R](#r) | [S](#s) | [T](#t) | [U](#u) | [V](#v) | [W](#w) | [X](#x) | [Y](#y) | [Z](#z) |

## A

### [Aplicações]
colocação de (alguma coisa) sobre (outra); sobreposição.
em outras palavras,por exemplo, quando temos uma aplicação web hospedada na nuvem.
temos no exmplo citado a nossa aplicação web (apache por exeplo) hospedado (aramazenado) na nuvem.

### [Automação]
sabe aquele trampo repetido e diário? seus problemas acabaram.
Automação é substituir o trabalho manual e demorado por tarefas via software e/ou sistemas para executar e substituir os processos manuais.
### [Ansible](https://docs.ansible.com/)

### [Ansible] 
é uma ferramenta de [Código Aberto](###Código-Aberto) para automação de TI que automatiza o provisionamento em nuvem, o gerenciamento de configurações, a implantação de aplicativos e a orquestração intra-serviços.

### [AWS](https://aws.amazon.com/pt/)

AWS é o acrônimo para Amazon Web Services, é o provedor de serviços na nuvem da Amazon

### [Azure](https://docs.microsoft.com/pt-br/azure/?product=featured)

Azure, ou Microsoft Azure, é o provedor de serviços na nuvem da Microsoft

## B

### [Box]
Assim como a extensão vbox está para a imagem do virtualbox, o box está para a imagem instânciada/baixada pelo vagrant.
você pode procurar box no site do vagrant,segue o [link](https://app.vagrantup.com/boxes/search)


## C

### [CI/CD]
Você já foi em um local pra se alimentar e precisou de alguém para te servir o cardápio por exemplo?
basicamente CI/CD é um garçom, tecnicamente é um método para entregar aplicações,nesta etapa os métodos são integração,entrega,implantação contínua.
abreviando é,CI/CD continuous integration/continuous delivery.

### [Container]

Entenda container como sua definição... nada mais é que isolamento,exemplo, veja container como os cubinhos de gelo separados na forminha.
são ambientes em tempo de execução que disponilizam os arquivos, variaveis,IO,bibliotecas para funcionar.

### [Containerd](https://containerd.io/)

Containerd é um ambiente de execução de containers disponível como um daemon em ambientes Linux e Windows. É responsável por gerenciar todo o ciclo de vida de containers em seu host incluindo: armazenamento e transferência de imagens, execução e supervisão de containers, armazenamento de dados em baixo nível, etc.

### [Copy-on-Write](https://pt.wikipedia.org/wiki/C%C3%B3pia_em_grava%C3%A7%C3%A3o)

Copy-on-Write ou Cópia em gravação é uma técnica de gestão de recursos usada na programação de computadores para implementar eficientemente uma operação "duplicar" ou "copiar" em recursos modificáveis.


### [cri-o](https://cri-o.io/)

cri-o é um ambiente de execução de containers usando os padrões da [OCI](###OCI). É uma alternativa de implementação de interface de execução de containers para o [Kubernetes](###Kubernetes). 

### [Código Aberto](https://pt.wikipedia.org/wiki/C%C3%B3digo_aberto)

Código Aberto é um termo que se refere a um software cujo código está disponível para download por qualquer pessoa e a uma filosofia de criação de aplicativos voltada para a colaboração entre desenvolvedores.

## D

### [Daemon] 

Você já ouviu falar em aplicativo em 2 plano?
daemon é isso, um processo em background, ou seja 2 plano, logo ele fica rodando sem o controle direto de um usuário interativo.


### [Docker](https://www.docker.com/)

Docker é uma tecnologia que permite empacotar,entregar, e executar aplicações em containers
porque docker não é uma maquina virtual, Na prática, o Container promove a comunicação do hardware para o sistema operacional e diretamente para os containers, que cuidam do isolamento e da inicialização das aplicações. ... Já dentro da VM haverá inicialização do sistema operacional e, só então, as aplicações estarão ativadas.

### [Deploy]

Você já comprou uma pizza por aplicativo por exemplo ?
sim, o ato de alguem te entregar é um deploy, ou seja é basicamente pegar algo que está em uma posição /localização e colocar em outra. 
O deploy é o ato de pegar esse conjunto de arquivos e levar até um determinado lugar. Esse lugar é normalmente um servidor, que hospedará esse software e exibirá para o usuário sempre que solicitado.
(confira esse link para entender deploy de uma forma super atrativa -> [link](https://gomex.me/2020/07/17/o-que-%C3%A9-deploy/)

## E

## F

## G

### [GCP](https://cloud.google.com/docs?hl=pt-br)

GCP é o acrônimo para Google Cloud Platform, é o provedor de Infraestrutura da Google

## H

### [Host]
É a maquina fisíca onde esta rodando os serviços e aplicações, exemplo na virtualização temos o host e o guest, que no caso é a maquina instanciada compartilhada os mesmos recursos.

### [Hypervisors]
É um monitor de máquina virtual,ou seja é o processo que cria e executa máquinas virtuais.
por ele que é possivel que o HOST suporte várias VM'S compartilhando virtualmente seus recursos(memória,cpu por exemplo)

### [Helm](https://helm.sh/)

Helm é análogo a um gerenciador de pacotes e visa tornar mais fácil a distribuição de aplicações conteinerizadas voltadas para o [Kubernetes](###Kubernetes). O Helm é responsável por empacotar os recursos e manifestos do Kubernetes na forma de um Chart, controlando versões de recursos e simplificando a aplicação destes em clusteres Kubernetes.

## I

### [IaC](https://pt.wikipedia.org/wiki/Infraestrutura_como_C%C3%B3digo)

IaC, Infraestrutura como Código ou em inglês Infrastructure as Code, é o gerenciamento do provisionamento de Infraestrutura utilizando arquivos versionáveis e auditáveis.

### [Issue](https://docs.github.com/pt/issues/tracking-your-work-with-issues/creating-an-issue)

Issue é o termo usado pelo github para documentar um problema no repositório em questão. Ao abrir uma issue você está detalhando um problema ou melhoria desejada para aquele repositório de código.

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

### [Pipeline]

Quando você vai ao supermercado fazer compras( eu sei que neste periodo tudo está carissímo,graças ao bo...)
vocẽ coloca tudo na esteira do caixa e ela, e consequentemente a pessoa que esta no caixa te atendendo aperta no botão para a esteira trazer a sua mercadoria e ela passar na registradora ? isso é feito item por item, pra justamente garantir que cada produto seja pago, pois bem, esse é um exemplo de pipeline.
mas tecnicamente, o que é pipeline? é a automação do processo de entrega de um sofware de forma rápida sem perder a caracteristísca de de qualidade,segurança,estabilidade.
segue link para um melhor entendimento -> [link](https://gomex.me/2020/08/11/o-que-%C3%A9-pipeline/)

### [Packer](https://www.packer.io/docs)

Packer é uma ferramenta de [Código Aberto](###Código-Aberto) utilizada para construir imagens no provedor de cloud. Ela é uma das referencias para a [Infraestrutura Imutavel](###Infraestrutura-Imutavel)

### [Provisionamento]

são processos que se refere as etapas de necessidade e gerencimaento aos dados e recursos em TI, por exemplo, precisamos PROVISIONAR a maquina virtual.

### [Provedor]
Como o prṕrio termo sugere, um provedor é algo que prover, neste caso ele fornece serviços de qualidades em redes, aplicações, gerenciamento.
sua abreviação é, Managed Service Providers (MSPs)

### [provider]
Provedor de serviços, na construção da image/vbox por exemplo do debian, o vagrant exige que voce tenha um provider, virtualbox,vmware,aws,gcp, o que é bem lógico, pois sendo assim o vagrant um criador de provisionamento.


## Q

## R

### [RKE](https://rancher.com/docs/rke/latest/en/)

RKE é uma distribuição Kubernetes (binário) com certificação CNCF que resolve complexidades de instalação comuns do Kubernetes, removendo a maioria das dependências de host, apresentando um caminho estável para implantação, atualizações e reversões.
Ele seria algo semelhante ao [KOPS](https://kops.sigs.k8s.io/)
## S

## T

### [Terraform](https://www.terraform.io/intro/index.html)

Terraform é uma ferramenta de [Código Aberto](###Código-Aberto) utilizada para construir, modificar e versionar infraestrutura de forma segura e eficiente. Ela é uma das referencias para a Infraestrutura como Código ou [IaC](###IaC)

## U

## V

### [Volume](https://blog.container-solutions.com/understanding-volumes-docker)

Volumes são diretórios (ou arquivos) existentes fora do Union File System (UFS) padrão e existem como diretórios e arquivos normais no sistema de arquivos do hospedeiro (host).

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
