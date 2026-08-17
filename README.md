# Multivibrador Astável com BC548

Este foi um projeto desenvolvido durante a disciplina de Princípios de Engenharia Eletrônica. A proposta era montar um circuito multivibrador astável utilizando dois transistores BC548, dois LEDs e componentes passivos.

O projeto inicialmente seria realizado em um trio, como foi feito pelos demais alunos da turma. Porém, acabei realizando sozinho todas as etapas, desde o desenvolvimento da placa até a montagem e os testes finais.

## Desenvolvimento da PCB

Comecei o projeto utilizando o **KiCad** para desenvolver o esquemático e o layout da placa.

Passei aproximadamente um dia testando diferentes posições e configurações dos componentes e das trilhas. A ideia era encontrar uma disposição que fosse funcional e, ao mesmo tempo, deixasse a placa o mais organizada e otimizada possível.

Durante essa etapa, também precisei considerar o tamanho das trilhas, a posição dos componentes e a facilidade para realizar a soldagem posteriormente.

Depois de finalizar o layout, preparei a placa para a fabricação.

## Fabricação da placa

A placa foi produzida utilizando o processo de corrosão química com **percloreto de ferro**.

Foram feitas duas placas durante o processo. Uma delas acabou apresentando problemas na corrosão e não ficou em condições adequadas para utilização, sendo descartada.

A segunda placa ficou em condições melhores e foi utilizada para continuar o projeto.

Depois da corrosão, realizei os furos para os componentes utilizando uma **broca de 1 mm**, tomando cuidado para manter os furos alinhados com os pads da placa.

## Componentes

* 2x Transistores BC548
* 2x LEDs
* Resistores de 1 kΩ
* Resistores de 100 kΩ
* 2x Capacitores eletrolíticos de 4,7 µF
* Chave ON/OFF
* Alimentação de 5 V

## Montagem e primeiros testes

Com a placa pronta, comecei a soldagem dos componentes.

Durante a primeira montagem, encontrei alguns problemas. Em algumas partes houve **excesso de solda nas trilhas**, o que poderia causar contato indesejado entre regiões próximas da placa. Fiz a correção retirando o excesso e ajustando a soldagem.

Também percebi um erro na **polaridade dos capacitores eletrolíticos**, que foram montados de forma invertida. Após identificar o problema, corrigi a posição dos componentes antes de continuar os testes.

Durante os testes, um dos LEDs acabou queimando. Utilizei um **multímetro** para verificar o circuito e ajudar a identificar a falha. Depois de confirmar que o LED estava com problema, fiz a substituição e continuei a montagem.

Outro problema encontrado foi a utilização incorreta de alguns **resistores relacionados aos LEDs e aos transistores**. Depois de identificar o erro, os resistores foram substituídos pelos valores corretos.

## Correções e resultado

O projeto passou por várias etapas de teste e correção até chegar ao funcionamento esperado.

Os principais problemas encontrados durante o desenvolvimento foram:

* Uma das placas precisou ser descartada devido a problemas durante a corrosão;
* Excesso de solda em algumas trilhas;
* Polaridade invertida dos capacitores;
* LED queimado;
* Resistores incorretos no circuito;
* Necessidade de revisar conexões entre LEDs e transistores.

Depois das correções, o circuito passou a funcionar corretamente, realizando a alternância dos LEDs conforme esperado.

## O que aprendi

Apesar de alguns problemas durante a montagem, o projeto foi uma experiência importante para entender melhor o processo completo de desenvolvimento de uma PCB.

Além de trabalhar com o **KiCad**, tive contato prático com fabricação de placas por corrosão química, furação, soldagem, testes com multímetro e diagnóstico de problemas.

O projeto também mostrou na prática que pequenos erros no desenvolvimento ou na montagem podem impedir o funcionamento do circuito, e que saber identificar e corrigir esses problemas faz parte do processo.

### Conhecimentos utilizados

* KiCad
* Eletrônica analógica
* Transistores BC548
* LEDs
* Resistores e capacitores
* Projeto de PCB
* Fabricação de PCB
* Corrosão com percloreto de ferro
* Soldagem
* Uso de multímetro
* Diagnóstico e correção de falhas

Avaliação: Nota máxima no projeto, conforme avaliação da disciplina.
