# MedScan

MedScan is a full stack web application designed to provide patients and doctors with clear, reliable information about medicines. Users can scan a barcode or search for a medicine by name to instantly access details such as usage, dosage, side effects, warnings, and safety checks based on personal allergies or conditions. Doctors have a special view with extra information like drug interactions to support safe prescriptions.

---

## Features

- **Medicine Search:** Find medicine information by barcode or name.
- **Barcode Scanning:** Scan medicine barcodes using your device camera (QuaggaJS integration).
- **Personal Safety Checks:** Warnings based on user allergies, conditions (e.g., pregnancy, diabetes).
- **Doctor Dashboard:** Additional insights including drug interactions and patient notes.
- **Role-based Access:** Separate views and permissions for patients and doctors.
- **Modern Tech Stack:** Java (Spring Boot) backend, React frontend, MySQL/PostgreSQL database.

---

## How It Works

- **Patients** scan or search for medicines and receive personalized safety warnings.
- **Doctors** log in for expanded medicine details and can review drug interactions for their patients.

---

## Getting Started

### Prerequisites

- [Java 17+](https://adoptopenjdk.net/)
- [Node.js 18+](https://nodejs.org/)
- [Maven](https://maven.apache.org/)
- [MySQL](https://www.mysql.com/) or [PostgreSQL](https://www.postgresql.org/)

### Installation

#### 1. Clone the Repository

```bash
git clone https://github.com/<your-username>/medscan.git
cd medscan
```

#### 2. Backend Setup (Spring Boot)

```bash
cd backend
# Configure src/main/resources/application.properties with your database credentials
mvn spring-boot:run
```

#### 3. Frontend Setup (React)

```bash
cd ../frontend
npm install
npm start
```

#### 4. Access the App

- Open [http://localhost:3000](http://localhost:3000) in your browser.
- Backend runs on [http://localhost:8080](http://localhost:8080)

---

## Project Structure

```plaintext
medscan/
├── backend/         # Spring Boot REST API
│   ├── src/
│   └── pom.xml
├── frontend/        # React app with QuaggaJS
│   ├── src/
│   └── package.json
└── README.md
```

---

## Contributing

1. Fork the repo
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## License

This project is licensed under the MIT License.

---

## Acknowledgements

- [Spring Boot](https://spring.io/projects/spring-boot)
- [React](https://react.dev/)
- [QuaggaJS](https://serratus.github.io/quaggaJS/)
- [MySQL](https://mysql.com/), [PostgreSQL](https://postgresql.org/)

#hello world this is mu first change in this read me file hehehe
---
