# notes-development

## Análisis

## Diseño

## Implementación

- Herramientas de desarrollo

  - Node

    <https://nodejs.org/en/download/current>
    <https://nodejs.org/dist/v20.12.2/node-v20.12.2-x64.msi>

    ```powershell
    # verifies the right Node.js version is in the environment
    node -v # should print `v20.12.2`
    # verifies the right NPM version is in the environment
    npm -v # should print `10.5.0`
    ```

- PowerShell

  - [Resumen](https://learn.microsoft.com/en-us/powershell/scripting/overview)
  - [Instalación](https://learn.microsoft.com/es-es/powershell/scripting/install/installing-powershell-on-windows)

    - [Descargar](https://aka.ms/powershell-release?tag=stable)
    - Ejecutar

      ```powershell
      winget install --id Microsoft.Powershell --source winget
      ```

## Pruebas

- Proyectos de pruebas
  - XUnit.net - Proyectos de pruebas para .NET
    - [Sitio oficial](https://xunit.net)
    - [Contexto compartido entre pruebas](https://xunit.net/docs/shared-context)
- Generación de datos de pruebas
  - Bogus - Paquete de generación de datos de pruebas para .NET
    - [Sitio oficial](https://github.com/bchavez/Bogus)
    - [Explicación general](https://code-maze.com/data-generation-bogus-dotnet)
    - [Integración con Entity Framework](https://stenbrinke.nl/blog/taking-ef-core-data-seeding-to-the-next-level-with-bogus)
- Mock de clases para pruebas
  - https://github.com/devlooped/moq
  - https://www.youtube.com/watch?v=a6Qab5l-VLo
  - https://www.codemag.com/Article/2305041/Using-Moq-A-Simple-Guide-to-Mocking-for-.NET
  - https://code-maze.com/using-moq-to-determine-if-method-is-called/
- Validaciones en pruebas
  - Fluent Assertions - Paquete para hacer validaciones "fluidas" para .NET
    - [Sitio oficial](https://fluentassertions.com)
    - [Explicación general](https://fluentassertions.com/introduction)
- Docker
  - Testcontainers - Paquete de integración de Docker para .NET
    - [Sitio oficial](https://testcontainers.com/guides/getting-started-with-testcontainers-for-dotnet)
    - [Sitio oficial .NET](https://dotnet.testcontainers.org/)
    - [Integración con pruebas en .NET 1](https://blog.jetbrains.com/dotnet/2023/10/24/how-to-use-testcontainers-with-dotnet-unit-tests)
    - [Integración con pruebas en .NET 2](https://www.milanjovanovic.tech/blog/testcontainers-integration-testing-using-docker-in-dotnet)
- TODO
  - <https://milan.milanovic.org/post/enabling-high-code-quality-in-net/>

## Despliegue

## Mantenimiento
