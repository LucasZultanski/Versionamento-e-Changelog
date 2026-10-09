# Changelog

Todas as mudanças notáveis neste projeto serão documentadas neste arquivo.

O formato é baseado em [Keep a Changelog](https://keepachangelog.com/pt-BR/1.1.0/),
e este projeto adere ao [Versionamento Semântico](https://semver.org/lang/pt-BR/spec/v2.0.0.html).

## [Unreleased]

## [1.3.0] - 2026-06-08

### Changed

- O agendamento de preparo agora aceita múltiplos horários por dia e seleção de dias da
  semana. O formato anterior (horário único) continua aceito sem alterações.

## [1.2.1] - 2026-05-12

### Fixed

- Novelas e comerciais na TV que pronunciavam a palavra "café" iniciavam o preparo
  automaticamente. Agora é necessário dizer a palavra de ativação antes do comando.

## [1.2.0] - 2026-05-04

### Added

- Integração com assistentes de voz para iniciar, agendar e cancelar o preparo.

## [1.1.1] - 2026-04-14

### Fixed

- A granulometria "extrafina" moía os grãos a ponto de entupir o filtro, e a nuvem de pó de
  café resultante acionava o detector de fumaça da cozinha.

## [1.1.0] - 2026-04-06

### Added

- Suporte ao moedor integrado, com ajuste de granulometria (grossa, média, fina e extrafina).

## [1.0.2] - 2026-03-18

### Fixed

- O sensor de nível de água confundia leite com água, permitindo preparar um "café com leite"
  sem nenhum café.
- O alerta de reservatório vazio tocava em volume máximo às 3h da manhã quando o agendamento
  estava configurado para o dia seguinte.

## [1.0.1] - 2026-03-05

### Fixed

- A cafeteira preparava café descafeinado em todas as segundas-feiras, pois "segunda" era
  interpretado como a "segunda opção" do menu de grãos.
- Perfis com emoji no nome faziam o moedor entrar em loop infinito.

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

[unreleased]: https://github.com/LucasZultanski/Versionamento-e-Changelog/compare/v1.3.0...HEAD
[1.3.0]: https://github.com/LucasZultanski/Versionamento-e-Changelog/compare/v1.2.1...v1.3.0
[1.2.1]: https://github.com/LucasZultanski/Versionamento-e-Changelog/compare/v1.2.0...v1.2.1
[1.2.0]: https://github.com/LucasZultanski/Versionamento-e-Changelog/compare/v1.1.1...v1.2.0
[1.1.1]: https://github.com/LucasZultanski/Versionamento-e-Changelog/compare/v1.1.0...v1.1.1
[1.1.0]: https://github.com/LucasZultanski/Versionamento-e-Changelog/compare/v1.0.2...v1.1.0
[1.0.2]: https://github.com/LucasZultanski/Versionamento-e-Changelog/compare/v1.0.1...v1.0.2
[1.0.1]: https://github.com/LucasZultanski/Versionamento-e-Changelog/compare/v1.0.0...v1.0.1
[1.0.0]: https://github.com/LucasZultanski/Versionamento-e-Changelog/compare/v0.6.0...v1.0.0
[0.6.0]: https://github.com/LucasZultanski/Versionamento-e-Changelog/compare/v0.5.0...v0.6.0
[0.5.0]: https://github.com/LucasZultanski/Versionamento-e-Changelog/compare/v0.4.0...v0.5.0
[0.4.0]: https://github.com/LucasZultanski/Versionamento-e-Changelog/compare/v0.3.0...v0.4.0
[0.3.0]: https://github.com/LucasZultanski/Versionamento-e-Changelog/compare/v0.2.0...v0.3.0
[0.2.0]: https://github.com/LucasZultanski/Versionamento-e-Changelog/compare/v0.1.0...v0.2.0
[0.1.0]: https://github.com/LucasZultanski/Versionamento-e-Changelog/releases/tag/v0.1.0
