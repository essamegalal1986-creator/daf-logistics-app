# DAF Logistics App

Order-to-stock logistics tracker by **DAF – For Digital Solutions**.

One reference number follows every order from request to preparation, route, delivery, sale, stock movement and report.

## First use

The app starts **empty**, with one built-in administrator account:

- **Username:** `admin`
- **Password:** `DafAdmin2026` (temporary)

At the first sign-in, the app asks you to choose your own name, username and password. After that the temporary password stops working.

Then set up, in this order:

1. Projects
2. Products and batches
3. Setup data: customers, governorates, route groups, warehouses, sales team, logistics agents and opening stock
4. Users, on the Users and access page

## Publishing (GitHub Pages)

Settings → Pages → Deploy from a branch → `main` / `/ (root)`.

## Where the data is stored

This is a static website with no server.

- All data is saved in the **browser on the device** where it is entered (localStorage).
- Another device or browser starts empty.
- Clearing browser data deletes it.

**Download a backup regularly:** Users and access → Backup and restore → Download backup.

Use **Restore from backup** to move the data to another browser or device.

Logins control which pages and projects each user sees. They are checked inside the browser, so they are not strong security.
