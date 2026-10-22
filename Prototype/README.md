# UX/UI Prototype

This Figma prototype shows how employees will manage commercial rental properties, tenants, lease agreements and payments. It covers the main screens and user workflows planned for the system.

[Open the prototype in Figma](https://www.figma.com/design/Jwn9qz6Tmftz7hHpqBdu8o)

## User roles

- **Property Owner** reviews occupancy and financial reports, manages properties, and assigns employee roles.
- **Rental Manager** maintains tenant and lease records, checks space availability for selected dates, and monitors expiring agreements.
- **Accountant** creates charges, records confirmed payments, and checks outstanding balances.

Tenants are stored as records and do not have accounts in the system.

## Main workflows

The prototype demonstrates how a manager finds an available space, selects a tenant and creates a lease. It also includes a date conflict message when the selected rental period overlaps with an existing agreement.

The payment workflow shows how an accountant records a confirmed payment and reviews the remaining balance after a partial payment. Actual receipts are checked separately through bank records or 1C. The proposed system does not connect directly to 1C.

Other screens cover editing property and tenant details, adding charges, reviewing notifications, viewing financial reports and managing employee accounts. Forms include examples of validation errors and successful saves.

The rental price estimate screen shows the planned inputs and result layout. Its displayed amount is a demonstration value; no trained model is connected.

## How to view

Open the Figma file and start presentation mode. Choose a role on the starting screen, then use the buttons and menus to follow its workflows.

The prototype uses sample data and predefined screen transitions. Forms do not save real records, and there is no backend or real authentication at this stage.
