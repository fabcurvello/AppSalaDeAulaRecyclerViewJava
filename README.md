# App Sala de Aula com RecyclerView (Java)

> Repositório didático: exercício prático de Android nativo com **Java**, desenvolvido e aplicado em sala de aula pelo Prof. Fabricio Curvello.

## Sobre o projeto

Aplicativo que exibe a grade de disciplinas da turma em uma lista com **RecyclerView**.

## Contexto acadêmico

Exercício aplicado em sala de aula, usado como prática guiada com os alunos.

## O que o app faz

- Lista de disciplinas montada com `RecyclerView`, mostrando nome, professor, dia da semana e sala.
- Linha divisória entre os itens (`DividerItemDecoration`).
- **Clique simples** em um item: mostra o dia da semana e a sala.
- **Clique longo**: mostra o nome da disciplina e o professor.

## Conceitos trabalhados em aula

- `RecyclerView`, `Adapter` e `ViewHolder`
- `LinearLayoutManager`
- Classe de modelo (`Disciplina`) com encapsulamento
- Tratamento de cliques simples e longos com `GestureDetector` (`RecyclerItemClickListener`)
- Organização do código em pacotes (activity, adapter, model)

## Tecnologias

- **Java**
- **Android SDK** (Android Studio)
- **Gradle**
- AndroidX RecyclerView
- `minSdk 28` / `compileSdk 34`

## Como executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/fabcurvello/AppSalaDeAulaRecyclerViewJava.git
   ```
2. Abra a pasta no **Android Studio** e aguarde a sincronização do Gradle.
3. Execute em um emulador ou dispositivo físico com Android compatível com a API 28 ou superior.

## Veja também

Outros repositórios de aula com o mesmo tema:

- [AppRecyclerViewUNAAnima](https://github.com/fabcurvello/AppRecyclerViewUNAAnima)
- [AppSalaDeAulaRecyclerViewAnima](https://github.com/fabcurvello/AppSalaDeAulaRecyclerViewAnima)

## Autor

**Fabricio Curvello**: professor de desenvolvimento de software no SENAI-RJ (desde 1997) e em faculdades do grupo Ânima Educação (IBMR e UNA).

- GitHub: [github.com/fabcurvello](https://github.com/fabcurvello)
- LinkedIn: [linkedin.com/in/fabriciocurvello](https://www.linkedin.com/in/fabriciocurvello)
- YouTube: [@fabriciocurvello](https://www.youtube.com/@fabriciocurvello)
