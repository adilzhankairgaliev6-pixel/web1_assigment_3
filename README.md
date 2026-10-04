# Assignment #3. Responsive Web Design

## Student Information
- Name: Adilzhan Kairgaliyev
- Group: SE-2540

---

## Project Overview
In this lab assignment, I built a responsive e-commerce web application (StrideHouse). Here, I practiced working with Media Queries, flexible containers, a custom 12-column grid system, a responsive navbar, and portfolio blocks adapted for different screens (mobiles, tablets, PCs).

---

## Tasks & Assignments

### Part 1. Media Queries

- Task 0. Responsive Typography
- What I did: Made headings and text dynamically change their font size depending on the device used to open the page (phone, tablet, or computer).
- Screenshot:
<img width="959" height="868" alt="image" src="https://github.com/user-attachments/assets/e4ba1e77-fea8-4f7e-bc63-4bd44959fbf5" />
<img width="533" height="695" alt="image" src="https://github.com/user-attachments/assets/adc942bc-2491-4d07-b57e-95df324c8760" />

- Task 1. Responsive Layout (without Bootstrap)
- What I did: Created three blocks ("Free Shipping", "100% Authentic", "Easy Returns"). On a computer, they stand in a single row; on a tablet, two per row; on a phone, they stack vertically one under another.
- Screenshot:
<img width="951" height="233" alt="image" src="https://github.com/user-attachments/assets/ad61c249-d071-4253-a172-0824489f22f5" />
<img width="695" height="287" alt="image" src="https://github.com/user-attachments/assets/1862f592-576b-4e1f-ad82-0bdd472975e1" />
<img width="403" height="643" alt="image" src="https://github.com/user-attachments/assets/e45be184-e0bb-4467-979a-4c541c932531" />

### Part 2. Grid System

- Task 2. Responsive Columns
- What I did: Created category blocks using a 12-column grid. On desktop, they divide the width into 3 equal parts (`col-lg-4`); on tablet, the first two go side-by-side while the third drops to the second row (`col-md-12`); on mobile, everything goes into a single column (`col-12`).
- Screenshot:
<img width="396" height="537" alt="image" src="https://github.com/user-attachments/assets/b83b78a1-56c1-4170-a933-490cef850dd3" />
<img width="962" height="451" alt="image" src="https://github.com/user-attachments/assets/b92dc603-45d7-4933-a6db-89a909caa1c3" />
<img width="984" height="234" alt="image" src="https://github.com/user-attachments/assets/9f7b6f8a-5adf-4d81-aefb-bf8dce4c5700" />

- Task 3. Responsive Navigation Bar
- What I did: Built a website header with a logo on the left and links on the right. On smaller screens, the menu hides and opens when clicking the hamburger icon (implemented via a checkbox without JavaScript).
- Screenshot:
<img width="968" height="123" alt="image" src="https://github.com/user-attachments/assets/01def1e1-87c8-408c-b054-5d9b3f9f2e91" />
<img width="958" height="286" alt="image" src="https://github.com/user-attachments/assets/60679290-a063-4fd4-959a-4fed2b4cc919" />
<img width="423" height="290" alt="image" src="https://github.com/user-attachments/assets/6fc1d641-c674-4631-b81c-b824c1416e3b" />

### Part 3. Combined Project

- Task 4. Portfolio / Catalog Page
- What I did: Assembled a comprehensive page combining the navbar, product card grid on the left, sidebar with filters/info on the right, and a footer at the bottom. Added media queries so that extra text in the sidebar hides on mobile devices for a clean look.
- Screenshot:
<img width="1904" height="1035" alt="image" src="https://github.com/user-attachments/assets/c86508d8-e3ca-4391-9946-1f6981f91c3a" />
<img width="952" height="925" alt="image" src="https://github.com/user-attachments/assets/eb304a98-2e69-4c2c-987d-5737e6dad754" />
<img width="394" height="915" alt="image" src="https://github.com/user-attachments/assets/2a1de2ab-79ce-4bcd-bcc3-e38879dbd8b6" />

---

## Workflow Process
1. Created the file structure `index.html` and `style.css`, linked fonts and the viewport meta tag.
2. Wrote styles with media queries for text and blocks (Tasks 0 and 1).
3. Coded grid blocks for categories and products (Task 2).
4. Added the interactive hamburger navbar (Task 3).
5. Assembled the final store section and checked layout scaling via browser developer tools.
