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
-nome: erros:
