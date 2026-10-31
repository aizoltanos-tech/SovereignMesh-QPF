# Public push policy

Push to the public GitHub repository **only**:

- Operations console HTML (operator UI, no internals)
- High-level README without algorithms, protocols, or architecture details
- Marketing or status pages that do not describe how detection, mesh, or cryptography works

**Do not push:**

- Source code of the firewall or protocol engines
- Official technical records that describe mechanisms
- Continuation notes that list implementation steps (XDP, Z3, entropy models, etc.)
- Deploy scripts with install paths or service definitions that expose design
- Any file that explains principles of operation or know-how

Internal archives remain local or in private storage only.
