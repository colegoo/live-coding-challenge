# 🚀 Live Coding Challenge: Mini-platformă de Onboarding pentru Profesori

Proiectează și dezvoltă o platformă simplă de onboarding pentru profesori în **90 de minute**, concentrându-te pe **clean code** și **UX**.

---

## 📊 Structura DB (Exemplu)

```sql
-- Profesor (Teacher)
CREATE TABLE teachers (
  id BIGINT AUTO_INCREMENT PRIMARY KEY,
  name VARCHAR(100) NOT NULL,
  email VARCHAR(100) NOT NULL,
  subject VARCHAR(255),          -- ex: "matematica" / "informatica"
  description TEXT,              -- descriere scurtă a anunțului
  hourly_rate DECIMAL(10,2),      -- tarif pe oră
  availability VARCHAR(255),      -- ex: "luni-vineri,09:00-17:00"
  created_at DATETIME NOT NULL DEFAULT CURRENT_TIMESTAMP
);
```

---

## 🎯 Cerințe

### Pagina 1. **Landing page simplă**
- [Hero section](https://tailwindui.com/components/marketing/sections/heroes) minimal cu titlu și descriere
- Buton **"Înregistrare Profesor"**
- Redirect pagina 2

### Pagina 2. **Formular de înregistrare profesor**
- **Input-uri:** Nume, email, materie predată (dropdown), descriere anunț, tarif pe oră, program disponibilitate (text)
- **Buton Submit:** Salvare în DB
- Redirect pagina 3

### Pagina 3. **Pagină de success**
- **Preview date:** Afișează datele salvate de la pasul precedent (din baza de date)

### **Bonus:**
- **Responsiveness:** Design responsive pentru mobile pentru toate paginile

---

## 🛠️ Stack Recomandat

Folosește framework-ul web cu care te simți cel mai confortabil, atat pe backend, cât și pe frontend.

- **UI:** [Tailwind CSS](https://tailwindcss.com/) (sau alt framework CSS modern)
- **DB:** SQL (MySQL, PostgreSQL, SQLite, etc.)

---

## 💡 Tips pentru Succes

### 🛠️ **Recomandări:**
- Folosește AI tools (ChatGPT, GitHub Copilot) pentru boilerplate
- Concentrează-te pe quality coding și UX plăcut
- Comunică dacă ai blocaje sau întrebări
- Gândește cu voce tare și explică-ți deciziile pe parcurs

### ✅ **Focus pe:**
- Cod curat și bine organizat
- Design modern și intuitiv (ex: [Tailwind UI components](https://tailwindui.com/components))

### ❌ **De evitat:**
- Setup complicat sau over-engineering
- Cod copiat fără înțelegere
- UI/UX neintuitive sau design inconsistent

---

## 🎯 Evaluare

| 🏆 **Categorie**       | **Criterii**                                                                                                                                                                    | **Pondere** |
|------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------|
| **Implementare tehnică** | - Cod curat și organizat, self-documented (denumiri intuitive, comentarii, etc.)<br>- Validări și error handling<br>- Funcționalitate completă | **40%**     |
| **Frontend & UX**      | - Design modern și intuitiv<br>- Responsive pe mobile și desktop<br>- Atenție la detalii UI/UX                                                                                  | **40%**     |
| **Best Practices**     | - Comunicare clară<br>- Coding standards                                                                                                                                        | **20%**     |

---

Dacă ai feedback sau sugestii pentru acest proiect, suntem deschiși să le auzim!


**Mult succes!** 🚀
