# SDP_ual_24-25
/*cvb*/
Sistema de gestão de Eventos eventLink


Sistema distribu´ıdos e Paralelos - 2024/2025
Enunciado do Projeto
Sistema de gest˜ao de
Eventos
eventLink
1 Objetivos
Este projeto tem como objetivo desenvolver um sistema distribu´ıdo baseado na
microservi¸cos para a gest˜ao e venda de bilhetes online.
2 Descri¸c˜ao
Neste projeto pretende-se o desenvolvimento de um sistema distribu´ıdo que
permita aos utilizadores ter acesso aos pr´oximos eventos, reservar e comprar
ingressos. O sistema ser´a dividido em v´arios microservi¸cos independentes, cada
um respons´avel por uma parte espec´ıfica da funcionalidade, como listagem de
eventos, gest˜ao de utilizadores, processamento de pagamentos e emiss˜ao de ingressos.
3 Componentes m´ınimos do Projeto
O projeto deve ter pelo menos os seguintes microservi¸cos:
1. Microservi¸co de gest˜ao de eventos: Gest˜ao de informa¸c˜oes sobre eventos, incluindo datas e locais.
2. Microservi¸co de utilizadores: Respons´avel pela autentica¸c˜ao e manuten¸c˜ao
de contas de utilizadores.
3. Microservi¸co de pagamentos: Processa transa¸c˜oes financeiras de forma
segura.
4. Microservi¸co de bilhetes: Realiza a gest˜ao de ingressos digitais.
4 Tecnologias m´ınimas
• Python: Para o desenvolvimento dos microservi¸cos.
• Base de dados: `a escolha do grupo (importante referir que em aula os
exemplos e exerc´ıcios ser˜ao com Postgres)
• Docker: Para a containeriza¸c˜ao dos microservi¸cos.
• Kubernetes: Para gest˜ao dos containers Docker.
As ferramentas adicionais necess´arias ficam ao crit´erio de cada grupo. E impor- ´
tante salientar que o foco deste projeto ´e o desenvolvimento back-end,
especificamente a arquitetura distribu´ıda baseada em microservi¸cos.
Portanto, a implementa¸c˜ao de uma interface gr´afica para o utilizador
n˜ao ´e obrigat´oria. Para este projeto, a intera¸c˜ao via linha de comandos ´e suficiente. Ressalta-se que a implementa¸c˜ao de uma interface
gr´afica n˜ao ser´a considerada na avalia¸c˜ao deste projeto.
1
5 Seguran¸ca
Em termos de sugran¸ca ´e necess´ario implementar autentica¸c˜ao do utilizador.
6 Sistemas de Ficheiros Distribu´ıdos
Utiliza¸c˜ao de sistemas de ficheiros distribu´ıdos para armazenamento eficiente e
escal´avel de dados relacionados a eventos e utilizadores.
7 Avalia¸c˜ao
Os alunos ser˜ao avaliados com base na funcionalidade do sistema, na integra¸c˜ao
efetiva dos microservi¸cos, na robustez da seguran¸ca implementada.
8 Entrega do Projeto
O projeto deve ser entregue via e-learning at´e 19 de janeiro de 2025 at´e `as
'''