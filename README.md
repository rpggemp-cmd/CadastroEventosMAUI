# Cadastro de Eventos — .NET MAUI

Aplicativo demonstrativo para cadastrar eventos e exibir um resumo com duração e custo total.

## Funcionalidades
- Cadastro de nome, datas, número de participantes, local e custo por participante.
- `BindingContext` associado à model `Evento`.
- Duração calculada por `DateTime` e diferença representada por `TimeSpan`.
- Custo total calculado por participantes × custo unitário.
- Navegação para página de resumo e validação de dados.

## Como executar
1. Instale o Visual Studio 2022 com a carga de trabalho **Desenvolvimento de interface do usuário de aplicativos multiplataforma .NET (MAUI)** ou instale o .NET 8 SDK com os workloads MAUI.
2. Abra `CadastroEventosMAUI.csproj`.
3. Selecione um emulador Android, dispositivo ou destino Windows e execute.

> Observação: o projeto foi preparado como código-fonte .NET MAUI. A compilação e as capturas reais devem ser feitas em ambiente com o workload MAUI instalado.

## Regra de duração
A duração apresentada considera os dias corridos incluindo a data de início e a data de término. Exemplo: de 10/11 a 12/11 = 3 dias.
