<img width="800" height="240" alt="ficha-animada" src="https://github.com/user-attachments/assets/6dc9e45e-2d91-4866-8430-01ec18652bc3" />!<svg xmlns="http://www.w3.org/2000/svg" width="800" height="240" viewBox="0 0 800 240" role="img" aria-label="Ficha técnica: Alexsandra Moura, Product Designer UI/UX e IA Aplicada, do produto têxtil ao produto digital">
  <defs>
    <pattern id="grade" width="20" height="20" patternUnits="userSpaceOnUse">
      <path d="M20 0H0V20" fill="none" stroke="#E3DFE7" stroke-width="1"/>
    </pattern>

    <!-- Revela a costura da esquerda para a direita -->
    <mask id="revela-costura" maskUnits="userSpaceOnUse" x="0" y="50" width="800" height="24">
      <line x1="40" y1="62" x2="760" y2="62" stroke="#fff" stroke-width="6"
            stroke-dasharray="720" stroke-dashoffset="0">
        <animate attributeName="stroke-dashoffset" values="720;0" dur="1.2s" fill="freeze"/>
      </line>
    </mask>

    <!-- Efeito de digitação: valor-base = largura final (render estático mostra tudo) -->
    <clipPath id="c1"><rect x="40" y="88" height="50" width="420">
      <animate attributeName="width" values="0;0;420" keyTimes="0;0.33;1" dur="1.8s" fill="freeze"/>
    </rect></clipPath>
    <clipPath id="c2"><rect x="40" y="140" height="28" width="470">
      <animate attributeName="width" values="0;0;470" keyTimes="0;0.625;1" dur="3.2s" fill="freeze"/>
    </rect></clipPath>
    <clipPath id="c3"><rect x="40" y="176" height="24" width="380">
      <animate attributeName="width" values="0;0;380" keyTimes="0;0.708;1" dur="4.8s" fill="freeze"/>
    </rect></clipPath>
  </defs>

  <!-- Fundo -->
  <rect width="800" height="240" rx="12" fill="#F7F6F9"/>
  <rect width="800" height="240" rx="12" fill="url(#grade)"/>
  <rect x="0.5" y="0.5" width="799" height="239" rx="12" fill="none" stroke="#D9D3DF"/>

  <!-- Cabeçalho -->
  <g font-family="ui-monospace, SFMono-Regular, Menlo, Consolas, 'Liberation Mono', monospace">
    <text x="40" y="44" font-size="14" font-weight="700" letter-spacing="3" fill="#7E459B">FICHA TÉCNICA</text>
    <text x="760" y="44" font-size="12" letter-spacing="2" fill="#8A8191" text-anchor="end">REF. AM-2026</text>
  </g>

  <!-- Costura -->
  <g mask="url(#revela-costura)">
    <line x1="40" y1="62" x2="760" y2="62" stroke="#7E459B" stroke-width="2"
          stroke-dasharray="8 6" stroke-linecap="round"/>
  </g>
  <!-- Agulha -->
  <circle cx="760" cy="62" r="4" fill="#7E459B" opacity="0">
    <animate attributeName="cx" values="40;760" dur="1.2s" fill="freeze"/>
    <animate attributeName="opacity" values="1;1;0" keyTimes="0;0.85;1" dur="1.4s" fill="freeze"/>
  </circle>

  <!-- Linhas digitadas (textLength fixa a largura em qualquer fonte) -->
  <g font-family="ui-monospace, SFMono-Regular, Menlo, Consolas, 'Liberation Mono', monospace">
    <text x="40" y="128" font-size="38" font-weight="700" fill="#1D1424"
          textLength="400" lengthAdjust="spacingAndGlyphs" clip-path="url(#c1)">Alexsandra Moura</text>
    <text x="40" y="162" font-size="20" fill="#1D1424"
          textLength="456" lengthAdjust="spacingAndGlyphs" clip-path="url(#c2)">Product Designer · UI/UX · IA Aplicada</text>
    <text x="40" y="194" font-size="16" fill="#7E459B"
          textLength="370" lengthAdjust="spacingAndGlyphs" clip-path="url(#c3)">do produto têxtil ao produto digital</text>
  </g>

  <!-- Cursor -->
  <rect x="420" y="180" width="9" height="18" fill="#7E459B">
    <animate attributeName="x" values="40;40;416" keyTimes="0;0.708;1" dur="4.8s" fill="freeze"/>
    <animate attributeName="opacity" values="1;1;0;0" keyTimes="0;0.5;0.5;1" dur="1s" repeatCount="indefinite"/>
  </rect>

  <!-- Fita métrica -->
  <g stroke="#B9B0C2" stroke-width="1">
    <line x1="40" y1="222" x2="760" y2="222"/>
    <path d="M40 222v-8M90 222v-8M140 222v-8M190 222v-8M240 222v-8M290 222v-8M340 222v-8M390 222v-8M440 222v-8M490 222v-8M540 222v-8M590 222v-8M640 222v-8M690 222v-8M740 222v-8"/>
    <path d="M50 222v-4M60 222v-4M70 222v-4M80 222v-4M100 222v-4M110 222v-4M120 222v-4M130 222v-4M150 222v-4M160 222v-4M170 222v-4M180 222v-4M200 222v-4M210 222v-4M220 222v-4M230 222v-4M250 222v-4M260 222v-4M270 222v-4M280 222v-4M300 222v-4M310 222v-4M320 222v-4M330 222v-4M350 222v-4M360 222v-4M370 222v-4M380 222v-4M400 222v-4M410 222v-4M420 222v-4M430 222v-4M450 222v-4M460 222v-4M470 222v-4M480 222v-4M500 222v-4M510 222v-4M520 222v-4M530 222v-4M550 222v-4M560 222v-4M570 222v-4M580 222v-4M600 222v-4M610 222v-4M620 222v-4M630 222v-4M650 222v-4M660 222v-4M670 222v-4M680 222v-4M700 222v-4M710 222v-4M720 222v-4M730 222v-4M750 222v-4"/>
  </g>

