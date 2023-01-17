## Configurações iniciais

Primeiro devemos criar o ambiente virtual:

```python
# Criar
	# Linux
		python3 -m venv venv
	# Windows
		python -m venv venv
```

Após a criação do venv vamos ativa-lo:

# Ativar
	# Linux
		source venv/bin/activate
	# Windows
		venv\Scripts\Activate

# Caso algum comando retorne um erro de permissão execute o código e tente novamente:

Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned

Agora vamos fazer a instalação do Django e as demais bibliotecas:

```python
pip install django
pip install pillow
```

Vamos criar o nosso projeto em Django:

```python
django-admin startproject adote .
```