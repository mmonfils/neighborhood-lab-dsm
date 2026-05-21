# The Neighborhood Toolkit 🛠️

This document outlines the operational rules and structural parameters for managing our physical asset database. Rather than tracking deficits or relying on traditional top-down agency surveys, this framework catalogs internal neighborhood capabilities to build true community resilience.

---

## 📋 The Asset Mapping Standard

We map the assets of our immediate street using direct face-to-face conversations. To ensure the process is transparent and standard across any participating block, assets are tracked using four core categories:

* **1. Mechanical & Tool Infrastructure**
    * High-utility physical items owned by individual households that can be shared to keep the block operational during crises.
    * Examples: Snowblowers, chainsaws, vehicle jumper cables, truck hitches, lawnmowers, water pumps, garden tillers, and power tools.
* **2. Emergency Care Capacity**
    * Specialized human skills or institutional knowledge present right on our street.
    * Examples: Certified CPR/First Aid skills, tree removal experience, basic carpentry/roofing repair, small engine mechanics, and fluency in multiple languages.
* **3. Resilient Logistics & Space**
    * Physical properties or localized equipment that can serve as an anchor point during severe weather power outages or infrastructure challenges.
    * Examples: Off-grid backup generators, functioning wood stoves, deep-freeze storage space, large trucks for moving fallen limbs, or a large covered porch for meeting spots.
* **4. Relational & Care Support**
    * Time, presence, and relational capacity dedicated to tracking the well-being of neighbors.
    * Examples: Checking in on elderly or disabled neighbors during an Iowa blizzard, providing short-term emergency childcare, or helping coordinate local communication threads.

---

## 🔒 Security, Privacy & Local Sovereignty

Because this tracker maps the tangible wealth and specific locations of neighborhood tools, keeping the data completely secure and independent is an absolute policy priority.

* **Strict Off-Grid Storage:** This database should live as a local file (such as a shared spreadsheet or physical printout) handled directly by participating block residents. Do not host active datasets with personal phone numbers, house addresses, or tool details on public web repositories or unencrypted corporate platforms.
* **Anti-Surveillance Rule:** Under no circumstances should this asset roster be shared with law enforcement, city code enforcement, property management corporations, or outside marketing firms. It is built strictly for voluntary, cooperative mutual aid among neighbors.
* **No Deficit Assessment:** Do not add data columns to track what residents "need" or lack. Focus entirely on strengths, recognizing that every resident possesses an essential asset to offer the collective resilience of the street.

---

## 📊 Database Schema: `block-toolkit-template.csv`

To keep data management simple and portable across standard spreadsheet software, individual blocks utilize a flat CSV structure using the exact headers defined below:

| Column Name | Data Type | Description & Formatting Rules |
| :--- | :--- | :--- |
| `Household_ID` | Text (e.g., H01, H02) | Anonymous unique tracker to prevent public exposure of house numbers. |
| `Asset_Category` | Dropdown Text | Must be categorized exactly as: *Tool, Skill, Space,* or *Care Network*. |
| `Item_Description` | Text | Clear name of asset (e.g., "24-inch Snowblower", "CPR Certified", "Generator"). |
| `Availability_Notes` | Text | Seasonal or time limits (e.g., "Available weekends", "Winter storm emergency only"). |
| `Primary_Contact` | Text | First name and localized communication handle (e.g., "Dave - Group Text Row 4"). |
| `Last_Verified` | Date (YYYY-MM-DD) | The date this asset entry was confirmed accurate during seasonal porch check-ins. |

---

## 🪵 Maintenance & Verification Schedule

* **The Spring Thaw Check:** Review the data columns every April to audit lawn maintenance tools, gardening assets, and summer storm infrastructure.
* **The Winter Freeze Audit:** Review the rows every October to verify that snowblowers are operational, backup power generators are fueled, and contacts for checking on vulnerable residents are up to date.
