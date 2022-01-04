# Scheduling and Api

Projeto desenvolvido para testar uma alternativa de rodar alguns jobs com ***Cron*** e manter uma API normalmente, sem a necessidade de ficar chamando com um Broker ou WinSvc.

Então foi possivel colocar uma execução a um metodo agendada com o Cron para ser executada de tempos em tempos.

Funcionou como esperado.

## Introdução

Essas instruções fornecerão uma cópia do projeto em execução na sua máquina local para fins de desenvolvimento e teste.

### Prerequisitos

O que você precisa para baixar, rodar e disponibilizar.

* Um editor de sua preferência
* Dotnet core 3.1 instalado

### Utilizado no teste

* Projeto feito em C# no modelo de WebApi 2
* [Cronos](https://github.com/HangfireIO/Cronos)

### Instalação

Após a execução do pre requisitos, segue um passo a passo de como rodar localmente.

Clonar o repositório

```
git clone git@github.com:robsonpedroso/scheduling-api.git
```

Acesse a pasta do projeto que foi clonado e execute o build

```
dotnet build
```

## Versionamento

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

```
Given a version number MAJOR.MINOR.PATCH, increment the:

MAJOR version when you make incompatible API changes,
MINOR version when you add functionality in a backwards compatible manner, and
PATCH version when you make backwards compatible bug fixes.
Additional labels for pre-release and build metadata are available as extensions to the MAJOR.MINOR.PATCH format.
```

## Autores

* **Robson Pedroso** - *Projeto inicial* - [RobsonPedroso](https://github.com/robsonpedroso)

## License

[MIT](https://opensource.org/licenses/MIT)

