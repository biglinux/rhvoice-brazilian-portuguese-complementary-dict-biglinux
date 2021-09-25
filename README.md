# rhvoice-brazilian-portuguese-complementary-dict-biglinux


Ajude a melhorar o leitor de textos, adicione mais palavras nos dicionários, basta abrir um dos arquivos ou criar um novo arquivo na pasta /usr/share/RHVoice/languages/Brazilian-Portuguese/userdict/src/ e inserir as pronúncias das palavras.

Por exemplo:

UNB/i
OMS/i
KDE/i
DNER=deeniéerri
USP=úspi
mosca=môsca
bexiga=bechiga
driver=dráiver
git=guíti

A palavra recebida fica antes do = e a forma de pronunciar depois do =

Não pode utilizar espaço em branco

Quando se insere /i significa que é para soletrar

Com o RHVoice instalado e também a voz Letícia-F123 recomendo testar no terminal com o comando:

echo 'Frase a ser testada' | spd-say --wait -e -o rhvoice -y Letícia-F123

Basta trocar aonde está escrito 'Frase a ser testada' pela frase ou palavra que você desejar.
