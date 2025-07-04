# Web3 Harbour Landing Page Duplicate

This is a React-based duplicate of the Web3 Harbour landing page (https://www.web3harbour.org/).

## Features

- Responsive design matching the original website
- Dark theme with cyan accents
- All original content and sections included
- Partner logos and team member information
- Newsletter signup functionality
- Mobile-friendly navigation

## Setup Instructions

1. **Extract the project files:**
   ```bash
   tar -xzf web3harbour-duplicate.tar.gz
   cd web3harbour-duplicate
   ```

2. **Install dependencies:**
   ```bash
   npm install
   # or
   pnpm install
   ```

3. **Start the development server:**
   ```bash
   npm run dev
   # or
   pnpm run dev
   ```

4. **Open your browser:**
   Navigate to `http://localhost:5173` to view the website.

## Project Structure

```
web3harbour-duplicate/
├── public/                 # Static assets
├── src/
│   ├── assets/            # Images and logos
│   ├── components/        # React components
│   │   └── ui/           # UI components from shadcn/ui
│   ├── App.jsx           # Main application component
│   ├── App.css           # Styles and Tailwind configuration
│   └── main.jsx          # Application entry point
├── package.json          # Dependencies and scripts
└── index.html            # HTML template
```

## Technologies Used

- **React** - Frontend framework
- **Vite** - Build tool and development server
- **Tailwind CSS** - Utility-first CSS framework
- **shadcn/ui** - UI component library
- **Lucide React** - Icon library

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## Customization

The main component is located in `src/App.jsx`. You can modify:

- Colors and styling in `src/App.css`
- Content and layout in `src/App.jsx`
- Images in `src/assets/`

## Deployment

To deploy the website:

1. Build the project: `npm run build`
2. The built files will be in the `dist/` directory
3. Deploy the `dist/` directory to your hosting provider

## Notes

- All images from the original website have been extracted and included
- The design is responsive and works on mobile devices
- Hover effects and transitions are included for better user experience
- The newsletter signup form is styled but not connected to a backend service

