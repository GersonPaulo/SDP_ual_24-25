SDP_ual_24-25
#                                                       Sistema de gestão de Eventos eventLink
# 1. Objetivos

Este projeto tem como objetivo desenvolver um sistema distribu´ıdo baseado na
microservi¸cos para a gest˜ao e venda de bilhetes online.

# 2. Descrição
Neste projeto pretende-se o desenvolvimento de um sistema distribuído que
permita aos utilizadores ter acesso aos próximos eventos, reservar e comprar
ingressos. O sistema será dividido em vários microsserviços independentes, cada
um responsável por uma parte específica da funcionalidade, como listagem de
eventos, gestão de utilizadores, processamento de pagamentos e emissão de ingressos.

# 3. Componentes mínimos do Projeto
O projeto deve conter, no mínimo, os seguintes microserviços:

1. Microserviço de gestão de eventos: Responsável pela gestão de informações sobre eventos, incluindo datas e locais.
2. Microserviço de utilizadores: Responsável pela autenticação e manutenção de contas de utilizadores.
3. Microserviço de pagamentos: Responsável por processar transações financeiras de forma segura.
4. Microserviço de bilhetes: Responsável pela gestão de ingressos digitais.

# 4. Tecnologias mínimas

*Python*: Para o desenvolvimento dos microserviços.

*Base de dados*: À escolha do grupo (importante destacar que, em aula, 
os exemplos e exercícios serão realizados com PostgreSQL).

*Docker*: Para a containerização dos microserviços.

*Kubernetes*: Para a gestão dos containers Docker.

As ferramentas adicionais necessarias ficam ao criterio de cada grupo. E importante salientar que o foco deste projeto é o desenvolvimento back-end, especificamente a arquitetura distribuıda baseada em microserviços. Portanto, a implementação de uma interface gráfica para o utilizador ñ è obrigatória. Para este projeto, a interação via linha de comandos é suficiente. Ressalta-se que a implementação de uma interface gráfica ñ será considerada na avaliação deste projeto.

# 5. Segurança

É necessário implementar a autenticação de utilizadores como medida de segurança.

# 6. Sistemas de ficheiros distribuídos
Deve ser utilizada uma solução de sistemas de ficheiros distribuídos para o armazenamento eficiente e escalável de dados relacionados a eventos e utilizadores.

# 7. Avaliação

Os alunos serão avaliados com base nos seguintes critérios:
Funcionalidade do sistema;
Integração efetiva entre os microserviços;
Robustez da segurança implementada.

# 8. Entrega do projeto

O projeto deve ser submetido via e-learning até 19 de janeiro de 2025, às 23h59.

# 10. Apresentação

Todos os projetos entregues serão apresentados em sala. Para isso, cada grupo deverá realizar uma apresentação do projeto desenvolvido para a turma. A apresentação serve para demonstrar que o código entregue foi, de fato, elaborado pelo grupo e que houve uma distribuição equilibrada do trabalho entre os membros.

O calendário das apresentações será disponibilizado no e-learning após o prazo final de entrega.
Cada apresentação terá a duração máxima de 15 minutos.
Durante a apresentação, devem ser abordados, no mínimo, os seguintes pontos:
Introdução: Apresentação breve do projeto e seus objetivos.
Estrutura do projeto: Descrição da arquitetura do sistema.
Simulação do sistema: Demonstração de um exemplo funcional do sistema, destacando todas as funcionalidades implementadas.
Conclusões: Considerações finais.
Dica: Para auxiliar na apresentação, recomenda-se o uso de slides (ex.: PowerPoint ou ferramentas similares).



