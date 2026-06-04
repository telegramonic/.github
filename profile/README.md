<div align="center">
<!-- <img width="20%" src="https://github.com/user-attachments/assets/fd179a7b-b129-491f-9ace-5f259c382c3d"/>  -->
<h1> Telegramonic </h1>
<img width="15%" src="https://github.com/user-attachments/assets/b0e0eb85-8184-40e4-8127-6f6eade63ab5"/> 
</div>


### 🚀 A high-performance, minimalist cloud storage solution designed for digital craftsmen, developers, and tech professionals.


---

### 🔭 Our Core Pillars

*   **⚡ Native Performance**: Blazing-fast compiled Rust gateway bridging client requests directly to Telegram's MTProto.
*   **🎨 Utility Minimalism**: Sleek, distraction-free interfaces featuring fluid animations and adaptive light/dark visual styling.
*   **💻 Developer Ergonomics**: TypeSafe architecture, robust offline-first caching, and complete command hotkey integrations.

---

### 📂 Workspace Architecture

*   🌐 **web** — Public landing portal, OS-detection downloads, and documentation.
*   💻 **desktop** — Secure Electron shell featuring dashboard navigation and a login wizard.
*   🦀 **server** — Fast Rust Axum server serving as the MTProto API bridge.
*   📦 **common** — Shared design system tokens, localizations, and icons.

<img width="3168" height="1344" alt="Gemini_Generated_Image_5wz0co5wz0co5wz0" src="https://github.com/user-attachments/assets/eb44b3d7-d5ef-42c0-bb45-d1654389506a" />

---

### ⚙️ Frameworks & Tooling

| Layer | Technologies Used |
| :--- | :--- |
| **Frontend** | React 18+, TypeScript 5.x, React Router v7, Zustand v5 |
| **Data Fetching** | TanStack Query v5, TanStack Form v1 |
| **Styling & Motion** | Chakra UI v3, Panda CSS, Framer Motion |
| **Shell & Server** | Electron, Rust (Axum, default port `50065`) |
| **CI / CD** | GitHub Actions, FTP Deploy, Conventional Changelog |

---

### 💎 Design System Spec

*   **Colors**: Telegram Blue (`#0088CC`) accents, Deep Charcoal (`#212529`) text, soft grey surfaces (`#F8F9FA` / `#FFFFFF`).
*   **Geometry**: Modern 8px borders for control buttons/inputs and 16px border-radius for modals.
*   **Adaptability**: Complete native Dark Mode integration supporting automatic system preference detection.

---

### 🤝 Developer Workflow

1.  **Branch Prefixing**: `amitraikwar/TEL-{ticket_number}/{short-description}`
2.  **Conventional Commits**: Commit messages must match `type(scope): message` with detailed descriptions.
3.  **Local Testing**: Ensure everything compiles and passes before pushing: `yarn run-staged-tests`
4.  **Target**: Open Pull Requests directly to the `development` branch.

---

<p align="center">
  Crafted with ❤️ by the Amit Raikwar.
</p>
