```python
if player == maq_escolha:
  print('Empate')
elif player == 'pedra' and maq_escolha == 'papel' or player == 'tesoura' and maq_escolha == 'pedra' or player == 'papel' and maq_escolha == 'tesoura':
  print('A máquina venceu!')
else:
  print('O jogador venceu!')
```
