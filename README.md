# 📦 Modelowanie łukowatości tektury falistej (Streamlit Dashboard)

> **Status projektu:** Zamknięte repozytorium / Case Study (Kod źródłowy zastrzeżony). Wizualizacja interaktywnego panelu analitycznego do kontroli geometrii tektury falistej.

## 🎯 Cel projektu
Opracowanie aplikacji analitycznej w ekosystemie Pythona służącej do bezkontaktowej metrologii łukowatości arkuszy tektury oraz innych metryk na podstawie zdjęć 2D.

## 🛠️ Stack Technologiczny
* **Frontend / Dashboard:** Streamlit (interaktywne widgety, dynamiczne wykresy)
* **Przetwarzanie danych i sygnałów:** `NumPy`,`OpenCV,` `SciPy` (filtracja Savitzky'ego-Golaya, transformacje oparte na cięciach)
* **Wizualizacja:** Matplotlib / Plotly

---

## 📸 Podgląd aplikacji i dopasowania linii (Streamlit UI)

<table>
  <tr>
    <td align="center" width="50%">
      <b>1. Panel główny</b><br><br>
      <img src="./assets/p1.PNG" width="100%" alt="Main">
    </td>
    <td align="center" width="50%">
      <b>2. Manual Cropping</b><br><br>
      <img src="./assets/p7.PNG" width="100%" alt="manual">
    </td>
    <td align="center" width="50%">
      <b>3. Segmentacja stosów przy użyciu modelu grounding dino</b><br><br>
      <img src="./assets/p3.PNG" width="100%" alt="AI segmentation">
    </td>
  </tr>
  <td align="center" width="50%">
      <b>4. Dopasowanie linii do chmury punktów</b><br><br>
      <img src="./assets/p4.PNG" width="100%" alt="Curve">
    </td>
    <td align="center" width="50%">
      <b>5. Stats</b><br><br>
      <img src="./assets/p6.PNG" width="100%" alt="stats">
    </td>
    <td align="center" width="50%">
      <b>6.Stats adv</b><br><br>
      <img src="./assets/p8.PNG" width="100%" alt="statsv2">
    </td>
    
</table>

---

## ⚙️ Kluczowe Funkcjonalności Dashboardu
1. **Automatyczne dopasowanie linii referencyjnej do chmury punktów** .
2. **Opracowanie metryk jakościowych do precyzyjnej oceny i klasyfikacji struktur**. 
3. **Aplikacja posiada 3 tryby: Auto AI, Manual cropping, Live camera**.
4. **Panel konfiguracyjny dla użytkownika po lewej stronie jako pasek boczny**.
5. **Graficzna prezentacja wyników**.