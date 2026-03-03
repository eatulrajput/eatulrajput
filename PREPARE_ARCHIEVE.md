Before archiving a repository on GitHub, it’s smart to prepare it properly — especially if others use it.

Here’s a practical checklist:

---

## ✅ 1️⃣ Update the README

* Clearly state that the project is **no longer maintained**
* Add:

  * Date archived
  * Reason for archiving
  * Link to replacement project (if any)
* Mention whether pull requests will be reviewed (usually no)

Example:

> ⚠️ This project was archived in March 2026 and is no longer maintained.

---

## ✅ 2️⃣ Close or Review Open Issues & PRs

* Close unresolved issues (add a final comment if needed)
* Close or merge open pull requests
* Thank contributors

This avoids confusion after it becomes read-only.

---

## ✅ 3️⃣ Create a Final Release (Optional but Recommended)

* Tag the latest stable version
* Publish a release with notes
* Mark it as the “final stable version”

This makes it clear what the last official version is.

---

## ✅ 4️⃣ Update Documentation

* Ensure setup instructions still work (if applicable)
* Remove outdated links
* Clarify dependencies and versions

---

## ✅ 5️⃣ Check for Sensitive Data

Before archiving, double-check:

* API keys
* Tokens
* Passwords
* Private certificates
* `.env` files

If found, remove them and rotate credentials before archiving.

---

## ✅ 6️⃣ Notify Users (If Needed)

If the repo is used by others:

* Post an announcement issue
* Mention it in release notes
* Notify via README
* Announce on relevant platforms (if it’s a popular project)

---

## ✅ 7️⃣ Consider Alternatives

Ask yourself:

* Should it be **private instead**?
* Should it be transferred to another maintainer?
* Should it be moved to an organization account?

---

## 🚀 After That

Then you can archive:

> Repository → Settings → Danger Zone → **Archive this repository**

---

### 💡 Pro Tip

Once archived:

* You cannot edit files unless you unarchive it.
* Actions/workflows stop running.
* It becomes read-only immediately.
