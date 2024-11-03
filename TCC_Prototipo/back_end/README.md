# Procedimentos para ativar o backend

## Procedimentos de Instalação de Dependências


1. Instalar no terminal o fastapi em um ambiente virtual pipenv com servidor ASGI Uvicorn
```
pipenv install fastapi uvicorn
```

2. Execute no terminal o pipenv shell para ativar seu ambiente
```
pipenv shell
```

3. No terminal instale o pacote request
```
python -m pip install requests
```

4. No terminal instale os seguintes módulos
```
pip install pandas

pip install matplotlib

pip install scikit-learn
```


## Como executar o projeto

1. Clonar repositório
2. Entrar na pasta /Tcc-Manchester/TCC_Prototipo/back_end
3. Execute o servidor no terminal
```
uvicorn prot_random_forest:app
```
4. Na Web acesse o documento gerado http://localhost:8000/docs

# Autor

Marcelo Nobre de Morais
