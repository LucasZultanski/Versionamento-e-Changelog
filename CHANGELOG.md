# Changelog

Todas as mudanças notáveis neste projeto serão documentadas neste arquivo.

O formato é baseado em [Keep a Changelog](https://keepachangelog.com/pt-BR/1.1.0/),
e este projeto adere ao [Versionamento Semântico](https://semver.org/lang/pt-BR/spec/v2.0.0.html).

## [Unreleased]

## [1.0.0] - 2026-02-23

### Added

- Documentação completa da API pública.
- Página de ajuda com a lista de todos os comandos disponíveis.

### Changed

- API pública estabilizada sob o prefixo `/api/v1`.

### Fixed

- O histórico de cafés registrava o preparo duas vezes quando a notificação era reenviada.

## [0.6.0] - 2026-02-02

### Added

- Internacionalização da interface (português e inglês).
- Modo "Plantão": preparo automático de um café forte ao detectar uso do sistema após as 22h.

### Fixed

- A conversão de temperatura exibia valores em Fahrenheit com o símbolo de Celsius.

## [0.5.0] - 2026-01-12

### Added

- API REST para controle remoto da cafeteira.
- Autenticação na API por token estático.

### Changed

- Os perfis de usuário passaram a ser armazenados em JSON em vez de INI.

## [0.4.0] - 2025-12-15

### Added

- Exportação do histórico de cafés em CSV.
- Suporte a leite vaporizado, com receitas de cappuccino e latte.

## [0.3.0] - 2025-12-01

### Added

- Perfis de usuário com receitas favoritas.
- Sensor de nível de água com alerta de reservatório vazio.

### Fixed

- O agendamento ignorava os minutos do horário informado (ex.: 07:45 preparava às 07:00).

## [0.2.0] - 2025-11-17

### Added

- Agendamento de preparo por horário.
- Notificação de "café pronto" via terminal.

### Changed

- A intensidade padrão foi alterada de "forte" para "média".

## [0.1.0] - 2025-11-03

### Added

- Comando `brew` para iniciar o preparo de um café padrão.
- Configuração de intensidade do café (fraca, média e forte).
- README com instruções de instalação e uso.

[unreleased]: https://github.com/LucasZultanski/Versionamento-e-Changelog/compare/v1.0.0...HEAD
[1.0.0]: https://github.com/LucasZultanski/Versionamento-e-Changelog/compare/v0.6.0...v1.0.0
[0.6.0]: https://github.com/LucasZultanski/Versionamento-e-Changelog/compare/v0.5.0...v0.6.0
[0.5.0]: https://github.com/LucasZultanski/Versionamento-e-Changelog/compare/v0.4.0...v0.5.0
[0.4.0]: https://github.com/LucasZultanski/Versionamento-e-Changelog/compare/v0.3.0...v0.4.0
[0.3.0]: https://github.com/LucasZultanski/Versionamento-e-Changelog/compare/v0.2.0...v0.3.0
[0.2.0]: https://github.com/LucasZultanski/Versionamento-e-Changelog/compare/v0.1.0...v0.2.0
[0.1.0]: https://github.com/LucasZultanski/Versionamento-e-Changelog/releases/tag/v0.1.0
