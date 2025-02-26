# Sistema de Gerenciamento de Estoque

PROJETO INTEGRADO INOVAÇÃO - ADS
mport tkinter as tk
janela=tk.Tk()
janela.title('Meu primeiro projeto')
menu_principal=tk.Menu(janela)
menu_principal.add_command(label="Opção 1")
menu_principal.add_command(label="Opção 2")
menu_principal.add_command(label="Sair",command=janela.quit)
janela.config(menu=menu_principal)
janela.mainloop()

