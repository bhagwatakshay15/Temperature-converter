
# 🌡️ Temperature Converter Android App

An Android application built using Java and Android Studio that converts temperatures between Celsius and Fahrenheit. The app dynamically updates the background color and displays relevant images based on temperature input. It demonstrates the use of UI components, event handling, and utility classes in Android development.

---

## 🧪 Core Functionality

- Converts user-entered temperature between Celsius and Fahrenheit
- Switches background color based on result:
  - 🔴 Red if below 0
  - 💛 Yellow if between 0 and 90
  - 🔵 Skyblue if above 90
- Displays a **sunny** or **frosty** image based on temperature
- Includes Toast warnings for empty inputs

---

## 📁 Files Included

| File/Folder                  | Description                                          |
|-----------------------------|------------------------------------------------------|
| `MainActivity.java`         | Main Java logic for input, conversion, UI updates   |
| `ConverterUtil.java`        | Utility class for conversion logic                  |
| `activity_main.xml`         | Layout XML file with all UI elements                |
| `strings.xml` / `colors.xml`| Resources for UI text and color values              |
| `res/drawable/`             | Contains images (sunny, frosty) for visual feedback |
| `res/mipmap/`               | Custom home screen icon                             |
| `README.md`                 | Project documentation (this file)                   |

---

## 🎓 Concepts and Skills Demonstrated

- Understanding Android Studio's layout editor and component tree
- Used constraint-based layouts effectively
- Handled events using `onClick` and RadioGroups
- Defined and accessed XML-based resources
- Programmatically changed backgrounds and images
- Built and structured reusable Java utility classes
- Worked with `EditText`, `RadioButton`, `RadioGroup`, `Button`, `ImageView`
- Used `setBackgroundColor()` and `setImageResource()` dynamically
- Handled errors gracefully using Toast messages
- Implement logic branching with conditional statements in Java

---

## 🛠️ Tools & Technologies Used

- Android Studio (Kotlin DSL build config)
- Java
- XML (Layout and Resources)
- Emulator / Android Virtual Device (AVD)

---

## 🧪 Key Features

- **Editable Input Field** – accepts positive/negative decimal temperatures  
- **Two-Way Conversion** – toggles between Celsius and Fahrenheit  
- **Interactive UI** – responds to input with visuals and colors  
- **Custom Resource Management** – uses string, color, and drawable resources efficiently  
- **Minimal Design** – clean constraint layout with scalable positioning

---

## 📷 Snapshots

> _Check for App_screenshots in the repository_

- App running with 40°C converted to Fahrenheit  
- Background turned 🔵 (Skyblue) for temperatures > 90  
- Background turned 🔴 (Red) for temperatures < 0  
- Toast message for empty input  

---

## 📚 Resources

- [Android Developers Documentation](https://developer.android.com/docs)
- [Color Picker – Hex Codes](http://cloford.com/resources/colours/500col.htm)
- [ConstraintLayout Guide](https://developer.android.com/reference/androidx/constraintlayout/widget/ConstraintLayout)
