class Carro:
    def __init__(self):
        self.nome = "Cobalt"
        self.marca = "Chevrolet"
        self.idade = "9"
        self.cor_carro = "Cinza"

    def acelerar(self):
        return f"O carro {self.nome} está acelerando."

    def frear(self):
        return f"O carro {self.nome} está freando."

meu_carro = Carro()
print(meu_carro.acelerar())
print(meu_carro.frear())
