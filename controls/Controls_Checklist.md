# 🧾 Internal Controls Checklist  
Krunixbase — Security, Governance & Compliance  
Version: 2026  
Aligned with: ISO/IEC 27001 • ISO/IEC 42001 • SOC 2 • Internal Policies

This checklist defines the **mandatory security, operational, cryptographic, and compliance controls** required across the Krunixbase organization and the SeedTools Suite.

It is used during internal audits, external reviews, and grant evaluations.

---

# ✅ 1. Governance & Documentation Controls

| Control | Description | Status |
|--------|-------------|--------|
| **[GOV‑01](ca://s?q=Governance_documentation)** | All core policies documented and versioned | ✔️ |
| **[GOV‑02](ca://s?q=Compliance_directory_structure)** | `/compliance` directory complete and structured | ✔️ |
| **[GOV‑03](ca://s?q=Policy_review_cycle)** | Policies reviewed at least annually | ✔️ |
| **[GOV‑04](ca://s?q=Role_definition)** | Roles and responsibilities clearly defined | ✔️ |
| **[GOV‑05](ca://s?q=Transparency_controls)** | Documentation accessible to authorized maintainers | ✔️ |

---

# 🔐 2. Access Control & Identity Management

| Control | Description | Status |
|--------|-------------|--------|
| **[AC‑01](ca://s?q=MFA_requirement)** | MFA enabled for all maintainers | ✔️ |
| **[AC‑02](ca://s?q=RBAC_model)** | Role‑Based Access Control implemented | ✔️ |
| **[AC‑03](ca://s?q=Least_privilege)** | Least privilege enforced | ✔️ |
| **[AC‑04](ca://s?q=Access_review_cycle)** | Access reviewed every 6 months | ✔️ |
| **[AC‑05](ca://s?q=Restricted_data_controls)** | Restricted data accessible only offline | ✔️ |
| **[AC‑06](ca://s?q=Credential_rotation)** | Credentials rotated after incidents or role changes | ✔️ |

Learn more: **[Access Control Policy](ca://s?q=Access_Control_Policy)**

---

# 🔒 3. Cryptographic & Technical Controls

| Control | Description | Status |
|--------|-------------|--------|
| **[CRYPTO‑01](ca://s?q=Deterministic_verification)** | Deterministic cryptographic verification | ✔️ |
| **[CRYPTO‑02](ca://s?q=Offline_processing)** | All sensitive operations performed offline | ✔️ |
| **[CRYPTO‑03](ca://s?q=Evidence_integrity)** | Evidence integrity checks (hashing, fingerprints) | ✔️ |
| **[CRYPTO‑04](ca://s?q=Seed_entropy_validation)** | Seed entropy validation implemented | ✔️ |
| **[CRYPTO‑05](ca://s?q=Path_derivation_validation)** | BIP32/44/49/84/86/Taproot path validation | ✔️ |
| **[CRYPTO‑06](ca://s?q=Tamper_detection)** | Tamper detection for evidence and configs | ✔️ |

Learn more: **[Technical Verification](ca://s?q=Technical_verification)**

---

# 🛠 4. Operational Security Controls

| Control | Description | Status |
|--------|-------------|--------|
| **[OPS‑01](ca://s?q=Air_gapped_workflows)** | Air‑gapped workflows enforced | ✔️ |
| **[OPS‑02](ca://s?q=Device_isolation)** | Device isolation procedures followed | ✔️ |
| **[OPS‑03](ca://s?q=Backup_procedures)** | Secure backup procedures documented | ✔️ |
| **[OPS‑04](ca://s?q=Key_handling)** | Secure key handling procedures implemented | ✔️ |
| **[OPS‑05](ca://s?q=Operational_restrictions)** | Donor/NGO operational restrictions respected | ✔️ |
| **[OPS‑06](ca://s?q=Operational_logs)** | Operational logs stored offline | ✔️ |

Learn more: **[Operational Security Requirements](ca://s?q=Operational_security_requirements)**

---

# 🧩 5. Compliance Suite Controls

| Control | Description | Status |
|--------|-------------|--------|
| **[COMP‑01](ca://s?q=GDPR_validator)** | GDPR Evidence Validator operational | ✔️ |
| **[COMP‑02](ca://s?q=SOC2_validator)** | SOC2 Evidence Validator operational | ✔️ |
| **[COMP‑03](ca://s?q=IAM_validator)** | IAM Validator operational | ✔️ |
| **[COMP‑04](ca://s?q=Licensing_compliance_engine)** | Licensing Compliance Engine operational | ✔️ |
| **[COMP‑05](ca://s?q=Offline_report_generator)** | Offline report generator functional | ✔️ |
| **[COMP‑06](ca://s?q=Rule_set_versioning)** | Rule sets versioned and documented | ✔️ |

Learn more: **[Compliance Suite Architecture](ca://s?q=Compliance_Suite_Architecture)**

---

# 🌍 6. NGO Compliance Pipeline Controls

| Control | Description | Status |
|--------|-------------|--------|
| **[NGO‑01](ca://s?q=Donation_event_controls)** | Donation event evidence collected | ✔️ |
| **[NGO‑02](ca://s?q=Offline_evidence_collection)** | Evidence collected offline | ✔️ |
| **[NGO‑03](ca://s?q=UTXO_discovery)** | UTXO discovery validated | ✔️ |
| **[NGO‑04](ca://s?q=Compliance_classification)** | Classification: compliant/review/blocked | ✔️ |
| **[NGO‑05](ca://s?q=NGO_report_generation)** | Deterministic NGO report generated | ✔️ |
| **[NGO‑06](ca://s?q=Audit_trail_storage)** | Audit trail stored securely | ✔️ |

Learn more: **[NGO Compliance Pipeline](ca://s?q=NGO_Compliance_Pipeline)**

---

# 📝 7. Policy Compliance Controls

| Control | Description | Status |
|--------|-------------|--------|
| **[POL‑01](ca://s?q=Data_Protection_Policy)** | Data Protection Policy implemented | ✔️ |
| **[POL‑02](ca://s?q=Access_Control_Policy)** | Access Control Policy implemented | ✔️ |
| **[POL‑03](ca://s?q=Incident_Response_Policy)** | Incident Response Policy implemented | ✔️ |
| **[POL‑04](ca://s?q=Risk_Management_Policy)** | Risk Management Policy implemented | ✔️ |
| **[POL‑05](ca://s?q=Policy_versioning)** | Policies versioned and maintained | ✔️ |

---

# 🚨 8. Incident Response Controls

| Control | Description | Status |
|--------|-------------|--------|
| **[IR‑01](ca://s?q=Incident_identification)** | Incident identification procedures in place | ✔️ |
| **[IR‑02](ca://s?q=Incident_containment)** | Containment procedures documented | ✔️ |
| **[IR‑03](ca://s?q=Incident_eradication)** | Eradication procedures documented | ✔️ |
| **[IR‑04](ca://s?q=Incident_recovery)** | Recovery procedures validated | ✔️ |
| **[IR‑05](ca://s?q=Incident_documentation)** | Incident documentation requirements met | ✔️ |
| **[IR‑06](ca://s?q=Post_incident_review)** | Post‑incident review process defined | ✔️ |

Learn more: **[Incident Response Policy](ca://s?q=Incident_Response_Policy)**

---

# 🧪 9. Audit & Monitoring Controls

| Control | Description | Status |
|--------|-------------|--------|
| **[AUD‑01](ca://s?q=Internal_audit_cycle)** | Internal audits performed annually | ✔️ |
| **[AUD‑02](ca://s?q=Audit_trail_integrity)** | Audit trail integrity validated | ✔️ |
| **[AUD‑03](ca://s?q=Evidence_versioning)** | Evidence versioning enforced | ✔️ |
| **[AUD‑04](ca://s?q=Monitoring_controls)** | Monitoring controls in place | ✔️ |
| **[AUD‑05](ca://s?q=External_audit_readiness)** | Ready for external audits | ✔️ |

Learn more: **[Internal Audit 2026](ca://s?q=Internal_Audit_2026)**

---

# 📞 10. Contact

For questions regarding this checklist:

- **Andrzej (Krunixbase)**  
- Security & Compliance Lead  
- Project Lead — **SeedTools Suite**

