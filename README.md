# ecole-el-emal-management-system
# مدارس الأمل والتقدم الحرة — School CMS

A professional, bilingual (Arabic/French) digital ecosystem for **Al Amal Wa Taqaddom Private Schools** (Toujounine, Nouakchott, Mauritania). This platform serves as the official digital face of the institution, integrating a headless CMS for real-time content management.

**🌐 Live Production Site:** [ecoleelmel.com](https://ecoleelmel.com)

---

## 🚀 Core Capabilities

- **Bilingual Architecture**: Fully implemented RTL (Arabic) and LTR (French) support with a seamless language toggle.
- **Headless CMS Integration**: Powered by Sanity.io, allowing administration to update news, faculty profiles, and school settings without touching the code.
- **Performance Optimized**: Built with Vite and React 18 for near-instant load times and smooth client-side transitions.
- **Modern UX/UI**: Implementation of glassmorphism, Framer Motion animations, and a mobile-first responsive grid.
- **Real-time Sync**: Content updates in the Sanity Studio reflect instantly on the production frontend via highly optimized API queries.

## 🛠️ Technical Stack

- **Frontend**: `React 18`, `Vite`, `Tailwind CSS`, `Framer Motion`
- **Content Management**: `Sanity v3` (Headless CMS)
- **State & Routing**: `React Router v6`, `i18next` for internationalization
- **Infrastructure**: `Vercel` (Edge Network Deployment)
- **Icons & Assets**: `Lucide React`

---

## 🔒 Security & Privacy

To ensure the integrity of the school's data and the security of the infrastructure, the following measures have been implemented:

- **Environment Secret Management**: All sensitive credentials (Project IDs, Dataset tokens) are handled via encrypted environment variables.
- **CORS Policy**: Strict Cross-Origin Resource Sharing (CORS) settings are configured in the Sanity dashboard to allow requests only from the authorized production domain.
- **Content Security**: Implementation of Sanity's Role-Based Access Control (RBAC) to ensure only authorized administrators can modify school data.
- **Secure Deployment**: Deployed via Vercel with automatic SSL encryption (HTTPS) to protect data in transit.

---

## 👨‍💻 Developer Setup (Internal Use Only)

### Prerequisites
- Node.js 18+
- npm or yarn
- Authorized access to the Sanity Project

### Installation & Local Environment
```bash
# Clone the internal repository
git clone <repository-url>
cd school-cms

# Install dependencies
npm install
