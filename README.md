#Melodia - Página de Apresentação para Streaming de Música
Visão Geral
Melodia é uma página de apresentação (landing page) moderna e vibrante, criada para promover um aplicativo fictício de streaming de música voltado para jovens amantes da música. A página destaca as principais funcionalidades do aplicativo, permite que os usuários ouçam prévias de faixas musicais sem direitos autorais e coleta e-mails para campanhas de marketing. Desenvolvida com HTML, Tailwind CSS e JavaScript, o projeto foca em um design limpo, responsivo e com uma estética divertida, utilizando a fonte Poetsen One e um gradiente dinâmico de roxo para vermelho.

A página funciona como uma ferramenta de marketing para engajar usuários, destacar os benefícios do aplicativo (como áudio de alta fidelidade e playlists personalizadas) e construir uma lista de e-mails para atualizações futuras. Inclui elementos interativos, como prévias de áudio via embeds do SoundCloud e um formulário de inscrição funcional.

Funcionalidades
1. Seção Hero
Propósito: Apresenta o aplicativo Melodia com um título impactante e uma chamada para ação (CTA).
Detalhes:
Título: "Melodia: Sua Música, Sua Forma".
Descrição: Destaca a descoberta de músicas, criação de playlists e qualidade de som excepcional.
CTA: Botão "Ouvir Agora" que leva à seção de download (placeholder).
Estilização: Fundo com gradiente vibrante (#6B46C1 para #E53E3E), texto branco, layout centralizado.
2. Seção Apresentação (Por que escolher o Melodia?)
Propósito: Lista os principais benefícios do aplicativo para atrair usuários.
Detalhes:
Quatro benefícios destacados:
Qualidade de Som Superior: Áudio cristalino para uma experiência imersiva.
Playlists Personalizadas: Criação fácil de playlists baseadas no humor e estilo do usuário.
Descoberta de Artistas: Encontrar novos talentos que combinam com o gosto musical.
Interface Intuitiva: Navegação simples focada na música.
Estilização: Ícones do Font Awesome (volume, lista, estrela, celular), texto roxo (text-purple-600), layout em grade (1 coluna em mobile, 4 em desktop).
3. Seção Funcionalidades
Propósito: Detalha as funcionalidades técnicas do aplicativo.
Detalhes:
Quatro funcionalidades:
Áudio de Alta Fidelidade: Qualidade de estúdio em qualquer lugar.
Playlists Inteligentes: Sugestões automáticas baseadas no gosto musical.
Exploração Musical: Navegação por gêneros e artistas.
Sincronização Offline: Ouvir músicas sem internet.
Estilização: Cards brancos com sombra, ícones roxos, layout em grade (1 coluna em mobile, 2 em tablets, 4 em desktop).
4. Seção Depoimentos
Propósito: Mostra avaliações fictícias de usuários para gerar confiança.
Detalhes:
Três depoimentos:
Ana Clara: Elogia a qualidade do som.
Lucas Mendes: Destaca a descoberta de artistas.
Mariana Souza: Valoriza a organização de playlists.
Estilização: Cards cinza claro, imagens de perfil (placeholders em ./assets/), texto itálico, layout em grade (1 coluna em mobile, 3 em desktop).
5. Seção Prévia Musical
Propósito: Permite que os usuários ouçam prévias de músicas para demonstrar a qualidade do áudio.
Detalhes:
Três faixas royalty-free do SoundCloud:
Dreamland por Jonas Schmidt (ID: 1049492779).
Uebok (Gotta Run) por Apashe (ID: 1102347877).
Happy Life por Fredji (ID: 1016811799).
Implementação: Embeds do SoundCloud via iframes (altura 150px, largura 100%), com controles de reprodução.
Estilização: Cards brancos, ícones de música roxos, títulos e artistas em texto, layout em grade (1 coluna em mobile, 3 em desktop).
Observação: Os iframes reproduzem as faixas completas, não prévias curtas, devido às limitações do SoundCloud.
6. Seção Playlists
Propósito: Apresenta playlists em destaque para inspirar os usuários.
Detalhes:
Quatro playlists fictícias:
Top Hits: Sucessos atuais.
Relax Vibes: Músicas suaves.
Treino Pesado: Faixas energéticas para exercícios.
Flashback 2000s: Hits dos anos 2000.
Estilização: Cards cinza escuro com hover, imagens de capa (placeholders em ./assets/), texto branco, layout em grade (1-4 colunas dependendo do tamanho da tela).
7. Seção Formulário de Contato
Propósito: Coleta e-mails para campanhas de marketing.
Detalhes:
Formulário com campo de e-mail e botão "Enviar".
Funcionalidade via JavaScript:
Validação de e-mail com regex ([^\s@]+@[^\s@]+\.[^\s@]+).
Feedback: Alerta de sucesso ("Obrigado por se inscrever!") ou erro ("Por favor, insira um e-mail válido.").
Simulação de backend: E-mails são registrados no console do navegador.
Limpa o formulário após envio bem-sucedido.
Estilização: Campo transparente com borda branca, botão roxo arredondado, fundo com gradiente, layout centralizado.
8. Rodapé
Propósito: Fornece informações da marca e links adicionais.
Detalhes:
Logo: "Melodia" com slogan "Sua música, sua forma".
Links de redes sociais: Ícones do Facebook, Twitter e Instagram (placeholders).
Links adicionais: Política de Privacidade e Contato (placeholders).
Copyright: "© 2025 Melodia. Todos os direitos reservados."
Estilização: Fundo cinza escuro, texto branco/cinza, layout flexível (coluna em mobile, linha em desktop).
Tecnologias Utilizadas
HTML5: Estrutura da página.
Tailwind CSS (CDN): Estilização responsiva e utilitária.
JavaScript: Lógica do formulário (validação e feedback).
Font Awesome (CDN): Ícones para seções de benefícios, funcionalidades e rodapé.
Google Fonts (Poetsen One): Fonte divertida e moderna usada em toda a página.
SoundCloud Embeds: Iframes para reprodução de músicas na seção Prévia Musical.
Estrutura de Arquivos

melodia/
├── index.html              # Página principal
├── assets/                 # Diretório de recursos
│   ├── anaClara.jpg        # Imagem de perfil do depoimento (placeholder)
│   ├── lucas.jpg           # Imagem de perfil do depoimento (placeholder)
│   ├── mariana.jpg         # Imagem de perfil do depoimento (placeholder)
│   ├── 1-13.png            # Imagem da playlist Top Hits (placeholder)
│   ├── 14-26.png           # Imagem da playlist Relax Vibes (placeholder)
│   ├── 27-39.png           # Imagem da playlist Treino Pesado (placeholder)
│   ├── 40-50.png           # Imagem da playlist Flashback 2000s (placeholder)
└── README.md               # Documentação do projeto
Requisitos
Navegador moderno (Chrome, Firefox, Safari, Edge).
Conexão com a internet para carregar:
Tailwind CSS CDN (https://cdn.tailwindcss.com).
Font Awesome CDN (https://cdnjs.cloudflare.com/...).
Google Fonts (https://fonts.googleapis.com/...).
SoundCloud embeds (https://w.soundcloud.com/...).
Configuração e Instalação
Clonar o Repositório:

git clone https://github.com/seu-usuario/melodia.git
cd melodia
Estrutura de Arquivos:
Coloque as imagens de perfil (anaClara.jpg, lucas.jpg, mariana.jpg) e capas de playlists (1-13.png, 14-26.png, 27-39.png, 40-50.png) no diretório ./assets/.
Observação: As imagens atuais são placeholders. Substitua por arquivos reais ou mantenha os caminhos conforme especificado.
Executar Localmente:
Abra o arquivo index.html diretamente em um navegador:

open index.html  # macOS
start index.html # Windows
Alternativamente, use um servidor local para evitar problemas de CORS:

npx live-server
Hospedagem Online (Opcional):
Faça upload dos arquivos para uma plataforma como Netlify, Vercel ou GitHub Pages.
Certifique-se de incluir o diretório ./assets/ com todas as imagens.
Teste os embeds do SoundCloud e o formulário após o deploy.
Uso
Navegar pela Página:
Acesse as seções via rolagem ou pelo botão "Ouvir Agora" (leva ao #download, atualmente um placeholder).
Explore os benefícios, funcionalidades, depoimentos e playlists.
Ouvir Prévias Musicais:
Na seção Prévia Musical, clique no player do SoundCloud para ouvir:
"Dreamland" por Jonas Schmidt.
"Uebok (Gotta Run)" por Apashe.
"Happy Life" por Fredji.
Observação: Requer conexão com a internet, pois os iframes carregam do SoundCloud.
Inscrever-se no Formulário:
Insira um e-mail válido no formulário da seção Junte-se à Comunidade Melodia.
Clique em "Enviar" para registrar (o e-mail aparece no console do navegador e um alerta confirma o sucesso).
E-mails inválidos geram um alerta de erro.
Observações Importantes
SoundCloud Embeds:
As músicas são embedadas diretamente do SoundCloud, o que garante conformidade com os termos da plataforma.
Limitação: Os iframes reproduzem faixas completas, não prévias curtas (15-30 segundos). Para prévias, seria necessário baixar as faixas, trimá-las e hospedá-las localmente com <audio> tags.
Licenciamento: As faixas são rotuladas como "sem direitos autorais", mas verifique os termos no SoundCloud ou com os artistas (Jonas Schmidt, Apashe, Fredji) para uso comercial.
Formulário:
Atualmente, o formulário simula o envio de e-mails (log no console). Para armazenamento real, integre um backend como:
Firebase Firestore: Para salvar e-mails em um banco NoSQL.
Node.js/Express: Para criar uma API que armazena e-mails.
Mailchimp: Para adicionar e-mails diretamente a uma lista de marketing.
Exemplo de integração com Firebase:

<script src="https://www.gstatic.com/firebasejs/9.6.1/firebase-app.js"></script>
<script src="https://www.gstatic.com/firebasejs/9.6.1/firebase-firestore.js"></script>
<script>
  firebase.initializeApp({ /* sua configuração */ });
  const db = firebase.firestore();
  document.getElementById('email-form').addEventListener('submit', async (e) => {
    e.preventDefault();
    const email = e.target.querySelector('input[name="email"]').value;
    if (!/^[^\s@]+@[^\s@]+\.[^\s@]+$/.test(email)) {
      alert('Por favor, insira um e-mail válido.');
      return;
    }
    await db.collection('subscribers').add({ email, timestamp: new Date() });
    alert('Obrigado por se inscrever!');
    e.target.reset();
  });
</script>
Imagens:
As imagens de perfil e playlists são placeholders. Substitua por arquivos reais em ./assets/ com os mesmos nomes para manter a compatibilidade.
Exemplo: Substitua anaClara.jpg por uma foto real de 80x80px.
Estilização:
A fonte Poetsen One é bold e divertida, mas pode ser pesada para textos longos. Considere combinar com uma fonte secundária (e.g., Roboto) para parágrafos:

p, .text-gray-600 {
  font-family: 'Roboto', sans-serif;
}
Possíveis Melhorias
Prévias de Áudio:
Baixe as faixas do SoundCloud (se permitido), corte para 15-30 segundos e hospede em ./assets/audio/.
Use <audio> tags para controles personalizados:
html

<audio controls class="w-full">
  <source src="./assets/audio/dreamland.mp3" type="audio/mpeg">
  Seu navegador não suporta áudio.
</audio>
Backend para Formulário:
Integre com Firebase, Node.js ou Mailchimp para armazenar e-mails e automatizar campanhas de marketing.
Feedback Visual:
Substitua os alerts do formulário por mensagens estilizadas:

<div id="success-message" class="hidden bg-green-500 text-white p-4 rounded-lg">Inscrição realizada!</div>
<script>
  if (response.ok) {
    document.getElementById('success-message').classList.remove('hidden');
    setTimeout(() => document.getElementById('success-message').classList.add('hidden'), 3000);
  }
</script>
Imagens Reais:
Substitua placeholders por imagens de alta qualidade para depoimentos e playlists.
Analytics:
Adicione Google Analytics para rastrear cliques nos players e envios de formulário:

<iframe ... onplay="ga('send', 'event', 'Audio', 'Play', 'Dreamland')"></iframe>
SEO e Acessibilidade:
Adicione meta tags para SEO:

<meta name="description" content="Melodia: Streaming de música com qualidade de som superior e playlists personalizadas.">
Melhore a acessibilidade com ARIA labels:

<button type="submit" aria-label="Enviar e-mail para inscrição">Enviar</button>
Licenciamento
Código: Licença MIT (padrão para projetos abertos, ajuste conforme necessário).
Músicas:
As faixas são embedadas do SoundCloud e rotuladas como royalty-free. Confirme com os artistas ou SoundCloud para uso comercial.
Links originais:
Dreamland - Jonas Schmidt
Uebok (Gotta Run) - Apashe
Happy Life - Fredji
Fontes e Ícones:
Poetsen One: Licença SIL Open Font (grátis para uso comercial).
Font Awesome: Licença gratuita para ícones usados.
Contribuição
Faça um fork do repositório.
Crie uma branch para sua feature:

git checkout -b minha-feature
Commit suas alterações:

git commit -m "Adiciona minha feature"
Envie para o repositório remoto:

git push origin minha-feature

Integrantes: 
Leonardo Fernandes Mesquita, RM:559623
Marco Antonio Caires Freire, RM:559256
Guilherme Augusto Caseiro, RM:559765
https://github.com/Guiitens2005
https://github.com/leoGitFiap
https://github.com/MACF77

Link do Repositório: https://github.com/leoGitFiap/front_Cp5_2025

Link do GitPages: https://leogitfiap.github.io/front_Cp5_2025/
