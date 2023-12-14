# gerador-de-srt
gerador de srt para audios

Caso queira gerar uma srt para vídeos do youtube, só colocar todos os links dentro da lista **links[]** e rodar o código.

O formato de lista de **links[]** é o seguinte:
```python
links = [
    'https://www.youtube.com/watch?v=xxxxxxxxxxx',
    'https://www.youtube.com/watch?v=xxxxxxxxxxx',
]
```

O código irá gerar um arquivo .srt para cada video/link da lista **links[]**.

O arquivo .srt será gerado com o nome do vídeo, por exemplo: "video1.srt".

Caso queira utilizar o código para gerar srt para audios, só colocar o caminho do audio na variável **path** e rodar o código, lembrando de comentar o seguinte trecho:

```python
links = [
    'https://www.youtube.com/watch?v=xxxxxxxxxxx',
    'https://www.youtube.com/watch?v=xxxxxxxxxxx',
]
for link in links:
    download_youtube_audio(link)
```

de modo que fique assim:

```python
#links = [
#    'https://www.youtube.com/watch?v=xxxxxxxxxxx',
#    'https://www.youtube.com/watch?v=xxxxxxxxxxx',
#]
#for link in links:
#    download_youtube_audio(link)
```
vou deixar este código disponível no meu colab, só clicar no link abaixo:

https://colab.research.google.com/drive/1lgw245SY-gqhja7KfA5YRWLQnupJWGL6?usp=sharing