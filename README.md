
# **Student Records Dataset**

This repository contains a dataset of student records stored in JSON format. The data includes details like student ID, batch, section, registered subjects, contact information, and address.

## **Files in the Repository**
- **`students.json`**: 
  - Contains the student data in JSON format.
  - Each student has a unique ID and associated details.

---

## **Fields in `students.json`**

- **`id`**: Unique identifier for each student (e.g., "S101").
- **`name`**: Full name of the student (e.g., "Alice Johnson").
- **`batch`**: Graduation year or batch of the student (e.g., "2024").
- **`section`**: The section or group of the student (e.g., "A").
- **`subjects_registered`**: A list of subjects the student is enrolled in (e.g., `["Mathematics", "Physics"]`).
- **`phone_number`**: Contact number of the student (e.g., "+1-123-456-7890").
- **`email`**: Email address of the student (e.g., "alice.johnson@example.com").
- **`address`**: Nested object containing the following fields:
  - `street`: Street name (e.g., "123 Maple Street").
  - `city`: City name (e.g., "Springfield").
  - `state`: State name (e.g., "IL").
  - `zip`: ZIP code (e.g., "62704").
  - `country`: Country name (e.g., "USA").

---

## **Usage**

1. **Viewing the Data**:  
   Open the `students.json` file in any text editor or JSON viewer to examine the dataset.

2. **Parsing the Data**:
   - Use a programming language like Python to parse the JSON file.
   - Example Python snippet:
     ```python
     import json

     with open("students.json", "r") as file:
         data = json.load(file)
         print(data["students"])
     ```

3. **Modifying the Data**:
   - Update the JSON file manually in a text editor.
   - Or programmatically using JSON manipulation libraries.

---

## **Contributing**

If you wish to add new fields or students, follow these steps:
1. Fork the repository.
2. Add or update the `students.json` file with new entries.
3. Submit a pull request for review.

---

## **License**

This dataset is provided for educational purposes under the [MIT License](LICENSE). Please attribute appropriately if used elsewhere.
