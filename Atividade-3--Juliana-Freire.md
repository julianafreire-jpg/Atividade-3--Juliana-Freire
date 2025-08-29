# Atividade-3--Juliana-Freire


```pynthon

numero_fixo= 7
tentativa= 3

guess= int(input("Digite um número: "))

if guess == 7:
    print("Parabéns, você acertou!")

while guess != numero_fixo:
  tentativa-=1
  print(f"Você tem {tentativa +1} chances restantes")
  guess= int(input("Digite um número: "))
    
  if guess == 7:
    print("Parabéns, você acertou!")
    break
  elif guess < numero_fixo:
    print("O número é maior")
  else:
    print("O número é menor")

  if tentativa == 0:
    print("Você esgotou suas tentativas. Tente novamente.")
    break
´´´
