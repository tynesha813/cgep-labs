\# Compliant AWS S3 Primitive



Terraform implementation of a security-controlled AWS S3 architecture developed as part of the CGEP GRC Engineering Labs.



\## Security Controls



\- \*\*NIST SC-28 – Protection of Information at Rest\*\*

&#x20; - AES-256 server-side encryption on primary and logging buckets.



\- \*\*NIST AC-3 – Access Enforcement\*\*

&#x20; - S3 Public Access Block enabled with all four protections enforced.



\- \*\*NIST CM-6 – Configuration Settings\*\*

&#x20; - Standardized governance tags applied through Terraform.

&#x20; - Versioning enabled on the primary bucket.



\- \*\*NIST AU-3 / AU-6 – Audit Logging\*\*

&#x20; - Dedicated S3 logging bucket.

&#x20; - Primary bucket access logging enabled.

&#x20; - Log delivery permissions and ownership controls configured.



\## Compliance Metadata



Resources are tagged with:



\- Project

\- Environment

\- ManagedBy

\- ComplianceScope

\- Owner



\## Evidence



Machine-readable Terraform evidence is stored separately under:



`evidence/lab-2-3/`



This includes the Terraform execution plan and deployed state snapshot used to demonstrate the implemented controls.

