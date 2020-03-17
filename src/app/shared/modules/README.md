##**Contain All The External Module Files**
_These modules are imported across the application_

These modules mostly are shared modules and are imported in feature modules to limit the redundancy.

---
Depending on preference only, any structure is acceptable. However, its structure should be module and follow the feature subjects above for better management.
- Core module (`core/core.module.ts`)
- Material module (`core/material.module.ts`)
---

Should not put service/pipes/component/etc. to this shared folder.
