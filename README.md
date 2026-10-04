# Editor de Nós

Editor visual de nós com conexões elétricas. O HTML enviado foi preservado integralmente; a única adição na interface é o botão animado **Copiar HTML**.

## Publicar na Vercel

Importe este repositório em **Add New → Project**. O arquivo `vercel.json` configura um site estático sem build e sem dependências. Não são necessárias variáveis de ambiente.

## Usar

- Arraste os cartões para reorganizar o fluxo.
- Conecte cada saída à entrada do mesmo tipo no Processamento.
- Use **Executar** depois de conectar as três entradas.
- Use **Limpar conexões**, **Reorganizar** e a semente de ruído como no original.
- Clique em **Copiar HTML** para copiar todo o `index.html`, incluindo CSS, JavaScript e o próprio botão. Salve o conteúdo em um arquivo `.html` para reutilizar o app.

O processamento é a simulação visual presente no HTML original. Não há integração com geração de imagens, API ou banco de dados. As fontes usam Google Fonts, com fontes locais de reserva.

O botão de cópia deve ser usado pelo endereço publicado ou por um servidor local; abrir diretamente um arquivo com `file://` impede a leitura do código-fonte pelo navegador.
