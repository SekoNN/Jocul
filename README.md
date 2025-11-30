# Unity 3D AI Chess – Proiect realizat de Gavrilas Nicolae

Acest proiect reprezintă o aplicație desktop 3D de tip **joc de șah cu inteligență artificială**, pe care am dezvoltat-o în cadrul studiului individual. Proiectul este construit în **Unity 3D** și programat în **C#**, folosind concepte de programare orientată pe obiecte, structuri de date și algoritmi AI.

---

## 🧠 Descriere generală

Am realizat un joc de șah 3D complet funcțional, care include:

- tablă și piese 3D animate;
- modul de joc **Om vs Calculator**;
- evidențiere vizuală pentru selecție, mutări posibile și atacuri;
- implementarea situațiilor speciale:
  - **Șah**
  - **Șah Mat**
  - **Pat**
  - **Rocadă**
  - **En Passant**
  - **Promovarea pionului**;
- sistem de **Inteligență Artificială** bazat pe:
  - *Minimax Algorithm*
  - *Alpha-Beta Pruning* pentru optimizare și performanță.

Scopul proiectului a fost dezvoltarea unei aplicații desktop complexe, care îmbină logica avansată a șahului cu o interfață 3D modernă și utilizarea corectă a instrumentelor de versionare (**Git & GitHub**).

---

## ⚙️ Funcționalități implementate de mine

### ♟ Logică de joc
Am implementat regulile complete ale șahului:

- determinarea mutărilor valide pentru fiecare piesă;
- detectarea atacurilor și conflictelor;
- verificarea situațiilor speciale (șah, șah-mat, pat);
- evaluarea pozițiilor pentru avantaj strategic.

### 🧠 Inteligență Artificială (AI)
Am dezvoltat un modul AI care:

- analizează mutările posibile ale ambilor jucători,
- folosește algoritmul **Minimax** pentru decizii,
- aplică **Alpha-Beta Pruning** pentru reducerea timpului de calcul,
- selectează cea mai bună mutare în funcție de evaluarea poziției.

### 🎮 Interfață și grafică
- scenă 3D construită în Unity;
- piese și tabla cu materiale personalizate;
- highlight-uri pentru interacțiune;
- control intuitiv al jucătorului prin mouse.

---

## 📁 Structura proiectului

- **Assets/** – modele 3D, scene, materiale, texturi  
- **Scripts/** – scripturi C# pentru logică și AI  
- **ProjectSettings/** – configurări Unity  
- **docs/** – documente și note de dezvoltare  
- **README.md** – documentația principală  

---

## 🔧 Tehnologii utilizate

- Unity 3D  
- C# – OOP  
- Algoritm **Minimax + Alpha-Beta Pruning**  
- Git & GitHub pentru versionare  

---

## 🧪 Testare

Am testat proiectul pentru:

- corectitudinea mutărilor pieselor;
- funcționarea situațiilor speciale (rocadă, en passant, promovare etc.);
- reacțiile AI în poziții complexe;
- performanță și stabilitate;
- validarea condițiilor de șah și șah-mat.

---

## 🧩 Utilizarea Git și GitHub în dezvoltare

Pe parcursul proiectului am folosit Git pentru:

- crearea repository-ului;
- urmărirea versiunilor prin commit-uri;
- salvarea etapizată a progresului;
- publicarea proiectului pe GitHub.

### Commit-uri importante realizate de mine:

- configurarea structurii inițiale a proiectului;
- implementarea regulilor de șah;
- dezvoltarea modulului AI;
- configurarea scenei 3D;
- finalizarea documentației.

---

## ▶ Cum se rulează proiectul

1. Instalezi **Unity Hub**  
2. Instalezi o versiune Unity compatibilă (2020+ recomandat)  
3. Clonezi repository-ul meu:

```bash
git clone LINKUL_TAU_DE_REPOSITORY

