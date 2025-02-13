Here's a **README.md** file for your **YC Directory Clone** project. It provides an overview, the tech stack, and feature explanations. Let me know if you need any modifications!

---

### `README.md`

```md
# YC Directory Clone  

A **YC Directory Clone** built using Next.js 15, Sanity, and modern full-stack technologies. This application allows users to browse and submit startups, view detailed startup profiles, and interact with real-time data updates.  

## 🚀 Features  

### 🌍 Startup Listing  
- Displays a list of startups dynamically fetched from **Sanity CMS**.  
- Real-time updates: New startups appear instantly without page refresh.  
- Search and filter functionality based on startup name, category, or author.  

### 🏗️ Startup Details  
- Each startup has a dedicated profile page with an **image, description, founder details, and pitch**.  
- Data is **pre-rendered using Next.js 15’s advanced rendering strategies** for optimal performance.  

### 🔐 Authentication  
- OAuth-based authentication with **NextAuth.js**.  
- Users can sign in with Google and access personalized content.  

### ✏️ Startup Submission  
- Users can submit their own startups via a form powered by **React Server Actions**.  
- Rich text editor for startup pitches.  
- Real-time validation and feedback using **useActionState** hook.  

### 🖥️ Dynamic & Static Rendering  
- Next.js optimizations:  
  - **Server Components** for direct database interaction.  
  - **Static & Dynamic Rendering Hybrid** for performance.  
  - Suspense boundaries for handling async operations smoothly.  

### 📊 User Profiles  
- Dynamic profile pages for users, showing their submitted startups.  
- Server-side fetching for optimized data loading.  

### 🛠️ Error Handling & Monitoring  
- Global and route-specific **error boundaries** to catch and display errors gracefully.  
- Integrated with **Sentry** for real-time monitoring and debugging.  

### 🚢 Deployment & Performance  
- Fully deployed on **Vercel** for seamless scalability.  
- Optimized image loading using Next.js **Image component**.  

## 🛠️ Tech Stack  

| Technology     | Purpose |
|---------------|---------|
| **Next.js 15** | Full-stack framework |
| **React 19** | UI Components & Server Actions |
| **Sanity CMS** | Headless CMS for startups database |
| **NextAuth.js** | Authentication (Google OAuth) |
| **Tailwind CSS** | Styling |
| **TypeScript** | Type safety |
| **Vercel** | Deployment |
| **Sentry** | Error monitoring |

## 📦 Project Structure  

```
/yc-directory-clone  
│── /app           # Main application folder  
│── /components    # Reusable UI components  
│── /lib           # Utility functions & API clients  
│── /public        # Static assets  
│── /sanity        # CMS configurations  
│── /styles        # Global styles  
│── /types         # TypeScript types  
│── /pages         # Next.js route pages  
│── next.config.js # Next.js configurations  
│── tailwind.config.js # Tailwind CSS setup  
│── .env.local     # Environment variables  
│── package.json   # Dependencies & scripts  
│── README.md      # Project documentation
```

## 🔧 Installation & Setup  

1. **Clone the repository**  
   ```sh
   git clone https://github.com/yourusername/yc-directory-clone.git  
   cd yc-directory-clone  
   ```

2. **Install dependencies**
   ```sh
   npm install  
   ```

3. **Set up environment variables**
    - Create a `.env.local` file and configure required API keys.

4. **Run the development server**
   ```sh
   npm run dev  
   ```
   Open [http://localhost:3000](http://localhost:3000) in your browser.

5. **Deploy to Vercel**
   ```sh
   vercel  
   ```

## 📜 License

This project is licensed under the MIT License.

---

Let me know if you need any modifications! 🚀
```