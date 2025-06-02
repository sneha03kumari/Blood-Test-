# Blood Test Panel –
This blood test panel program is designed to evaluate key aspects of a person’s health by checking electrolyte balance, blood sugar levels, and kidney function. It tests sodium, potassium, and chloride levels to assess electrolyte imbalances, which are critical for maintaining bodily functions. The program also evaluates blood sugar levels specifically for Type 1 and Type 2 diabetes patients using tailored thresholds. Additionally, it assesses kidney health by analyzing creatinine levels and estimated glomerular filtration rate (GFR) to detect potential kidney impairment. The tool provides clear, easy-to-understand feedback based on standard medical reference ranges, helping users identify potential health issues early through a simple interactive interface.

## 🎯 Features
- Electrolyte Panel Test:
Checks sodium, potassium, and chloride levels, and reports low, high, or normal with medical context.
- Sugar Level Test:
Uses polymorphism with a base Patient class and derived classes for Type 1 and Type 2 Diabetes patients, applying different threshold logic.
- Kidney Health Check:
Evaluates creatinine and estimated GFR levels to assess kidney health status.
- Menu-driven Interface:
User can select tests repeatedly until choosing to exit.

## ⚙️ Project Workflow
- Display menu with test options and exit.
- User selects a test to perform.
- Input necessary data for the chosen test.
- Run evaluation logic specific to the test.
- Show the test results to the user.
- Repeat menu until user chooses to exit.

## 🏗️ Design Highlights
- Uses class encapsulation for each test area (ElectrolytePanel, Patient hierarchy, KidneyHealth)
- Polymorphism with virtual and pure virtual functions in Patient class and overrides in derived classes
- Simple operator overloading in KidneyHealth (though not used meaningfully here)
- Clear input-output interaction using console


