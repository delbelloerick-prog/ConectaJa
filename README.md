# 📱 ConectaJá - PWA de Serviços de Tupã (SP)

**ConectaJá** é um Progressive Web App (PWA) moderno e interativo no modelo de marketplace de serviços (como GetNinjas), desenvolvido especialmente para a cidade e região de **Tupã - SP**. O aplicativo conecta clientes locais a profissionais autônomos e prestadores verificados.

---

## 📲 Escaneie para Acessar no Celular

<div align="center">
  <img src="./qrcode.svg" width="260" alt="QR Code ConectaJá" />
  <p>
    <b>Aponte a câmera do seu celular para o QR Code acima</b><br>
    ou acesse diretamente pelo link:<br>
    <a href="https://delbelloerick-prog.github.io/ConectaJa/"><b>👉 https://delbelloerick-prog.github.io/ConectaJa/</b></a>
  </p>
</div>

---

## ✨ Funcionalidades Principais

### 👤 Modo Cliente
* **Exploração por Categorias:** Reformas e construção, Casa e limpeza, Reparos, Automotivo, Aulas e reforço, Beleza e bem-estar, Eventos, Fretes e mudanças, Pet e animais.
* **Busca e Filtros Inteligentes:** Ordenação por *Mais perto*, *Melhor nota* e *Menor preço*.
* **Perfil do Profissional:** Detalhes de serviços oferecidos, endereço em Tupã, avaliações e estimativa de valores.
* **Solicitação de Orçamentos:** Envio de pedidos rápidos para até 3 profissionais qualificados.
* **Chat Integrado:** Conversas em tempo real com respostas simuladas rápidas no estilo WhatsApp.
* **Pagamento Protegido:** Valor retido até a confirmação do serviço executado.
* **Assistente Virtual com IA:** Central de ajuda para tirar dúvidas sobre o funcionamento do app e garantia.

### 🛠️ Modo Prestador
* **Feed de Pedidos:** Acesso a novas demandas de clientes em bairros de Tupã.
* **Verificação de Identidade:** Fluxo de envio de documento (RG/CNH) e selfie para obter o selo de verificado.
* **Gestão de Créditos:** Liberação de contatos de clientes com créditos recarregáveis via Pix.
* **Devolução Automática:** Garantia de devolução de créditos em caso de pedidos falsos ou cancelados.
* **Extrato e Pacotes:** Pacotes Básico, Popular e Profissional com recarga imediata.

---

## 🚀 Recursos PWA (Progressive Web App)

* ✅ **Instalável:** Pode ser adicionado à tela inicial no Android, iOS (iPhone/iPad), Windows e macOS como um aplicativo nativo.
* ✅ **100% Offline-Ready:** O Service Worker faz cache de todos os scripts, fontes e ícones, permitindo uso mesmo sem conexão.
* ✅ **Design Responsivo:** Adaptável tanto para telas móveis quanto para computadores, com visualização centralizada e elegante.
* ✅ **Ícones & Splash Screens:** Ícones adaptativos (maskable) e de alta resolução (192px e 512px) e SVG vetorial.
* ✅ **Zero Dependências Externas em Tempo de Execução:** Fontes locais (Inter) e bibliotecas incluídas no projeto.

---

## 📂 Estrutura do Projeto

```
ConectaJa/
├── index.html              # Aplicação principal PWA
├── manifest.webmanifest    # Manifesto de configuração PWA
├── manifest.json           # Compatibilidade com navegadores legados
├── sw.js                   # Service Worker (estratégia de cache e offline)
├── qrcode.svg              # QR Code vetorial para acesso rápido
├── qrcode.png              # QR Code em PNG
├── .nojekyll               # Configuração para GitHub Pages
├── .gitignore              # Arquivos ignorados pelo Git
├── js/
│   ├── react.production.min.js      # React 18
│   ├── react-dom.production.min.js  # ReactDOM 18
│   └── dc-runtime.js                # Runtime de renderização reativa
├── fonts/
│   └── inter.woff2                  # Fonte Inter offline
└── icons/
    ├── favicon.svg                  # Ícone vetorial
    ├── icon-192.png                 # Ícone padrão 192x192
    ├── icon-512.png                 # Ícone padrão 512x512
    ├── icon-maskable-192.png        # Ícone adaptativo (Android)
    ├── icon-maskable-512.png        # Ícone adaptativo (Android)
    └── apple-touch-icon.png         # Ícone para iOS (Apple)
```

---

## 💻 Como Rodar Localmente

Você pode abrir o projeto diretamente pelo navegador ou subir um servidor estático local:

Com **Node.js**:
```bash
npx serve .
# ou
npx http-server .
```

Com **Python**:
```bash
python -m http.server 8080
```

Acesse em seu navegador: `http://localhost:8080`
