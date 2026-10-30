# 🏫 Cali School Management System (Nidaamka Maamulka Dugsiga)

Nidaam dhameystiran oo casri ah oo loogu talagalay maamulka dugsiyada (School Management System), laguna dhisay **HTML5, CSS3, iyo JavaScript**, kaasoo leh **Database buuxa oo shaqeynaya** (Client-side LocalStorage DB oo leh Export/Import JSON Backup).

---

## 🚀 Sida Loo Furo (How to Run)
Uma baahnid wax server ah ama wax rakibid ah (Zero installation needed):
1. Tag galka mashruuca: `c:\Users\cusma\OneDrive\Desktop\cali school management`
2. Si toos ah u laba-guji (double-click) faylka **`index.html`** si aad ugu furto browser-kaaga (Chrome, Edge, Firefox, iwm).

---

## 🔐 Akoonnada Diyaarsan ee Nidaamka (Default Login Credentials)

Nidaamku wuxuu leeyahay akoonno tijaabo ah oo horay loo geliyey:

### 👑 1. Maamulaha Guud (Super Admin)
* **Username:** `admin`
* **Password:** `admin 121212` *(sidoo kale waxaad isticmaali kartaa `121212`)*
* **Awoodaha:** Dhammaan nidaamka (ardayda, macallimiinta, imaanshaha, imtixaanka, fasallada, kharashaadka, ogeysiisyada, backup-ka database-ka).

### 👨‍🏫 2. Macallin (Teacher Account)
* **Username:** `axmed.cali` *(ama email: `axmed@calischool.edu.so`)*
* **Password:** `123456`
* **Awoodaha:** Qaadashada imaanshaha ardayda (attendance), gelinta buundooyinka imtixaanka (enter marks), aragtida ardayda fasalladiisa, iyo daabacaadda natiijooyinka.

### 👨‍🎓 3. Arday (Student Account)
* **Username:** `khaalid.jaamac` *(ama email: `khaalid@calischool.edu.so`)*
* **Password:** `123456`
* **Awoodaha:** Eegista natiijada imtixaanka (Report Card), aragtida heerka imaanshaha, kaarka ardaynimo (ID Card daabacan), xaaladda lacag-bixinta, iyo wargelinta dugsiga.

---

## 📝 Diiwaangelinta Cusub (Self Registration)

Qof kasta wuxuu si toos ah isaga diiwaangelin karaa bogga hore ee Login-ka:
* **Diiwaangeli Arday (Student Sign Up):**
  - Ardaygu wuxuu gelinayaa magaciisa, fasalkiisa, email-kiisa, lambarka sirta ah (password), iyo telefoonkiisa.
  - Nidaamku wuxuu si toos ah u siinayaa aqoonsi ardaynimo gaar ah (tusaale `STD-2005`), wuxuuna ku darayaa database-ka ardayda iyo biilasha waxbarashada.
* **Diiwaangeli Macallin (Teacher Sign Up):**
  - Macallinku wuxuu gelinayaa magaciisa, maaddada uu dhigo, email-kiisa, shahaadadiisa, iyo furaha sirta ah.
  - Waxaa loo abuurayaa akoon macallinnimo (tusaale `TCH-104`).

---

## ✨ Qeybaha Nidaamka (System Modules)

1. **📊 Dashboard (Guudmar):**
   - Xisaabinta guud ee tirada ardayda, macallimiinta, fasallada, iyo lacagaha la qabtay.
   - Shaqooyinka degdegga ah (Quick actions).

2. **👨‍🎓 Ardayda (Students Management):**
   - Ku darid, wax ka beddel, tirtiris ardayda.
   - Shaandheyn (Filter by class) iyo raadinta magacyada.
   - Soo saaridda iyo daabacaadda Kaarka Ardaynimo (**Student ID Card**).

3. **👩‍🏫 Macallimiinta (Teachers Management):**
   - Diiwaanka macallimiinta iyo maadooyinka ay dhigaan.
   - Ku darid, wax ka beddel iyo xiriirka fasallada.

4. **📅 Imaanshaha & Joogitaanka (Attendance System):**
   - Xulashada fasalka iyo taariikhda maalinlaha ah.
   - Badhamada Jooga (Present), Maqan (Absent), iyo Daahay (Late).
   - Hal-guji oo dhammaan jooga ka dhigaya (**Mark All Present**).
   - Xisaabinta tooska ah ee heerka boqolleyda imaanshaha (% Attendance rate).

5. **📝 Imtixaannada & Buundooyinka (Exams, Marks & Report Cards):**
   - Abuurista imtixaannada cusub iyo jadwalkooda.
   - Gelinta buundooyinka maaddo kasta (0 - 100).
   - Xisaabinta tooska ah ee darajada (A+, A, B, C, D, F) iyo GPA-da.
   - Soo saaridda iyo daabacaadda **Warqadda Rasmiga ah ee Natiijada Ardayga (Official Report Card)** oo leh saxiixa maamulka iyo macallinka.

6. **🏫 Fasallada & Maadooyinka (Classes & Subjects):**
   - Maamulka fasallada dugsiga (Form 1, 2, 3, 4 iwm).
   - Maamulka maadooyinka iyo macallimiinta loo xilsaaray.

7. **💰 Kharashaadka & Lacagaha (Fees & Finance):**
   - Diiwaanka khidmadda waxbarashada (Tuition Fees).
   - Xaaladaha: La Bixiyay (Paid), Qeyb (Partial), Aan La Bixin (Unpaid).
   - Qabashada lacag-bixinta ardayda iyo risiidhka.

8. **📢 Ogeysiisyada (Notice Board):**
   - Soo saaridda wargelinta dugsiga.
   - Kala soocidda ogeysiisyada ardayda, macallimiinta ama dadweynaha.

9. **💾 Database & Backup (Settings):**
   - **Export Database (JSON):** Hal-guji oo aad ku soo degsan karto dhammaan keydka xogta dugsiga si uusan marnaba kuugu lumin.
   - **Import Database (JSON):** Soo celinta xogtii aad horay u keydsatay.
   - **Reset Demo Data:** Dib u soo celinta xogta asalka ah ee tijaabada.
   - Beddelidda magaca dugsiga, halkudhigga iyo cinwaanka.

---

## 📁 Qaabdhismeedka Faylasha (File Structure)

```text
cali school management/
├── index.html          # Bogga ugu weyn ee nidaamka (Single Page Application)
├── css/
│   └── style.css       # Naqshadda casriga ah, midabbada, qaabka mobile-ka & daabacaadda
├── js/
│   ├── db.js           # Database engine-ka, LocalStorage CRUD, data seeder, export/import
│   ├── auth.js         # Nidaamka Login-ka (Admin, Teacher, Student) & is-diiwaangelinta
│   └── app.js          # Maamulaha guud ee shaashadaha, howlaha ardayda, imtixaanka, iwm
└── README.md           # Buug-tilmaameedka nidaamka
```
