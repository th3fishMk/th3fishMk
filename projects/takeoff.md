# Nereid Learning Projects (September → December 2025)

A set of **10 focused projects** designed to teach Rust, Tauri, and Vue while building skills directly useful for Nereid.

## **Rust + Tauri Projects (Backend & Systems)**

1. **Excel → CSV Converter (Rust + Tauri)**  
   - Read Excel files and convert sheets to CSV.  
   - Use Tauri API for desktop file dialogs.  
   - **Purpose:** Practicing file I/O

2. **Local Database CRUD App**  
   - Implement CRUD operations for “products” and “clients” using SQLite or Postgres.  
   - Connect backend with Tauri API calls.  
   - **Purpose:** Foundation for Inventory system.

3. **Simple POS Terminal Simulation**  
   - CLI-based Rust app: add products, calculate totals, print receipts.  
   - **Purpose:** Core POS logic practice.

4. **Networking – Local LAN Sync Prototype**  
   - Sync JSON data (inventory/products) between two machines over LAN.  
   - Handle conflict resolution.  
   - **Purpose:** Prepares for Phase 3 multi-terminal sync.

5. **License Validator / Offline Key Check**  
   - Rust app checking hardware ID + license key.  
   - Optional periodic “fairness check.”  
   - **Purpose:** Builds understanding for Phase 1/4 licensing.

## **Vue + Frontend Projects (Interface & UI)**

1. **Inventory Table Component**  
   - Vue table with filtering, sorting, and inline updates.  
   - Bind data to JSON mock data.  
   - **Purpose:** Core Inventory UI practice.

2. **POS Checkout UI Prototype**  
   - Vue interface with product list, quantity selector, checkout button.  
   - Reactive total calculation and discounts.  
   - **Purpose:** POS interface foundation.

3. **Dashboard Mini Charts**  
   - Use Chart.js or ApexCharts to display:
     - Sales over time  
     - Low-stock alerts  
     - Membership counts  
   - **Purpose:** Dashboard integration and charting practice.

4. **Localization Toggle**  
   - Vue component to switch languages dynamically using i18n plugin.  
   - Include English + Spanish example texts.  
   - **Purpose:** Multi-language UI.

5. **Plugin Loader / Modular UI Skeleton**  
    - Vue interface that “loads modules” from JSON configuration.  
    - Show/hide Inventory, POS, or Dashboard modules.  
    - **Purpose:** Prepares for Phase 3 modular/plugin system.

---

## **Optional Challenge Project**

- **Combine Rust + Vue → Mini Module**
  - Read Excel → CSV in Rust.  
  - Display and edit in Vue table with filtering/sorting.  
  - Save edits back to CSV/JSON.  
  - **Purpose:** Integrates backend, frontend, file I/O, and Tauri experience.
