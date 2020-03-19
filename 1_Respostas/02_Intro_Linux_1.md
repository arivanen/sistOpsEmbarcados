1. Por que o Linux recebeu esse nome?
Devido ao seu criador Linus Torvalds.

2. O que são daemons?
São usuários criados por demanda para controlar processos que podem eventualmente ser parados por outros usuários.

3. O que é o shell?
O shell é o intermediário entre o usuário e o sistema operacial, sendo esta ligação as linhas de comando.

4. Por que é importante evitar executar o terminal como super-usuário?
Comandos como super-usuário podem deixar o sistema operacional desprotegido além de pode prejudicar a funcionalidade do mesmo.

5. Qual botão do teclado completa o que o usuário escreve no terminal, de acordo com o contexto?
Tab.

6. Quais botões do teclado apresentam instruções escritas anteriormente?
As setas para cima e para baixo.

7. Apresente os respectivos comandos no terminal para: 
(a) Obter mais informações sobre um comando.
man

(b) Apresentar uma lista com os arquivos dentro de uma pasta. 
ls

(c) Apresentar o caminho completo da pasta.
pwd

(d) Trocar de pasta. 
cd

(e) Criar uma pasta.
mkdir

(f) Apagar arquivos definitivamente. 
rm

(g) Apagar pastas definitivamente. 
rm -r

(h) Copiar arquivos.
cp
(i) Copiar pastas.
cp -R /pasta1 /pasta2
"pasta1" pasta origem
"pasta2" pasta onde os arquivos serão copiados

(j) Mover arquivos. 
mv

(k) Mover pastas.
mv

(l) Renomear pastas.
mv para o mesmo diretório

(m) Apresentar o conteúdo de um arquivo.
cat

(n) Apresentar o tipo de um arquivo. 
file

(o) Limpar a tela do terminal. 
clear

(p) Encontrar ocorrências de palavras-chave em um arquivo-texto.
grep

(q) Ordenar informações em um arquivo-texto. 
sort

(r) Substituir ocorrências de palavras-chave em um arquivo-texto. 
sed -i 's/original/nova/g'
"-i" - in-place (define as alterações no arquivo. Se usar um sufixo, cria um backup)
"s" - substituição
"original" - a palavra a ser substituída
"nova" - a nova palavra que vai substituir a antiga
"g"- global (todo arquivo)
"arquivo" - nome do arquivo

(s) Conferir se dois arquivos são iguais. 
cmp

(t) Escrever algo na tela. echo

