
---
# Основные схемы объектов:
---
* **Auth:**
  - username (string, writeOnly)
  - password (string, writeOnly)
  - access (string, readOnly)
  - rememberMe (boolean, default: false)

* **Company:**
  - id (int, readOnly)
  - name (string)
  - argeement_date_begin (date)
  - agreement_date_end (date)
  - agreement (string, nullable)
  - image_url (string, nullable)
  - area_of_activity (string, nullable)
  - head_full_name (string, nullable)
  - head_job_title (string, nullable)

* **Contact:**
  - id (int, readOnly)
  - type (int)
  - value (string)

* **Speciality:**
  - id (int)
  - name (string)
  - code (string)
  - education_level (int, см. EducationLevelEnum)
  - ais_id (int, nullable)
  - faculty (int, nullable)

* **Theme:**
  - id (int, readOnly)
  - title (string)
  - type (string, см. TypeEnum)

* **User:**
  - username (string, readOnly)
  - first_name (string)
  - last_name (string)
  - email (string, nullable)


---
### Перечисления:
---

* **EducationLevelEnum:**
  - 0 - Бакалавриат
  - 1 - Специалитет
  - 2 - Магистратура
  - 3 - Аспирантура
  - 4 - Среднее профессиональное образование

* **TypeEnum:**
  - ВКР - Выпускная квалификационная работа
  - ПР - Производственная практика
  - НИОКР - Научно-исследовательские и опытно-конструкторские работы