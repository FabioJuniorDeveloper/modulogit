Revertendo Modificações

Quando vc dar um commit, vem junto um código bem grande, mas o que nos interessa é os primeiros 7 dígitos.
O HEAD = indica qual branch a gente está.

Comandos:
- git branch = vai listar todos os branchs do projeto, e a branch que tiver com * é a branch que estamos usando no momento.
-git commit -am "Mensagem" = esse "am" significa adicionar o arquivo ao sistema de monitoramento(fica só na máquina local) do git e fazer um commit(enviar para o sistema do git) em um só comando.
- git reset = ele vai ir para alguma versão anterior do seu projeto.
- git reset -soft = ele vai voltar para ao estado anterior, mas ele volta com os arquivos modificados posteriormente, eles vão estar preparados(ja vão estar com o git add -A) e  também não comitadas, aí eu faço dps o commit novamente.
- git reset -mixed = ele vai voltar para ao estado anterior, mas não vai estar preparado(não esta no sistema de monitoramento do git) para commitar, vai ter que dar o git add -A novamente.
- git reset --hard = Ele vai voltar ao estado anterior, só que os arquivos que criei posteriormente ele vai ignorar tudo, ele vai deletar praticamente, (não é muito recomendado)

