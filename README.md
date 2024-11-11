# JOGO
class Impressora:
    def (self,nome, imprimindo=False):
        self.nome= nome
        self.imprimindo=imprimindo
    def imprimir(self):
        if self.imprimindo:
            print(f'{self.nome} está imprimindo...')
            return
        
        print(f'{self.nome} já está imprimindo...')
        self.imprimindo=True
        
    def parar_impressao(self):
        if not self.imprimindo:
            print(f'{self.nome} não está imprimindo...')
        return
        
        print(f'{self.nome}está parando a impressão...')
        self.imprimindo= False
        
    def digitalizar(self):
        if self.imprimindo:
            print(f'{self.nome} não pode digitalizar enquanto imprime...')
            return
        print(f'{self.nome} está digitalizando...')

im1 = Impressora('Dell')
im2 = Impressora('Canon')
      
im1.imprimir()
im1.imprimir()
im1.digitalizar()
im1.parar_impressao()
im1.digitalizar()

print()

im2.escanear()
im2.imprimir()
im2.imprimir()
im2.escanear()
im2.parar_impressao()
im2.escanear()
