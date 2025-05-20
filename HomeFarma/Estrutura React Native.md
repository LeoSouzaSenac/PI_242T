## 📱 **📁 Estrutura Sugerida para React Native (fácil e organizada)**

my-app/
│
├── assets/                # Imagens, ícones, fontes, etc.
│
├── src/
│   ├── components/        # Componentes reutilizáveis (ex: Button, Card, Header)
│   ├── screens/           # Telas principais (ex: Home, Login, Profile)
│   ├── layouts/           # Estruturas de layout (ex: com header fixo, bottom tab)
│   ├── navigation/        # Configuração de rotas (React Navigation)
│   ├── services/          # APIs ou chamadas externas (ex: axios, firebase)
│   ├── hooks/             # Hooks personalizados (ex: useAuth, useKeyboard)
│   ├── contexts/          # Contextos globais (ex: AuthContext, ThemeContext)
│   ├── utils/             # Funções auxiliares (ex: formatadores, máscaras)
│   ├── styles/            # Temas, cores, tipografia global, styled-components
│   └── AppNavigator.js    # Centraliza a navegação principal
│
├── App.js                 # Ponto de entrada da aplicação
├── app.json               # Configurações do app (Expo)
├── package.json
├── .gitignore
└── README.md
```

---

## ✅ Por que essa estrutura é ótima para React Native?

| Pasta        | Utilidade                                                   |
| ------------ | ----------------------------------------------------------- |
| `components` | Componentes reutilizáveis (botões, cards, cabeçalhos, etc.) |
| `screens`    | Cada tela do app (como páginas em apps web)                 |
| `layouts`    | Estrutura de layout padrão com header, footer, tabs, etc.   |
| `navigation` | Navegação com React Navigation (stack, tabs, drawer, etc.)  |
| `services`   | Conexões com APIs externas, Firebase, etc.                  |
| `contexts`   | Estados globais com Context API (ex: autenticação, tema)    |
| `hooks`      | Lógica reutilizável para comportamento da aplicação         |
| `utils`      | Funções úteis para formatação, validação, etc.              |
| `styles`     | Temas globais, paleta de cores, fontes, spacing             |
| `App.js`     | Arquivo principal onde inicia o `NavigationContainer`       |




