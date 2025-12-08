# 📚 SchoolApp – MVC Model-First Project

A clean and modular **ASP.NET Core MVC** application following a **Model-First architecture**.  
Designed with best practices in mind, featuring **DTOs**, **Services**, **Repositories**, **Filters**, **Custom Exceptions**, and **Entity Framework Core**.

---

## ✨ Features

- 🧱 Model-First architecture with a well-structured domain layer  
- 🗄️ Entity Framework Core with migrations  
- 🧩 Repository pattern for clean data access  
- ⚙️ Service layer for business logic separation  
- 📦 DTOs for request/response models  
- 🔒 Custom filters & centralized exception handling  
- 🧑‍🏫 Controllers for all main modules (Students, Teachers, etc.)  
- 🎨 Razor Views following MVC conventions  
- 🚀 Extensible and maintainable design  

---

## 📁 Project Structure

```
SchoolApp/
│
├── Controllers/        -> MVC controllers
├── Core/               -> Domain models & filters
├── Data/               -> DbContext & EF Core configuration
├── Dto/                -> Data Transfer Objects
├── Exceptions/         -> Custom exception classes
├── Migrations/         -> EF Core migrations
├── Properties/         -> Project settings
├── Repositories/       -> Repository interfaces & implementations
├── Services/           -> Business logic layer
├── Views/              -> Razor UI views
└── wwwroot/            -> Static assets (CSS, JS, images)
```

---

## 🛠️ Technologies Used

- ⚡ ASP.NET Core MVC  
- 🟦 C# (.NET 7/8)  
- 🗄️ Entity Framework Core  
- 🖥️ Razor Views  
- 🧪 Dependency Injection  
- 🗃️ SQL Server / LocalDB  

---

## 🚀 Getting Started

### 1️⃣ Clone the repository

```
git clone https://github.com/vastriantafyllou/mvc-model-first-pro.git
```

### 2️⃣ Navigate into the project

```
cd mvc-model-first-pro/SchoolApp
```

### 3️⃣ Apply migrations

```
dotnet ef database update
```

### 4️⃣ Run the application

```
dotnet run
```

---

## 🧠 Design Principles

- 🔹 Clear separation of concerns  
- 🔹 Layered architecture (Controller → Service → Repository → DbContext)  
- 🔹 DTO-based communication for safety and clarity  
- 🔹 Centralized error handling  
- 🔹 Easy to extend with new modules  

---

## 🔮 Future Improvements

- 🔐 Add authentication & authorization  
- 🧪 Add unit & integration tests  
- 🎓 More advanced student/teacher features  
- 🎨 Improve UI with Bootstrap or a modern frontend framework  

