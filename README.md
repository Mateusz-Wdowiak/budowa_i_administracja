# Todo List - aplikacja do zarządzania zadaniami by Mateusz Wdowiak

Projekt natywnej aplikacji chmurowej realizowany w architekturze 3-warstwowej.

## Deklaracja Architektury (Mapowanie Azure)
Ten projekt został zaplanowany z myślą o usługach PaaS (Platform as a Service) w chmurze Azure.

| Warstwa | Komponent Lokalny      | Usługa Azure |
| :--- |:-----------------------| :--- |
| **Presentation** | React 19               | Azure Static Web Apps |
| **Application** | API (Node 24 (NestJs)) | Azure App Service |
| **Data** | MongoDB                | Azure Cosmos DB (dla MongoDB API) |

## 🏗 Status Projektu i Dokumentacja
* [x] **Artefakt 1:** Zaplanowano strukturę folderów i diagram C4 (dostępny w `/docs`).
* [ ] **Artefakt 2:** Konfiguracja środowiska Docker (w trakcie...).

> **Informacja:** Ten plik będzie ewoluował. W kolejnych etapach dodamy tutaj sekcje 'Quick Start', opis zmiennych środowiskowych oraz instrukcję wdrożenia (CI/CD).
