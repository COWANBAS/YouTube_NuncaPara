# SCRIPT

Este userscript é projetado para remover automaticamente a mensagem "Continue assistindo" do YouTube, clicando no botão correspondente assim que ele aparece. O script verifica a presença do botão a cada segundo para garantir que os vídeos continuem sendo reproduzidos sem interrupções.

*Function RemoveContinueWatching*

Define uma função chamada removeContinueWatching que procura pelo botão "Continue assistindo" no YouTube.
const continueButton = document.querySelector('button.ytp-continue-playback-button');: Utiliza querySelector para procurar pelo botão "Continue assistindo" usando a classe do botão.
if (continueButton) { continueButton.click(); }: Se o botão for encontrado, ele é clicado automaticamente para remover a mensagem e continuar a reprodução do vídeo.

*ContinueButton ContinueButton.click*

Se o botão for encontrado, ele é clicado automaticamente para remover a mensagem e continuar a reprodução do vídeo.

![image](https://github.com/user-attachments/assets/99fcff14-f640-491e-a591-30ebd3fb94d2)


*SetInterval*

Define um intervalo que chama a função removeContinueWatching a cada segundo (1000 milissegundos) para garantir que a mensagem seja removida assim que aparecer.

![image](https://github.com/user-attachments/assets/4a71cd2b-83b0-471b-a0d0-30e2cfe2bf3c)
