# O que é um sistema de controle de versões (VCS)?

r= O controle de versão, ou também conhecido como controle de
fonte, é uma prática de rastreamento e gerenciamento de alterações
em um código de software. Os sistemas de controle de versão são
como ferramentas de software, que permite que equipes de desenvolvimento
de software acompanhem e atualizem o código ao longo do tempo,
facilitando a colaboração, gerenciamento de distintas versões
de um projeto e a reversão de versões antigas no caso de algum
erro.

O VCS funciona registrando cada alteração realizada em arquivos
e p/ou projetos, seja adições, exclusão e modificações, mantendo
um histórico completo de todas as versões de um projeto, também
permitindo a consulta e comparação de alterações ao longo do tempo.

## Vantagens em utilizar um sistema de controle de versão:

1-- Desenvolvimento Simultâneo: Com o aumento da complexidade
dos projetos, torna-se essencial gerenciar múltiplas versões de
código, arquivos e até produtos inteiros. Isso permite que diferentes
profissionais, tais como desenvolvedores e designers, trabalhem
simultaneamente nos mesmos arquivos, sem o risco de sobrescrever
ou duplicar o trabalho dos colegas.

2-- Automação: Atualmente, empresas e equipes de desenvolvimento
estão focadas em alcançar mais qualidade e produtividade. Uma forma
eficaz de atingir esses objetivos é automatizar tarefas por meio de
scripts.

3-- Mudanças Monitoradas: Para que o trabalho em equipe seja eficiente,
é fundamental que todos os membros tenham visibilidade sobre as mudanças
feitas no produto. Saber quem fez o quê, quando e por quê é extremamente
valioso.
O controle de versão cumpre esse papel ao registrar de forma permanente
todo o histórico de alterações. Isso permite que todos acompanhe o andamento
do trabalho, entendam as motivações por trás das mudanças e, se necessário,
consigam identificar e corrigir erros com mais facilidade.

4-- Alta disponibilidade, segurança e recuperação de desastres: A segurança
do código é um dos bens mais valiosos de uma empresa. Utilizar o controle de
versão ajuda a proteger esse ativo, pois mantém uma cópia do repositório
acessível de qualquer lugar. Em caso de problemas, é possível alternar
rapidamente para essa réplica e manter a produção funcionando normalmente.
Além disso, o versionamento atua como uma barreira extra contra falhas de
segurança e ameaças virtuais, garantindo mais estabilidade e proteção
para as operações da empresa.

5-- Acompanhamento de upgrade, correção de bugs e outros ajustes: O (VCS)
vai muito além de apenas salvar cópias de arquivos. Ele registra todas as
alterações feitas no projeto, sendo ele em código, documentos ou recursos,
e indica quem fez cada modificação e quando.
Com isso, as equipes podem revisar, comparar, unir e até reverter alterações,
garantindo uma visão clara do estado atual e do histórico do projeto. Isso
também permite restaurar versões anteriores do produto, se necessário.
Além disso, o versionamento é essencial para recriar com precisão os
processos de pré-produção e prototipagem, pois mantém o controle não só do
código, mas também das ferramentas, ambientes de teste, bibliotecas e
configurações envolvidas.

## Exemplos de (VCS):

1-- Git; É o sistema mais popular atualmente. Ele permite que desenvolvedores
trabalhem juntos em um projeto, mesmo a distância, com controle total sobre cada
alteração feita. É rápido, confiável e usado por plataformas como GitHub e GitLab.

2-- (SVN) Ou Subversion; Mais tradicional, o SVN organiza as versões em um servidor
central. É útil para equipes que preferemum controle mais centralizado e direto do
histórico do projeto. Ainda é usado em empresas que mantém sistemas legados.

3-- Mercurial; Semelhante ao Git, o Mercurial também é distribuído, o que significa
que cada colaborador tem uma cópia completa do projeto. Ele é reconhecido por ser mais
simples de usar e com comandos mais intuitivos para iniciantes.

# O que é programação Orientada a Objetos (POO)?

r= É um paradigma de programação que busca organizar o código de maneira que ele se
aproxime do mundo real, facilitando o entendimento, manutenção e reutilização. Em vez
de apenas focar em funções e lógica, como em paradigmas mais tradicionais, a POO coloca
objetos como os principais componentes da aplicação. Esses objetos são "entidades" que
representam coisas do mundo real e têm características (atributos) e comportamnetos
(métodos). Imagine que está desenvolvendo um sistema para um colégio. Em vez de criar
funções soltas como -cadastrarAluno()- ou -mostrarBoletim()-, você cria uma classe
chamada -Aluno-, com atributos como nome, idade e notas, e métodos como -calcularMedia()-
e -exibirBoletim()-. Isso torna o código mais organizado e intuitivo, como se você
estivesse descrevendo pessoas, lugares ou situações.

## A POO é sustentada por quatros pilares principais:

1- Abstração: É a capacidade de esconder os detalhes complexos e mostrar apenas o que
é relevante. É como usar um carro: você sabe dirigir, mas não precisa entender o
funcionamento do motor para usá-lo. Em código, isso significa expor apenas métodos
e dados necessários, ocultando implementações internas.

2- Encapsulamento: Esse pilar protege os dados internos do objeto, permitindo que eles
sejam acessados e modificados apenas por métodos específicos. Isso ajuda a evitar erros,
pois impede que partes do programa alterem o estado do ojeto de forma indevida. É como
um cofre: você só acessa seu conteúdo com a chave certa.

3- Herança: Permite que uma classe herde características e comportamentos de outra.
Isso promove o reuso de código. Por exemplo, você pode ter uma classe Pessoa, e dela
derivar Aluno e Professor, que terão tudo que Pessoa tem, mas com comportamentos
específicos adicionados.

4-- Polimorfismo: É a habilidade de objetos diferentes responderm de forma distinta
à mesma mensagem (ou método). Por exemplo, um método fazerLogin() pode existir em várias
classes, mas se comportar de maneiras diferentes diferentes dependendo de quem está
usando: um aluno, um professor ou um administrador.

## 5 vantagens da POO:

1- reutulização de Código: A POO permite que o código já implementado seja reutilizado
em outros projetos, economizando tempo e aumentando a eficiência, através de herança e
polimorfismo.

2- Facilidade de Manutenção: A organização em classes e objetos torna o código mais fácil
de entender, o que facilita a manutenção e correção de bugs.

3- Organização Modular: A POO permite que o código seja organizado em unidades lógicas,
tornando-o mais fácil de gerenciar e resolver problemas.

4- Melhor Separação de Responsabilidades: A POO permite que as tarefas sejam distribuídas
de forma mais clara entre diferentes objetos, o que melhora a organização e a manutenção
do código.

5- Maior Capacidade de Escalabidade: A POO ajuda a tornar o código mais escalável, o que
é importante em projetos de software de grande porte.
