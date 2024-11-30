# Título: Calculadora IMC - TalentoTech
# Calculadora de IMC

## Objetivo do Projeto
Este projeto tem como objetivo criar uma calculadora de Índice de Massa Corporal (IMC) que permita ao usuário inserir seu peso e altura e, com base nisso, classifique o IMC de acordo com faixas de peso.

## Funcionalidades
- **Entrada de Dados:** O usuário poderá inserir seu peso (em kg) e altura (em metros, com casas decimais).
- **Cálculo do IMC:** A fórmula usada será: IMC = peso / (altura * altura).
- **Classificação:** Exibir a faixa de classificação (Exemplo: Abaixo do peso, Peso normal, Sobrepeso, etc.).
- **Mensagens Personalizadas:** Sugestões com base na classificação obtida.

## Cronograma de Desenvolvimento
| Etapa                     | Descrição                                        | Prazo       |
|---------------------------|--------------------------------------------------|-------------|
| Planejamento              | Definir os requisitos e criar o repositório.     | Dia 1       |
| Interface do Usuário      | Criar uma interface básica para entrada de dados.| Dias 2 a 3  |
| Lógica para Cálculo       | Implementar o cálculo e classificação.           | Dias 4 a 5  |
| Testes                    | Testar diferentes entradas.                      | Dia 6       |
| Documentação              | Revisar e documentar o processo.                 | Dia 7       |

-------------------------------------------------------------------------------------------------------------------

### **2. Uso de Branches**
O projeto será organizado em branches de acordo com a estrutura:

#### **Branches Sugeridas:**
1. **feature/interface**:  
   - Desenvolver a interface ou a entrada de dados no VSCode.  
   - Adicionar campos para peso e altura e um botão (ou comando) para calcular.  

2. **`feature/calcular`**:  
   - Implementar a lógica do cálculo do IMC.  
   - Verificar se as entradas são válidas (teste de exceções, como letras ao invés de números).  

4. **`feature/classificacao`**:  
   - Determinar a classificação do IMC com base no resultado obtido.  
   - Exibir a mensagem correspondente ao valor obtido.  

5. **`feature/documentacao`**:  
   - Melhorar a documentação do projeto, como tutoriais de uso e informações adicionais.  

-------------------------------------------------------------------------------------------------------------------

### **Passos para Criar Branches no Git:**
1. No terminal ou na interface gráfica do Git, use o comando para criar uma branch:  
   ```bash
   git checkout -b feature/interface
