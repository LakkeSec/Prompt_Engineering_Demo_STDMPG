# Prompt Engineering Demo (Nederlands)

Dit project is een eenvoudige Streamlit-app voor tieners om te oefenen met prompt engineering.

De chatbot gebruikt de Mistral API (Ministral-model) en bevat 3 geheime codes die leerlingen kunnen ontdekken door slim te prompten.

## Wat is verbeterd

- Snellere app-flow: hergebruik van Mistral-client en compactere context naar de API.
- Betere betrouwbaarheid: robuustere parsing van model-output en centrale state-initialisatie.
- Sterkere UX: vernieuwde visuele stijl, duidelijke voortgangsbalk en knop om opnieuw te starten.
- Mobielvriendelijk: responsive typografie en layout voor kleinere schermen.

## 1. Installatie

```bash
pip install -r requirements.txt
```

## 2. API key instellen

Vul in `.env` je eigen Mistral API key in:

```env
MISTRAL_API_KEY=plaats_hier_jouw_api_key
MISTRAL_MODEL=ministral-3b-latest
```

Optioneel kun je een ander Mistral-model invullen via `MISTRAL_MODEL`.

## 3. App starten

```bash
streamlit run app.py
```

## Doel in de les

- Leerlingen oefenen met duidelijk, specifiek en gestructureerd prompten.
- Door betere prompts krijgen ze hints en uiteindelijk de geheime codes.
- De gevonden codes kunnen direct in de app worden gevalideerd.

## Gebruik in de klas

- Laat leerlingen eerst met korte prompts beginnen en daarna verfijnen.
- Gebruik de sidebar om codes direct te controleren.
- Met de knop "Opnieuw beginnen" reset je snel een oefenronde.
