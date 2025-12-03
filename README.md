Bot został zbudowany jako modularny system obsługujący:

- komendy slash,

- listener’y eventów Discord,

- integrację z MongoDB,

- panel webowy (Spring Boot),

- dynamiczne ustawienia gildii,

- system cooldownów, wyjątków i zarządzania permisjami.

✨ Funkcje

🔹 Discord

Slash commands

Reagowanie na przyciski (ButtonEvent)

System wiadomości powitalnych (WelcomeMessage)

Obsługa eventów JDA z rozszerzonymi intencjami

🔹 Dashboard (Web Panel)

Folder: dashboard/

Uruchamiany przez Spring Boot

Metryki bota, statystyki, monitorowanie runtime

🔹 MongoDB

Folder: mongodb/

MongoConnection – połączenie z bazą

GuildManager – zarządzanie danymi serwerów

SettingsGuildManager – konfiguracje gildii

🔹 Utils

Cooldown

Scheduler

SlashCommand handler

HashUtils / GsonUtils

System Exclude / Pair
