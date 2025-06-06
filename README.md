# JOGO DA FORCA - VOLUME 2
👨‍💻ESSE É PEQUENO JOGO QUE RODA NO CONSOLE DA IDE.

<img src="FOTO.png" align="center" width="400"> <br>

## DESCRIÇÃO:
Este programa implementa o clássico jogo da forca em Python. Ele carrega uma palavra aleatória de um arquivo chamado "WORD.txt", inicializa uma lista para armazenar as letras acertadas, e pede ao usuário para adivinhar letras até que ele acerte todas as letras ou atinja o número máximo de erros permitidos (7 erros). O jogo exibe mensagens de abertura, vitória ou derrota, desenha uma forca conforme o número de erros e revela a palavra secreta quando o jogador perde. O usuário pode tentar adivinhar letras, e o jogo fornece feedback sobre as letras corretas e o progresso.

## EXECUTANDO O JOGO:
1. Navegue até o diretório `./CODIGO`, e execute o arquivo Python com o comando:
```bash
python CODIGO.py
```
2. O jogo será iniciado e você verá a mensagem de abertura.
3. Uma palavra será escolhida aleatoriamente do arquivo de palavras `WORD.txt`.
4. Você verá uma linha de underscores representando as letras da palavra a ser adivinhada.
5. Você pode digitar uma letra como seu palpite e pressionar Enter.
6. Se a letra estiver correta, ela será exibida na posição correta na palavra.
7. Se a letra estiver incorreta, você verá a parte correspondente do desenho da forca.
8. Você pode continuar adivinhando até que todas as letras sejam reveladas ou até que você erre 7 vezes e seja enforcado.
9. Se adivinhar corretamente todas as letras, você vence.
10. Se cometer 7 erros, você perde e a palavra correta será revelada.
11. O jogo termina e você verá uma mensagem de fim.

## SOBRE O EXECUTAVEL:
### 1. EXECUTANDO:
- Este arquivo executável está disponível no diretório `./APP`. Para executá-lo, basta dar dois cliques. O executável é bastante útil caso o Python não esteja instalado. Trata-se da mesma aplicação do arquivo `CODIGO.py`. Se desejar, você pode recompilá-lo novamente.

### 2. GERANDO:
   **1. Instalação do [PyInstaller:](https://pyinstaller.org/en/stable/)**
   - Certifique-se de ter o PyInstaller instalado. Se não tiver, instale usando o comando abaixo:
   ```bash
   pip install pyinstaller
   ```

   **2. Gerando o Executável**
   - No diretório `./CODIGO`, execute o comando abaixo para gerar o executável a partir do arquivo `.spec`:

   ```bash
   pyinstaller EXECUTAVEL.spec
   ```

   - O arquivo `JOGO DA FORCA 2.exe` será criado dentro da pasta `./CODIGO/dist`.

   - Após a geração, você pode mover o executável para `./APP` e remover as pastas temporárias `./CODIGO/build` e `./CODIGO/dist`.

   - Para executar o aplicativo, basta dar dois cliques no arquivo `.exe`.

## SUBSÍDIO:
* [DOCUMENTAÇÃO OFICIAL DO PYINSTALLER](https://pyinstaller.org/en/stable/)

## NÃO SABE?
- Entendemos que para manipular arquivos em muitas linguagens e tecnologias, é necessário possuir conhecimento nessas áreas. Para auxiliar nesse aprendizado, oferecemos cursos gratuitos disponíveis:
* [CURSO DE PYTHON](https://github.com/VILHALVA/CURSO-DE-PYTHON)
* [CONFIRA MAIS CURSOS](https://github.com/VILHALVA?tab=repositories&q=+topic:CURSO)

## CREDITOS:
- [PROJETO CRIADO PELO VILHALVA](https://github.com/VILHALVA)

