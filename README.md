LifeUp: Gamificando a Saúde
O LifeUp é uma aplicação desktop desenvolvida em Java que transforma a luta contra o sedentarismo numa jornada de RPG. Aqui, o seu progresso físico real é convertido em evolução dentro do jogo, utilizando mecânicas de gamificação para manter a motivação em alta.

🎮 O Conceito
Muitos profissionais e estudantes passam horas sentados à frente do computador. O LifeUp atua como um mestre de jogo (Game Master), incentivando pausas ativas e exercícios.

Fez uma caminhada? Ganhe XP.

Subiu escadas? Suba de nível.

Ficou parado muito tempo? Veja o seu avatar perder energia.

🛠️ Engenharia de Software (Design Patterns)
Este projeto não é apenas sobre gamificação, mas sobre a aplicação rigorosa de padrões de projeto para um código limpo e escalável:

Strategy Pattern: Utilizado para definir diferentes algoritmos de ganho de XP com base no tipo de exercício (Caminhada vs. Treino Intenso).

State Pattern: Controla o estado de humor e vitalidade do Avatar (Ex: Energizado, Neutro, Sedentário).

Observer Pattern: Garante que a interface visual e o sistema de conquistas sejam notificados automaticamente sempre que o usuário ganha XP.

Factory Method: Responsável pela geração dinâmica de missões diárias aleatórias.

✨ Funcionalidades
[x] Dashboard Visual: Interface intuitiva com barras de progresso e status do personagem.

[x] Missões Diárias: Desafios gerados automaticamente para quebrar a rotina.

[x] Evolução de Nível: Sistema de RPG com ganho de experiência.

[x] Sistema de Badges: Conquistas desbloqueáveis para marcos importantes.

💻 Tecnologias Utilizadas
Linguagem: Java 17+

Interface Gráfica: JavaFX (focada em feedback visual em tempo real)

Persistência de Dados: Armazenamento local (JSON/TXT)

🚀 Como Executar
Clone o repositório:

Bash
git clone https://github.com/seu-usuario/lifeup.git
Importe o projeto na sua IDE favorita (IntelliJ, Eclipse ou VS Code).

Execute a classe principal Main.java.

"Transformando o sedentarismo no boss final que todos conseguem derrotar." ⚔️
