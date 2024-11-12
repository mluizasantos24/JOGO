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
-nome:João Guilherme R. Quaresma erros: Erros: falta do `__init__`, ausência de `self` nos métodos, uso incorreto de chaves no `print`, lógica condicional mal posicionada nos métodos `imprimir` e `parar_impressao`, erro de formatação no método `digitalizar` e chamadas incorretas dos métodos na instância.

Sofia:
(f'{self.nome}...') que não estava no print
parar_impressao e digitalizar que não tem ()
falta de else quando self.imprimindo foi True

-nome:anabel erros:imprimir linha 6,falta o 'f' no print, falta de return, depois da linha 16 falta o self true, comando repetido na linha 31, a classe esta com letra maiúscula e o nome da classe ta minúscula, linha 24 em vez de imprimir está 'imprime'.

danilo miranda
erros: tá faltando o return, tá faltando o f no print, tá faltando o init, a class impressora está escrita com I minusculo, na def está faltando o self, o espaçamento,  o Dell no final está errado
 
-nome:Taciana.erros: Erros: falta do `__init__`, ausência de `self` nos métodos, 'Dell' deveria ser 'self', a class impressora deveria ter o 'I' Maiúsculo (Class Impressora), espaçamento incorreto de '=', falta do return, falta do f' antes dos prints.

Escreva o seu nome e liste os erros logo a baixo: 
-nome:murilin08 erros: falta o init no comeco, ta faltando return, class nao ta com letra maiuscula, ta sem formatacao, no comeco ta faltando o espaco, no final ta com igual,falta self ,commit

-nome: Danilo
Erros: Falta o init, faltando o self nos metodos, a logica tá errada no metodo de imprimir e tambem no parar_impressao, o print ta sendo usado errado, a formatação ta errada no digitalizar e ta chamando os metodos de instância errado

Nome: Geovana
erros: Faltando o _init_, falta o f' antes dos prints, falta do self, falta do return, 'Dell', espaçamento errado nos =, class deveria ter letra maiuscula

