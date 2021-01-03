# Livro de receitas :man_cook:

Olá muito bem vindo ao nosso livro de receitas :wave:
 - Lasanha
#
#
## Navegação via command line interface e instalação
### Anotações referente ao curso Introdução ao Git e ao GitHub ministrado pela **Digital Innovation One**
1. Windowns :control_knobs:
2. Linux :penguin:

### lista diretório
- dir
- ls
### command diretory navega (Windowns | Linux)
- cd
- cd
### limpar tela (Windowns | Linux)
- cls
- clear

### autocompletar (Windowns | Linux)	
- tab
- tab

### Criar diretório (Windowns | Linux)	
- mkdir
- mkdir	

### silence on success
- Ao criar o diretório com mkdir após o comando.

### criar arquivo
- echo hello > hello.txt

### somente deleta arquivos
- del

### deleta diretórios com arquivos
- rmdir /S /Q		usando flags para ficar mais usual
- rm -rf			r de recursivamente
					f de force para não aparecer exigências de confirmações



- SHA1
	- A sigla SHA siginifica secure hash algorithm (Algoritimo de hash seguro), é um conjunto de funções hash criptografadas projetadas pela NSA (Agência de segurança nacional dos EUA)

	- A encriptação gera conjunto de caracteres identificador de 40 dígitos.

	- A cada mundaça do projeto a cada commit usa um SHA1 unico.

	- É uma forma curta de representar um commit.

- Objetos fundamentais
	- Blobs
		- git hash-object --stdin
		- openssl sha1
		- Geram hash diferentes
		- Armazena meta dados, tipo, tamanho string, tamanho arquivos
		- Possuem seus próprios SHA1
		
	- Trees
		- Guarda o nome do arquivo
		- Aponta para o Blobs ou outras arvores
		- Possuem seus próprios SHA1
		
	- Commits
		- Objeto que junta tudo autor comentários, trees, parente, timestamp
		- Possuem seus próprios SHA1
		

- Sistema distribuído seguro
	- Tem a característica de poder ser enviado para nuvens e além de poder ser usados por mais colaboradores, isto é cada colaborador poderá ter a cópia geral dos commits gerados por todos de maneira segura.

### Iniciar o GIT
- git init

### Iniciar o versionamento
- git add

### Criar um Commit
- git commit