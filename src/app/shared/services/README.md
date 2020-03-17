##**Contain All The Service Files**
_These service are imported across the application_

These services normally handle the API process and other process that require cross component data transfer. However, if the application becomes more complex in the future, it's suggested to use `state mangagerement library` like `NgRx`, `NgXS`, `Akita State Managerment`; which I highly suggested you to take a look at `Akita` as they followed strictly to the Angular Service conventional.

---
Depending on preference only, any structure is acceptable. However, its structure should be module and follow the feature subjects above for better management.
- Authenticate pipe (`authorize/authenticate.service.ts`)
---

Should not put pipes/component/etc. to this shared folder.
