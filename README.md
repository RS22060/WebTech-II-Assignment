# WebTech-II-Assignment
Šeit var atrast saites uz visiem veiktajiem praktiskajiem uzdevumiem - nosacījums un kur kodā tas ir izpildīts.

---

## 1.Praktiskais uzdevums

### Uzdevums

---

## 2. Praktiskais uzdevums
[Source code](https://github.com/RS22060/HumanResourceSystem)
Vienkāršota cilvēkresursu sistēma uzņēmumam.

### Uzdevums:
1. Izveidot datubāzi ar vismaz 3 tabulām (Izstrādes vide pēc izvēles);

2. Izveidot Entity Framework modeli balstītu uz Code First metodes uz eksistējošas datu bāzes pamata;
[Modeļi](https://github.com/RS22060/HumanResourceSystem/tree/main/HumanResourceSystem/Models)

3. Veikt 3 izmaiņas datu bāzei un veikt migrāciju atbilstoši katrai izmaiņai:
- [Pievienota algas kolonna](https://github.com/RS22060/HumanResourceSystem/blob/main/HumanResourceSystem/Migrations/202309191734269_AddedSalaryColumn.cs)
- [Pievienota komandas entīte](https://github.com/RS22060/HumanResourceSystem/blob/main/HumanResourceSystem/Migrations/202309191736168_AddedTeamEntity.cs)
- [Pievienota kolonna dzimums](https://github.com/RS22060/HumanResourceSystem/blob/main/HumanResourceSystem/Migrations/202309191739277_AddedTeamsRelationshipToDepartment.cs)

4. Izveidot iespēju ievadīt un saglabāt datubāzē lietotāja definētus datus (UI izstrādes vide pēc izvēles). UI realizēts ar ASP.NET MVC
- [Kontrolieri](https://github.com/RS22060/HumanResourceSystem/tree/main/HumanResourceSystem/Controllers)
- [Skati](https://github.com/RS22060/HumanResourceSystem/tree/main/HumanResourceSystem/Views)

---

## 3. Praktiskais uzdevums

### Uzdevums:
1. Lejupielādēt DataAnnotation.zip vai FluentAPI.zip arhīvu no Moodle sistēmas;

2. Migrēt sagatavoto projektu.

3. Nomainīt vienas tabulas nosaukumu;
[Autors kļuva par lektoru](https://github.com/RS22060/FluentAPITask/blob/main/FluentAPI/Migrations/202312021712177_AuthorBecameLecturer.cs)

4. Nomainīt viena lauka nosaukumu;
[Kursa cenas lauks pārsaukts](https://github.com/RS22060/FluentAPITask/blob/main/FluentAPI/Migrations/202312021714257_CoursePriceFieldRenamed.cs)

5. Veikt izmaiņas 3 lauku parametros.
[Kursa nosaukums kļuva nullable](https://github.com/RS22060/FluentAPITask/blob/main/FluentAPI/Migrations/202312021719038_FieldParamsAdded.cs)

---

## 4. Praktiskais uzdevums 
[Visi vaicājumi](https://github.com/RS22060/Queries/blob/main/Queries/Program.cs)

### Uzdevums:
1. Lejupielādēt LINQ.zip arhīvu no Moodle sistēmas;

2. Migrēt sagatavoto projektu.

3. Izveidot vaicājumu un izgūt datus: 
 - visi autori;
 - viena autora visi kursi;
 - visus kursus kuriem ir tags “c#”.

---

## 5.Praktiskais uzdevums

### Uzdevums
Izveidot ASP.NET Core līmekļa lietotni;

Pievienot 1 modeli datu uzturēšanai;

Pievienot vismaz 2 saskarnes;

Pievienot 1 kontrolieri datu apstrādei;

Izmantojot ASP.NET MVC funkcionalitāti, pārnest ievadītus datu starp 2 saskarnēm.


---

## 6.Praktiskais uzdevums

### Uzdevums
1. [Izveidot API datu ieguvei no datu bāzes;](https://github.com/RS22060/NewsletterAPI/tree/main/NewsletterAPI)

2. [Savienot ASP.NET API ar izvēlēto saskarni;](https://github.com/RenarsS/newsletter/blob/main/src/App.js)

3. Izvadīt datus izvēlētajā saskarnē.

---

## 7. un 8. Praktiskais uzdevums

### Uzdevums

1.[Izveidot ASP.NET Core Web API projektu;](https://github.com/RS22060/ToDoListAPI/tree/main/ToDoListAPI)

2. [Izveidot DBContext datu savienošanai ar glabāšanas vietu (Runtime/SQL Server/ cits);](https://github.com/RS22060/ToDoListAPI/blob/main/ToDoListAPI/ToDoContext.cs)

3. [Izveidot API metodi datu pievienošanai izvēlētajai datu glabāšanas metodei;](https://github.com/RS22060/ToDoListAPI/blob/main/ToDoListAPI/Controllers/NotesController.cs)

4. Izmantojot Postman rīku nosūtīt / iegūt datus uz datu glabātuvi.

---

## Eksāmena uzdevums

### Uzdevums
