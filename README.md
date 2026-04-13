🚀 LifeUp: Gamificando a Saúde
O LifeUp é uma aplicação desktop desenvolvida em Java que transforma o combate ao sedentarismo numa jornada interativa de RPG. Através da gamificação, o esforço físico realizado no mundo real é convertido em evolução direta de um personagem virtual.

🎮 O Conceito
Muitos profissionais e estudantes passam horas em frente ao computador, o que prejudica a saúde a longo prazo. O LifeUp atua como um incentivo lúdico:

Movimentou-se? Ganhe experiência (XP) e suba de nível.

Ficou inativo? O seu Avatar mostra sinais de cansaço ou desânimo.

Cumpriu metas? Desbloqueie conquistas e medalhas exclusivas.

🛠️ Engenharia de Software
Este projeto foi construído focando em Clean Code e na aplicação de padrões de projeto do GoF (Gang of Four):

Strategy: Implementado para processar diferentes algoritmos de ganho de XP de acordo com o tipo de atividade física.

Observer: Utilizado para que a interface gráfica e o sistema de conquistas sejam atualizados automaticamente sempre que o progresso ocorre.

State: Gere os estados comportamentais e visuais do Avatar (ex: Ativo, Sedentário, Exausto).

Factory Method: Responsável pela criação dinâmica e aleatória de missões diárias.

✨ Funcionalidades Principais
Painel de Controlo (Dashboard): Visualização em tempo real do nível, XP e status do personagem.

Sistema de Missões: Desafios gerados diariamente para quebrar a rotina.

Feedback Visual: Interface rica construída em JavaFX para garantir a melhor experiência de utilizador.

Persistência de Dados: Registo local da jornada e do progresso do utilizador.

🚀 Como Executar
Clonar o repositório:

Bash
git clone https://github.com/seu-usuario/lifeup.git
Importar o Projeto: Utilize a sua IDE de preferência (IntelliJ, Eclipse ou VS Code) como um projeto Java.

Executar: Inicie a aplicação através da classe principal:

Plaintext
src/main/java/com/lifeup/Main.java
"Transformando o sedentarismo no Boss Final que todos conseguem derrotar." ⚔️