</svg>
[Uploading ficha-animada.svg…]()

<pre>
Busco ......... Vaga Jr em Product Design
Base .......... São Paulo, SP
Idiomas ....... Português (nativo) · Inglês (C1)


PROJETO FINAL ──────────────────────────────────────────

<a href="https://elasmapeiam.vercel.app">ElasMapeiam</a> ... Mapa colaborativo de bicicletários em SP
                mostra se o lugar ainda funciona e quando
                isso foi confirmado pela última vez
Pesquisa ...... 144 respostas de ciclistas de SP
                47% já deixaram de ir a algum lugar por
                não saber onde deixar a bike
IA ............ Gemini extrai critérios e tira dados
                pessoais do relato · moderação humana
Stack ......... TanStack Start · Supabase · Leaflet · Vercel
Código ........ <a href="https://github.com/alexsamn/elasmapeiam">github.com/alexsamn/elasmapeiam</a>


HACKATHONS ─────────────────────────────────────────────

Repô .......... Vencedor · Challenge da Reprograma · nov/2026
                IA "bibliotecária" para alunas da Reprograma

Rede Semente .. 1º lugar · WoHackers · ago/2026
                Fundo comunitário em blockchain para
                microempreendedoras comprarem equipamento

<a href="https://selo-raiz.vercel.app">Selo Raiz</a> ..... Festival Compartilhe · ARTIGO 19 + EFF
                Reputação de vendedora que viaja entre
                marketplaces, com consentimento (LGPD)

<a href="https://garimpaai-mvp.replit.app">Garimp.AI</a> ..... Techstars Startup Weekend IA · direção do time
                Agente de IA que conecta artistas
                e colecionadores


ORIGEM ─────────────────────────────────────────────────

10+ anos ...... Desenvolvimento de produto têxtil
Liderei ....... Linha Bike/Ciclismo da Lupo (via L'atelier)
                do conceito à ficha técnica e prova de modelagem
Na prática .... ficha técnica  →  spec de produto
                amostra        →  protótipo
                prova de peça  →  teste com usuário
                fábrica        →  handoff para dev


FORMAÇÃO ───────────────────────────────────────────────

Design de Moda ........ Senac
Análise e Desenv. ..... FIAP
UX .................... Menina de UX (bootcamp)
IA Aplicada ........... Todas em Tech · Reprograma (2026)
Em curso .............. Product Design · Design Circuit


EM ANDAMENTO ───────────────────────────────────────────

01 ............ ElasMapeiam
                validação da IA com 3 avaliadoras e
                teste com ciclistas

02 ............ Repô
                do protótipo vencedor ao app real


NO AR ──────────────────────────────────────────────────

<a href="https://arquivos-de-ux.vercel.app">Arquivos de UX</a>  Glossário de Product Design · 164 termos
                Next.js · Supabase · Vercel

<a href="https://github.com/alexsamn/reprograma-ia-aplicada">Reprograma</a> .... 13 entregas do curso IA Aplicada
                (9 individuais · 4 em grupo)

<a href="https://momotaro.store">Momotaro</a> ...... Loja de roupa de ciclismo · Shopify


FERRAMENTAS ────────────────────────────────────────────

Processo ...... Pesquisa · Wireframe · Protótipo · Teste
Design ........ Figma · Illustrator · Photoshop
Código ........ HTML · CSS · JavaScript · TypeScript
Vibe coding ... Claude Code · Lovable · Supabase · Vercel
Automação ..... Make · agentes com LLM
Web ........... Shopify
IA ............ Claude · ChatGPT · Gemini · FLORA


FORA DO TRABALHO ───────────────────────────────────────

Nasci em ...... Goiânia
Morei no ...... Japão
Pedalo com .... Vespas Bike Gang
Mora comigo ... Mika (a gata da fita métrica)


CONTATO ────────────────────────────────────────────────

Portfólio ..... <a href="https://alexsandramoura.com.br">alexsandramoura.com.br</a>
LinkedIn ...... <a href="https://www.linkedin.com/in/alexsandramoura">in/alexsandramoura</a>
E-mail ........ <a href="mailto:SEU-EMAIL">SEU-EMAIL</a>
</pre>
