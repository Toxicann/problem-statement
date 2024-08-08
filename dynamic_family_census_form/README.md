

---

# **Dynamic Family Census Form**

## **Overview**

This Flutter application simulates receiving a JSON structure from a server API call to dynamically generate a Family Census Form. The form allows users to input and manage family data efficiently, with features such as dynamic form rendering, validation, offline capability, and data synchronization with Firebase.


## **Requirements**

### **Dynamic Form Rendering**
- Parse the provided JSON structure to dynamically generate form fields according to their type (e.g., text, dropdown, radio button, etc.).
- Implement support for form sections, including repeatable sections like "Family Members," allowing users to add multiple entries.

### **Form Validation**
- Apply validation rules as defined in the JSON to the form fields (e.g., required fields, pattern matching for phone numbers, age limits).
- Display error messages when user input fails to meet validation criteria.

### **Data Management**
- Enable users to save their form data locally using SQLite, Hive, or another suitable method.
- Provide functionality for users to view, edit, and delete saved census data.

### **UI/UX Design**
- Design a user-friendly interface with clear distinctions between form sections.
- Ensure the form is responsive and provides a seamless experience across different screen sizes.

### **Offline Capability & Data Sync**
- Allow the app to function without an internet connection, enabling local form data saving.
- Automatically sync the locally saved data with Firebase when the device reconnects to a stable network.

## **Expected Outcome**

A fully functional Flutter application that dynamically renders a Family Census Form based on the provided JSON structure. The application should support the following:
- Multiple family members.
- Validation of user input according to the JSON rules.
- Local data saving.
- Automatic data synchronization with Firebase when an internet connection is available.

## **Bonus Point**

- **CSV Export:** Implement an option to export the saved form data to a CSV file, which should include all census details and be easily shareable.

## **Getting Started**

### **Prerequisites**
- Flutter SDK
- Dart
- Firebase account for data synchronization
- SQLite, Hive, or other local storage options

---

