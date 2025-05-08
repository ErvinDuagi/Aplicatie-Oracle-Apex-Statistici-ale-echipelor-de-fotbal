# 🏆 Proiect Oracle APEX - Management Echipe și Meciuri Fotbal

Acest proiect este o aplicație web creată cu Oracle APEX pentru gestionarea echipelor, meciurilor, jucătorilor și statisticilor din cadrul unui campionat de fotbal. 

---

## 🔧 Tehnologii folosite

- **Oracle APEX 24.2.5**
- **Oracle SQL**
- **XCase** – pentru modelul conceptual/logical


---

## 📁 Funcționalități implementate

- 5 tabele relaționate (Echipe, Jucători, Meciuri, Statistici, Antrenori)
- 2 formulare de tip `Form` (ex: Antrenori, Echipe)
- 2 formulare `Master-Detail` (Echipe-Jucători și Meciuri-Statistici)
- 3 rapoarte:
  - Interactive Grid (Jucători)
  - Interactive Report (Meciuri)
  - Classic Report (Echipe)
- 2 grafice:
  - Bar Chart: Goluri per jucător
  - Pie Chart: Distribuția pozițiilor jucătorilor

---

## 📸 Capturi de ecran

### 🧩 Formulare

#### ✅ Master-Detail: Echipe și Jucători
![Form Echipe-Jucători](https://i.imgur.com/EtBXbKN.png)
#### ✅ Master-Detail: Meciuri și Statistici
![Form Meciuri Statistici Master-Detail](https://i.imgur.com/mVDmPYX.png)
#### ✅ Form simplu: Pagina principală - Navigație
![Home Page](https://i.imgur.com/SakcFWy.png)

---

### 📊 Rapoarte

#### 📋 Classic Report - Echipe
![Classic Report Echipe](https://i.imgur.com/gwdHRoK.png)

#### 📋 Interactive Grid - Jucători
![Interactive Grid Jucători](./screenshots/interactive_grid_jucatori.png)

#### 📋 Interactive Report - Meciuri
![Interactive Report Meciuri](./screenshots/interactive_report_meciuri.png)

---

### 📈 Grafice

#### 📊 Bar Chart: Goluri per jucător
![Goluri per jucător](https://i.imgur.com/cJdJntG.png)

#### 🥧 Pie Chart: Distribuția pozițiilor
![Pie Chart Poziții](./screenshots/chart_pie_pozitii.png)

---

## 🧠 Ce am învățat

- Proiectarea unui model relațional coerent folosind XCase
- Utilizarea Oracle APEX pentru a crea aplicații funcționale rapid
- Folosirea relațiilor Master-Detail pentru interfețe dinamice
- Vizualizarea datelor cu grafice și rapoarte interactive
- Gestiunea erorilor frecvente (ex: ORA-01400, ORA-02291)

---

## 📦 Instalare (opțional)

> Dacă ai acces la un mediu Oracle APEX:
1. Creează schema bazei de date folosind scriptul SQL inclus
2. Importă fișierul aplicației APEX (.sql)
3. Rulează aplicația și folosește meniul pentru navigare

---

## 📄 Autor

**Duagi Ervin**  
ICASE, Universitatea Politehnica din București  
[duagiervin@gmail.com](mailto:duagiervin@gmail.com)
