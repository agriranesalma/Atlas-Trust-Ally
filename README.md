# 🇲🇦 Atlas Trust  
### Souks + Taxis → Get the Fair Price  

---

## 🌟 Overview  

**Atlas Trust** is an AI-powered assistant that helps users avoid overpaying in Morocco, specifically in:  

- 🛍️ Souks (markets)  
- 🚕 Taxis  

It combines **computer vision, geolocation, and transparent pricing logic** to give users real-time, fair price estimates.  

💡 Built to protect locals and tourists from overpricing — while promoting fair, transparent commerce.  

---

## 🚀 Features  

### 🛍️ Souk Ally (AI Price Checker)  
- 📸 Take a photo of an item  
- 🤖 AI detects the product (TensorFlow Lite model)  
- 💰 Compares with real market price ranges  
- 🧠 Gives negotiation advice in real time  
- 💬 Suggests phrases to bargain  

---

### 🚕 Taxi Ally (Smart Fare Calculator)  
- 📍 Select or click departure & destination on map  
- 🗺️ Interactive map powered by Folium  
- 📏 Distance calculation using Haversine formula  
- 💸 Fair price estimation based on real taxi logic  
- 🌙 Night surcharge detection (+30%)  
- ✈️ Airport trip detection (special pricing logic)  

---

### 🔍 Transparent AI (Explainability)  
- No black-box pricing  
- Full breakdown of fare calculation  
- Clear logic users can understand and trust  

---

### 🔐 Privacy First  
- ❌ No personal data stored  
- 📷 Images processed locally and discarded  
- ❤️ Built with user trust in mind  

---

## 🧱 Tech Stack  

- **Frontend / App:** Streamlit  
- **Language:** Python  
- **AI Model:** TensorFlow Lite  
- **Image Processing:** PIL (Pillow), NumPy  
- **Maps & Geolocation:** Folium + streamlit-folium  
- **Data Handling:** Pandas  
- **Math / Distance:** Haversine formula  

---

## 🎯 How It Works  

### 🛍️ Souk Flow  
1. User takes a photo of an item  
2. AI predicts the item category  
3. User enters asked price  
4. App compares with real price range  

**Output:**  
- ✅ Fair price  
- ⚠️ Slightly high  
- ❌ Overpriced + negotiation tip  

---

### 🚕 Taxi Flow  
1. User selects or clicks two locations  
2. App calculates distance  
3. Applies local taxi pricing rules  
4. Adjusts for:  
   - 🌙 Night pricing  
   - ✈️ Airport trips  

**Output:**  
- Fair price estimate  
- Overpricing warning  
- Potential savings  

---

## 🌍 Real-World Impact  

Atlas Trust solves a real, everyday problem:  

- 💸 Protects users from unfair pricing  
- 🤝 Encourages honest trade  
- 🌍 Improves tourism experience in Morocco  
- 🧠 Educates users on local pricing norms  

---

## 👨‍💻 Author  

**Salma Agrirane**  
AI & Big Data Engineering Student

---

## 🏁 Final Note  

> “Trust the price. Trust the journey. Trust Atlas.”  
