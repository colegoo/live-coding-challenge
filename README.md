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

### 1. **Landing page simplă**
- [Hero section](https://tailwindui.com/components/marketing/sections/heroes) minimal cu titlu și descriere
- Buton **"Înregistrare Profesor"**

### 2. **Formular de înregistrare & creează primul anunț**
- **Input-uri:** Nume, email, materie predată (dropdown), descriere anunț, tarif pe oră, program disponibilitate (text sau time picker simplu)
- **Buton Submit:** Salvare în DB și redirect către pagina de profil
- **Preview (bonus):** În timp real sub formular care arată cum va apărea anunțul
- **Validări (bonus):** Validări de bază pentru input-uri

### 3. **Pagină de profil cu informațiile salvate**
- **Submit:** Salvare în DB
- **Redirect:** Pagina de succes, unde se afișează datele introduse din baza de date

### **Bonus:**
- **Responsiveness:** Design responsive pentru mobile pentru toate paginile
- **Autentificare:** Implementare autentificare simplă cu email și parolă

---

## 🛠️ Stack Recomandat

- **Frontend:** React, Vue, Laravel Blade, Django Templates, etc.
- **Backend:** Orice MVC Framework (.NET, Node, Laravel, Spring, etc.)
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
