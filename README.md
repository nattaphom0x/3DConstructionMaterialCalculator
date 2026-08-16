# 🏗️ 3D Construction Material Calculator (Web-Based)

> **Mini Project V1.18: Material Manager (Height Support)**
> A web-based application for estimating construction materials using interactive 3D modeling.

## About The Project (เกี่ยวกับโปรเจกต์)

This project is a **Pre-Graduation Mini Project** developed by 4th-year students from the **Department of Computer Science, Faculty of Liberal Arts and Science, Kasetsart University.**

The application is designed to help users calculate the amount of construction materials (bricks, mortar, sand) required for building walls. It utilizes **Three.js** to provide a real-time 3D visualization, allowing users to draw blueprints, adjust dimensions, and see the exact arrangement of materials before construction.

โปรเจกต์นี้เป็น **มินิโปรเจกต์ก่อนจบการศึกษา (Pre-Graduation)** จัดทำโดยนิสิตชั้นปีที่ 4 **สาขาวิทยาการคอมพิวเตอร์ คณะศิลปศาสตร์และวิทยาศาสตร์ มหาวิทยาลัยเกษตรศาสตร์**

แอปพลิเคชันนี้ถูกพัฒนาขึ้นเพื่อช่วยคำนวณปริมาณวัสดุก่อสร้าง (อิฐ ปูน ทราย) ผ่านการจำลองโมเดล 3 มิติ ผู้ใช้งานสามารถสร้างกำแพง ปรับขนาด และดูการเรียงตัวของอิฐได้จริง พร้อมคำนวณรายการวัสดุ (Bill of Materials) ให้อัตโนมัติ

## Authors (ผู้จัดทำ)

* **Nattaphom Chombrisut (ณัฐภูมิ ชมบริสุทธิ์)**
* **Natnicha Vannachat (ณัฐณิชา วรรณชาติ)**

**Department of Computer Science (CS)** **Faculty of Liberal Arts and Science** **Kasetsart University (Kamphaeng Saen Campus)**

## Key Features (ฟีเจอร์หลัก)

* **Interactive 3D Workspace:** Move, rotate, and scale walls freely in a 3D environment.
* **Material Manager:** Customize material properties (Size W/H/L, Gap, Mortar usage).
    * Supports: Red Brick, Concrete Block, Lightweight Block, and Rammed Earth.
* **Real-time Calculation:**
    * **Visual Count:** Counts the actual number of bricks rendered in 3D.
    * **Standard Formula:** Calculates based on area (m²) and volume (m³) for purchasing.
* **Blueprint Mode:** Draw 2D floor plans and extrude them into 3D walls instantly.
* **Visualizer Mode:** Toggle between "Solid Wall" view and "Real Unit" view (shows individual bricks stacked).
* **Bill of Materials (BOM):** Generates a summary report of all materials needed for the project.

## Technologies Used (เทคโนโลยีที่ใช้)

* **HTML5 / CSS3** (Responsive GUI)
* **JavaScript (ES6 Modules)**
* **Three.js** (3D Rendering Engine)
    * `OrbitControls` for camera movement.
    * `TransformControls` for object manipulation.
    * `CSS2DRenderer` for floating labels.

## How to Run (วิธีใช้งาน)

Since this project uses ES6 Modules, you need a local server to run it properly (to avoid CORS errors).

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/NattaphomGitHu/3DConstructionMaterialCalculator.git](https://github.com/NattaphomGitHu/3DConstructionMaterialCalculator.git)
    ```
2.  **Open the project folder.**
3.  **Run with a local server:**
    * **VS Code:** Install the "Live Server" extension, right-click `index.html`, and select "Open with Live Server".
    * **Python:** Run `python -m http.server` in the terminal and open `localhost:8000`.
    * **Node.js:** Use `http-server` or similar packages.

##Screenshots
![Program Interface](path/to/screenshot.png)

---
*Created as part of the CS curriculum, Kasetsart University.*
