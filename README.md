# JOGO
Class impressora:
    def (self,nome, imprimindo=False):
        self.nome= nome
        self.imprimindo=imprimindo
    def imprimir:
        if self.imprimindo:
            print('{self.nome} está imprimindo...')
            
        
        print('{self.nome} já está imprimindo...')
        self.imprimindo=True
        
    def parar_impressao:
        if not self.imprimindo:
            print('{self.nome} não está imprimindo...')
        
        
        print('{self.nome}está parando a impressão...')
        self.imprimindo= False
        
    def digitalizar:
        if self.imprimindo:
            print('{self.nome} não pode digitalizar enquanto imprime...')
            
        print('{self.nome} está digitalizando...')

im1 = Impressora('Dell')
      
im1=imprimir()
im1=imprimir()
im1=digitalizar()
im1=parar_impressao()
im1=digitalizar()

print()


Escreva o seu nome e liste os erros logo a baixo: 

-nome: Danilo
Erros: Falta o init, faltando o self nos metodos, a logica tá errada no metodo de imprimir e tambem no parar_impressao, o print ta sendo usado errado, a formatação ta errada no digitalizar e ta chamando os metodos de instância errado


-nome:João Guilherme R. Quaresma erros: Erros: falta do `__init__`, ausência de `self` nos métodos, uso incorreto de chaves no `print`, lógica condicional mal posicionada nos métodos `imprimir` e `parar_impressao`, erro de formatação no método `digitalizar` e chamadas incorretas dos métodos na instância.
