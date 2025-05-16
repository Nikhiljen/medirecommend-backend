**Web App Overview:**

**Main Function**: User enters disease name + location → App provides:

1. Doctor recommendation:
    - Name, qualification, experience.
    - Specialization in handling similar cases.
    - Location & hospital/clinic name.
2. Hospital Info:
    - Fee structure (consultation, surgery, tests, etc.).
    - Government health schemes availability.
    - Alternate hospitals where government schemes are applicable.
3. Health Insurance:
    - List of applicable health insurance plans.
    - Government and private insurers.
    - Coverage benefits & eligibility.

---

## **Key Features and Data Sources Needed:**

### 1. **User Input:**

- Disease name (e.g., "diabetes", "cardiac arrest").
- Location (city, district, pin code).

### 2. **Doctor & Hospital Database:**

- **Sources**: Government APIs (like National Health Stack), hospital directories, private health APIs.
- **Data to fetch**:
    - Doctor name, qualifications (MBBS, MD, etc.), years of experience.
    - Specialization & treatment record for specific diseases.
    - Current working hospital/clinic.
    - Consultation and treatment fees.

### 3. **Government Schemes:**

- **Sources**: Ministry of Health & Family Welfare (MoHFW), Ayushman Bharat, state health portals.
- Check if the selected hospital is enrolled.
- If not, recommend alternative government-empaneled hospitals.

### 4. **Insurance Options:**

- **Data needed**:
    - List of insurance providers active in the user’s area.
    - Policy types (for disease-specific coverage).
    - Eligibility criteria and process to apply.
- **Sources**: IRDAI (Insurance Regulatory and Development Authority of India), private insurers' APIs.

---
