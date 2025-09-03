# 🛠️ CRUD App with Next.js & Radix UI
A modern, full-featured CRUD (Create, Read, Update, Delete) application built with 
**Next.js 15**, **React 18**, and **TypeScript**.
This project demonstrates all essential database operations with a beautiful, responsive UI powered by **Radix UI** components and **Tailwind CSS**.

![Next.js](https://img.shields.io/badge/Next.js-15.5.2-black)
![React](https://img.shields.io/badge/React-18.3.1-blue)
![TypeScript](https://img.shields.io/badge/TypeScript-5-blue)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-4.1.9-38B2AC)
![License](https://img.shields.io/badge/license-MIT-green)

## ✨ Features

- 🚀 **Complete CRUD Operations**
  - ➕ **CREATE** - Add new records with form validation
  - 👁️ **READ** - View and search through data
  - ✏️ **UPDATE** - Edit existing records seamlessly  
  - 🗑️ **DELETE** - Remove records with confirmation dialogs

- 🎨 **Modern UI/UX**
  - Responsive design that works on all devices
  - Beautiful animations and transitions
  - Accessible components built with Radix UI

- 🛠️ **Developer Experience**
  - Full TypeScript support
  - Form validation with React Hook Form + Zod
  - Component-based architecture
  - Clean, maintainable code structure

- 📊 **Rich Components**
  - Data visualization with Recharts
  - Interactive forms and dialogs
  - Toast notifications with Sonner
  - Loading states and error handling

## 🛠️ Tech Stack

### Frontend
- **Framework**: [Next.js 15](https://nextjs.org/) - React framework with App Router
- **Language**: [TypeScript](https://www.typescriptlang.org/) - Type-safe JavaScript
- **Styling**: [Tailwind CSS 4](https://tailwindcss.com/) - Utility-first CSS framework
- **UI Components**: [Radix UI](https://www.radix-ui.com/) - Unstyled, accessible components
- **Icons**: [Lucide React](https://lucide.dev/) - Beautiful & consistent icons

### Forms & Validation
- **Forms**: [React Hook Form](https://react-hook-form.com/) - Performant forms library
- **Validation**: [Zod](https://zod.dev/) - TypeScript-first schema validation
- **Resolvers**: [@hookform/resolvers](https://github.com/react-hook-form/resolvers) - Form validation resolvers

### Data & State
- **Charts**: [Recharts](https://recharts.org/) - Composable charting library
- **Dates**: [date-fns](https://date-fns.org/) - Modern date utility library
- **Notifications**: [Sonner](https://sonner.emilkowal.ski/) - Toast notifications

## 🚀 Getting Started

### Prerequisites

- **Node.js** 18.0 or later
- **npm** or **yarn** package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/diorsolutions/curd-advanced-example.git
   cd my-crud-app
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Run the development server**
   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. **Open your browser**
   
   Navigate to [http://localhost:3000](http://localhost:3000) to see the application.

## 📝 Available Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | Start development server with hot reload |
| `npm run build` | Build the application for production |
| `npm run start` | Start the production server |
| `npm run lint` | Run ESLint to check code quality |

## 🏗️ Project Structure

```
my-crud-app/
├── app/                    # Next.js App Router pages
├── components/             # Reusable React components
│   ├── ui/                # Radix UI components
│   └── forms/             # Form components
├── lib/                   # Utility functions and configurations
├── public/                # Static assets
├── styles/                # Global styles and Tailwind config
└── types/                 # TypeScript type definitions
```

## 🎯 CRUD Operations

### Create (Add New Records)
- Interactive forms with real-time validation
- User-friendly error messages
- Success confirmations

### Read (View Data)
- Sortable and filterable data tables
- Search functionality
- Pagination support
- Responsive card/list views

### Update (Edit Records)
- Pre-populated forms
- Inline editing capabilities
- Optimistic updates
- Change tracking

### Delete (Remove Records)
- Confirmation dialogs
- Bulk delete operations
- Soft delete options
- Undo functionality

## 🎨 UI Components

This project includes a comprehensive set of UI components:

- **Layout**: Navigation, Sidebars, Headers
- **Forms**: Input fields, Select dropdowns, Checkboxes, Radio buttons
- **Feedback**: Alerts, Toasts, Progress bars, Loading spinners  
- **Overlays**: Modals, Popovers, Tooltips, Dropdowns
- **Data Display**: Tables, Cards, Avatars, Badges
- **Navigation**: Tabs, Breadcrumbs, Pagination

## 🌙 Theme Support

The application supports both light and dark themes:

- Automatic system theme detection
- Manual theme switching
- Persistent theme preferences
- Smooth theme transitions

## 🔧 Customization

### Adding New CRUD Operations

1. Create your data model types in `types/`
2. Build form components in `components/forms/`
3. Add validation schemas using Zod
4. Implement CRUD logic in your page components
5. Style with Tailwind CSS classes

### Styling

- Modify `tailwind.config.js` for custom design tokens
- Update component styles in the `components/ui/` directory
- Add global styles in `app/globals.css`

## 📱 Responsive Design

- **Mobile-first** approach
- Breakpoints: `sm` (640px), `md` (768px), `lg` (1024px), `xl` (1280px)
- Touch-friendly interface elements
- Optimized for all screen sizes

## ⚡ Performance

- **Next.js 15** App Router for optimal performance
- **Server-side rendering** and **static generation**
- **Code splitting** and **lazy loading**
- **Image optimization** built-in
- **Bundle analysis** and optimization

## 🤝 Contributing

We welcome contributions! Please follow these steps:

1. **Fork** the repository
2. **Create** a feature branch: `git checkout -b feature/amazing-feature`
3. **Commit** your changes: `git commit -m 'Add amazing feature'`
4. **Push** to the branch: `git push origin feature/amazing-feature`
5. **Open** a Pull Request

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Next.js Team](https://nextjs.org/) - Amazing React framework
- [Radix UI](https://www.radix-ui.com/) - Accessible component primitives  
- [Tailwind CSS](https://tailwindcss.com/) - Utility-first CSS framework
- [Vercel](https://vercel.com/) - Deployment platform

## 📞 Support

If you have any questions or need help:

- 📧 **Email**: your.email@example.com
- 💬 **Issues**: [GitHub Issues](https://github.com/diorsolutions/curd-advanced-example/issues)
- 📖 **Documentation**: [Wiki](https://github.com/diorsolutions/curd-advanced-example/wiki)

---

⭐ **Star this repo** if you found it helpful!
