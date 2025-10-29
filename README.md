# jogo-de-dados-poo
# Jogo de Dados

## Levantamento de Requisitos
### Requisitos Funcionais
- O sistema deve permitir que o jogador inicie o jogo.
- O sistema deve permitir que o jogador realize apostas.
- O sistema deve validar as apostas realizadas.
- O sistema deve permitir que o jogador lance os dados.
- O sistema deve calcular o resultado da aposta.
- O sistema deve atualizar o saldo do jogador.
- O sistema deve exibir o resultado da rodada.

### Requisitos Não Funcionais
- Usabilidade: interface simples e intuitiva.
- Aleatoriedade: resultados dos dados devem ser aleatórios.
- Desempenho: cálculos e lançamentos devem ocorrer imediatamente.
- Segurança: impedir que o saldo fique negativo ou ocorra erro de cálculo.

---

## Diagrama de Classes
![Diagrama de Classes](https://github.com/user-attachments/assets/aca8498d-e0bf-4cb5-baf7-7f3eaf81d23a)


---

## Diagrama de Casos de Uso
![Diagrama de Casos de Uso](https://github.com/user-attachments/assets/ffc29e55-fedb-406e-82a6-9bba4e5d4ad4)


---

## Descrição Textual do Diagrama de Casos de Uso
**Ator:** Jogador – usuário que interage com o sistema para jogar, apostar e visualizar resultados.

**Casos de Uso:**
1. **Iniciar Jogo:** jogador inicia uma nova sessão do jogo; o sistema prepara o jogo.  
2. **Realizar Aposta:** jogador escolhe o valor da aposta; o sistema registra para validação.  
3. **Validar Aposta:** sistema verifica se a aposta é válida; se inválida, exibe mensagem de erro.  
4. **Lançar Dados:** jogador executa o lançamento dos dados; o sistema gera números aleatórios.  
5. **Calcular Resultado:** sistema calcula ganho ou perda com base na aposta e no resultado.  
6. **Atualizar Saldo:** sistema atualiza o saldo do jogador de acordo com o resultado.  
7. **Exibir Resultado:** sistema mostra o resultado da rodada e saldo atualizado.

---

## Referências
- [Documentação oficial do GitHub](https://github.com/jucilenesilva719-star/jogo-de-dados-poo.git)
