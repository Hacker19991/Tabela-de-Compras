# **AppCompras (Tabela de compras)**

> Um aplicativo Android desenvolvido para monitorar o consumo de recursos.

## Descrição
O **AppCompras** permite ao usuário que possa marcar quais compra ela queira para o app fazer a somatoria de valores dos produtos selecionados.

## Funcionalidades
- [x] Entrada de dados de consumo
- [x] Cálculo e exibição de estatísticas de consumo
- [x] Gráficos interativos para visualização dos dados
- [x] Interface intuitiva e amigável
- [ ] Suporte para diferentes tipos de recursos (planejado para futuras versões)

## Tecnologias Utilizadas
- [x] **Android Studio** (versão recomendada: Bumblebee | 2021.1.1)
- [x] **Java** para desenvolvimento
- [x] **ConstraintLayout** para interface responsiva
- [ ] **TextView**, **EditText** para entrada e exibição de dados

## Como Rodar o Projeto
Siga os passos abaixo para rodar o projeto localmente:

1. Clone este repositório:
   ```bash
   https://github.com/Hacker19991/Tabela-de-Compras
   
2. Abra o projeto no Android Studio.
   
3. Compile e execute o projeto em um emulador ou dispositivo físico.

## Estrutura do Projeto

```
── app
   ├── src
   │   ├── main
   │   │   ├── java/com/example/appconsumo
   │   │   │   ├── MainActivity.java # Atividade principal para monitoramento de consumo
   │   │   ├── res
   │   │   │   ├── layout
   │   │   │   │   ├── activity_main.xml # Layout da tela principal
   │   │   │   └── values
   │   │   │       ├── strings.xml # Strings usadas no app
   │   │   │       ├── colors.xml # Cores definidas no projeto
   └── build.gradle # Configuração do Gradle
```

## Design e Prototipage
A interface do app foi criada usando ConstraintLayout no modelo Design para ser mais simples e facil de se usar e para ser mais compacto ao android e mais simples e pratico assim podendo se acostumar com o tempo.

## Telas do Aplicativo 

> Tela Principal

![image](https://github.com/user-attachments/assets/2ea387e4-6bba-4816-a8d7-ac6a0ad01d5b)

Uma tela simples,  5 CheckBox para serem selecionados com o nome do produto e o valor dele, um Button para o processo de calculo ser afetuado de maneira como o usuário queira e um TextView para o usuario poder entender o que será feito (Este pode ser opicional ao gosto de quem querer colocar em sua copia do app), não será necessário o TextView para mostrar o resultado pois ele será alertado por um AlertDialog que mostrara o resultado por uma caixa de mensagem atrávez do botão.

## Desenvolvedores
**Gabriel Henrique** - Desenvolvedor - [GitHub](https://github.com/Hacker19991).

## Licença
Este projeto está licenciado sob os termos da licença MIT. Para mais detalhes, veja o arquivo
[LICENSE](LICENSE).
