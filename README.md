# 🛒 Projeto Lista de Compras - Ciclo de Vida no Angular

Este projeto foi desenvolvido com o objetivo de **aprender e aplicar o ciclo de vida dos componentes no Angular**, explorando seus principais *lifecycle hooks* e sua importância na criação de **aplicações mais rápidas, organizadas e performáticas**.

---

## 🚀 Objetivo do Projeto

Criar uma **lista de compras interativa**, utilizando um **formulário simples** para adicionar, editar e remover itens, enquanto exploramos o comportamento dos principais hooks do ciclo de vida de um componente Angular.

---

## 🧩 Hooks Explorados

Durante o desenvolvimento, focamos nos seguintes hooks:

- **`ngOnInit()`** → Executado uma vez, logo após a inicialização do componente.  
  Utilizado para inicializar dados e configurar o estado inicial da aplicação.

- **`ngOnChanges()`** → Detecta mudanças em propriedades de entrada (`@Input`).  
  Ideal para reagir a atualizações vindas de componentes pais.

- **`ngDoCheck()`** → Chamado a cada verificação de mudanças.  
  Usado para criar verificações personalizadas além do *default change detection* do Angular.

- **`ngOnDestroy()`** → Executado antes de o componente ser destruído.  
  Utilizado para limpeza de subscrições, timers e listeners.

---

## 🧠 Conceitos Abordados

- Lógica de **inicialização** de componentes.
- **Verificação de propriedades de entrada** e reatividade.
- **Monitoramento de alterações** internas do componente.
- **Lógica de limpeza** ao destruir o componente.
- Boas práticas para **melhorar o desempenho** e evitar vazamentos de memória.

---

## 🧰 Tecnologias Utilizadas

- **Angular** (versão utilizada no aprendizado)
- **TypeScript**
- **HTML5 / CSS3**
- **FontAwesome** (ícones de edição e exclusão)
- **Componentização e Data Binding** do Angular

---

## 📝 Funcionalidades

- Adicionar novos itens à lista.  
- Editar e excluir itens.  
- Marcar itens como concluídos.  
- Exibir a data e hora de inclusão.  
- Limpar toda a lista com um clique.  

---

## 💡 Aprendizados

Durante o desenvolvimento, foram compreendidos os seguintes pontos:

- O ciclo de vida do Angular **determina como e quando um componente nasce, se atualiza e é destruído**.  
- Utilizar corretamente os hooks evita **operações desnecessárias**, aumentando a **performance** da aplicação.  
- O uso de `ngOnDestroy` é essencial para garantir **limpeza de recursos** e evitar **memory leaks**.  
- O `ngDoCheck` permite **controle granular sobre detecção de mudanças**, quando necessário.
