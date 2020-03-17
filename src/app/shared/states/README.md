##**Contain All The State Files**
_These state files are imported across the application_

These state files are very effective for a large scale project that require dynamic variable process that independent from normal service. There are many existed state management libraries out there but I highly suggest you to checkout these:

- `NgRx`
- `NgXS`
- `Akita State Managerment`

I highly suggested you to take a look at `Akita` as they followed strictly to the Angular Service conventional and have a very active chat forum.

---
Depending on preference only, any structure is acceptable. However, its structure should be module and follow the feature subjects above for better management.

---

Should not put pipes/component/etc. to this shared folder.
