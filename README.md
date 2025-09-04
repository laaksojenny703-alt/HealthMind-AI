# HealthMind-AI
Mitt projekt heter HealthMind AI och är en app som använder AI för att tidigt upptäcka tecken på stress och psykisk ohälsa. Genom att analysera språk, sömn- och aktivitetsmönster kan appen ge personliga insikter och rekommendationer. Målet är att människor ska förstå sina signaler i tid, minska lidande och avlasta vården.
Building AI course project"



## Din idé i ett nötskal
HealthMind-AI är ett AI-baserat verktyg som automatiskt tolkar laboratorievärden (t.ex. eGFR, P-Urea) och ger patienter och vårdpersonal lättförståeliga förklaringar samt riskbedömningar.

## Bakgrund
Många människor har svårt att förstå sina laboratorieresultat, vilket kan leda till oro eller att viktiga problem missas. Njursjukdom är vanligt – enligt internationella studier påverkas cirka 10 % av världens befolkning av någon grad av kronisk njursjukdom. Min personliga motivation är att öka patienters förståelse för sin egen hälsa och ge vårdpersonal ett verktyg för snabbare tolkning. Detta ämne är viktigt eftersom tidig insikt i laboratorievärden kan förebygga komplikationer och förbättra vården.

## Data- och AI-tekniker
- **Datakällor:** Offentliga dataset om laboratorievärden och njursjukdom; syntetiska dataset för träning av modeller utan att kompromettera patientsekretess.
- **AI-tekniker:** Maskininlärning (regression och klassificering) för risknivåer; NLP för att generera textförklaringar; eventuell webbaserad prototyp med Python och Streamlit/Gradio.
- **Demo:** Input: `eGFR = 18, P-Urea = 11,2`. Output: “Din njurfunktion är kraftigt nedsatt. Kontakta läkare för uppföljning.”

## Hur används den
- **Användare:** patienter som vill förstå sina laboratorieresultat; vårdpersonal som vill ha snabb tolkning.
- **Sammanhang:** Hem- eller klinikbaserad hälsoundersökning.
- **Påverkade personer:** Patienten får bättre insikt; vårdpersonal kan prioritera riskpatienter.

## Utmaningar
- AI:n ersätter inte läkare – endast stöd och tolkning.
- Resultaten är begränsade till de laboratorievärden som matas in och kan påverkas av felaktiga data.
- Etiska frågor kring patientdata och sekretess måste alltid hanteras korrekt.

## Vad händer härnäst
- Utveckla en mer avancerad prototyp med fler laboratorievärden och patientparametrar.
- Implementera visualiseringar över tid och varningar för snabba förändringar.
- Integrera med journal- och hälsosystem för real-time övervakning.

## Bekräftelser
- Om öppen källkod används (t.ex. Python-bibliotek som scikit-learn, pandas, Streamlit), anges tydlig kredit.
- Inspirationskällor inkluderar AI-lösningar för medicinsk analys, open-source medicinska dataset och tidigare projekt inom patientinformation.


