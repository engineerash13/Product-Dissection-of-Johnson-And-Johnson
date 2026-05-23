# Product Dissection of Johnson & Johnson

A business and product analysis of Johnson & Johnson (J&J), examining how one of the world's leading healthcare companies solves real-world problems through its pharmaceutical, medical device, and consumer health product lines. Includes a conceptual database schema design for a digital health platform.

---

## Files in This Repository

| File | Description |
|------|-------------|
| `Product Dissection of Johnson & Johnson.docx` | Full analysis document — company overview, product dissection, real-world problem-solution mapping, and ER schema design |

---

## About Johnson & Johnson

Founded in **1886**, J&J operates across 60+ countries in three core segments:

- **Pharmaceuticals** — cancer treatments (Darzalex), autoimmune drugs, infectious disease therapies
- **Medical Devices** — surgical instruments, orthopedic implants, cardiovascular devices
- **Consumer Health** — Band-Aid, Tylenol, Johnson's Baby, Acuvue contact lenses

---

## Real-World Problems & J&J's Solutions

| Problem | J&J Solution |
|---------|--------------|
| Wound care accessibility in remote areas | Band-Aid — convenient, sterile first-aid |
| Safer pain relief amid opioid crisis | Tylenol (acetaminophen) — non-opioid alternative |
| Affordable vision correction | Acuvue contact lenses |
| Safe skincare for infants | Johnson's Baby — hypoallergenic products |
| Targeted cancer treatment | Darzalex — multiple myeloma therapy |

---

## Key Business Insights

- Strong R&D investment drives continuous healthcare innovation
- Quality assurance and stringent safety testing are core to the brand
- Sustainability initiatives include eco-friendly packaging and carbon reduction
- Digital health transformation — AI-driven diagnostics and telemedicine
- Global accessibility strategy ensures affordability across markets

---

## Database Schema Design

A conceptual ER schema for a J&J digital health platform:

**Entities & Key Attributes**

| Entity | Primary Key | Key Attributes |
|--------|-------------|----------------|
| Users | UserId (PK) | Name, Email, Age, Gender |
| Products | ProductId (PK) | Name, Category, Price, Description |
| Transactions | TransactionId (PK) | UserId (FK), ProductId (FK), Date, Amount |
| Reviews | ReviewId (PK) | UserId (FK), ProductId (FK), Rating (1–5), Comments |

**Relationships**
- A User can make many Transactions (one-to-many)
- A Product can appear in many Transactions (one-to-many)
- A User can leave many Reviews; a Product can receive many Reviews (many-to-many resolved via Reviews entity)

---

## Topics

`product-analysis` `business-analysis` `database-design` `er-diagram` `healthcare` `johnson-and-johnson`
