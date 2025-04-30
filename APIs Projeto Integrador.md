### 🧠 **1. RelaxMind**
**Objetivo**: Apoiar emocionalmente, sugerir atividades, meditações, frases positivas.

**APIs sugeridas**:
- **BoredAPI** (sem registro) – Sugere atividades relaxantes.  
  🔗 `https://www.boredapi.com/api/activity`
- **Zen Quotes API** (sem registro) – Frases inspiradoras e motivacionais.  
  🔗 `https://zenquotes.io/api/random`
- **OpenAI API** (com registro, plano gratuito com limites) – Pode criar um chatbot de suporte emocional.  
  🔗 `https://platform.openai.com`

---

### 💊 **2. HomeFarma**
**Objetivo**: Organizar doses, lembrar horários, verificar interações.

**APIs sugeridas**:
- **OpenFDA** (sem registro) – Dados da FDA sobre medicamentos (EUA), efeitos colaterais, etc.  
  🔗 `https://api.fda.gov/drug/label.json?search=ibuprofen`
- **RxNorm API – NIH** (registro opcional) – Informações detalhadas sobre medicamentos e interações.  
  🔗 `https://rxnav.nlm.nih.gov/` (tem UI + API REST)
- **Google Calendar API** (com registro) – Pode ser usado para agendar lembretes de uso.  
  🔗 `https://developers.google.com/calendar`

---

### 🔍 **3. Contrata.me**
**Objetivo**: Facilitar o acesso a prestadores de serviços próximos.

**APIs sugeridas**:
- **Google Places API** (com registro, plano gratuito limitado) – Localiza estabelecimentos por categoria (ex: psicólogos, farmácias, dentistas).  
  🔗 `https://developers.google.com/maps/documentation/places/web-service`
- **OpenStreetMap Nominatim** (sem registro, respeitar rate limit) – Geolocalização gratuita e aberta.  
  🔗 `https://nominatim.openstreetmap.org/search?q=clinica+medica+em+Curitiba&format=json`
- **Brasil.io** (sem registro) – Dados públicos úteis como estabelecimentos de saúde (em datasets específicos).  
  🔗 `https://brasil.io`

---

### 🌍 **4. AtlasMundi**
**Objetivo**: Mostrar dados como população, moeda, idiomas, bandeira, etc.

**APIs sugeridas**:
- **REST Countries** (sem registro) – Informações completas e organizadas sobre países.  
  🔗 `https://restcountries.com/v3.1/all`
- **World Bank API** (sem registro) – Indicadores econômicos e sociais de cada país.  
  🔗 `https://api.worldbank.org/v2/country/all/indicator/SP.POP.TOTL?format=json`
- **CountryFlags API** (sem registro) – Bandeiras por país.  
  🔗 `https://countryflagsapi.com/png/br`

---

### ♻️ **5. Recicle+**
**Objetivo**: Incentivar reciclagem com pontos por materiais entregues ou boas práticas.

**APIs sugeridas**:
- **WasteDataFlow (UK) ou dados locais de prefeituras** – Pode-se usar dados abertos sobre reciclagem.  
  🔗 Exemplo: https://dados.gov.br  
- **OpenWeatherMap API** (com chave gratuita) – Saber clima/local ideal para coleta.  
  🔗 `https://openweathermap.org/api`
- **IP Geolocation (ipinfo.io)** (sem registro para uso básico) – Ver localização do usuário para adaptar pontos de coleta.  
  🔗 `https://ipinfo.io/json`

