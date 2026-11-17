# Changelog

## v1.0.0 – Módulo de Empréstimos (TDD)

- **Fase 01:** classes `Cliente` e `ContaBancaria` (composição com `Cliente` e `Agencia`).
- **Fase 02:** interface `IEmprestimoService` na pasta `Services` (regra R1).
- **Fase 03:** projeto de testes xUnit `PrjFinanceiro.Tests` na solução, referenciando `PrjFinanceiro`;
  `EmprestimoService.CalcularJurosSimples` criado via TDD (Red → Green → Refactor).
- **Fase 04:** respostas em `Documentacao/Respostas_Fase04.md`.
- **Fase 05:** `CalcularJurosCompostos` (regra R2) via TDD, com cálculo em `decimal`.

Total: 11 casos de teste (2 `[Fact]` + 9 linhas de `[Theory]`).

Executar os testes: `dotnet test AppMVC/PrjFinanceiroSLN/PrjFinanceiroSLN.sln`
ou, no Visual Studio, menu **Teste > Gerenciador de Testes > Executar Todos**.
