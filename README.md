# Tap to Forget

A React + TypeScript application designed to help elderly users and people with ADHD by providing reminders, voice notes, and quick recaps — empowering memory assistance in a simple and accessible way.

---

## Frontend Framework

- **React 18.3.1** with **TypeScript**  
- **Vite** as the build tool and development server

## Styling

- **Tailwind CSS** for utility-first styling  
- Custom fonts from **Google Fonts**: *Exo 2* and *Poppins*

## UI Components and Animation

- **Lucide React** for crisp, customizable icons  
- **@lottiefiles/react-lottie-player** for smooth, engaging animations  
- **react-hot-toast** for non-intrusive toast notifications

## Document Generation

- **jsPDF** to generate PDF certificates for user achievements

## Browser APIs

- **Web Speech API (SpeechRecognition)** for voice input and commands  
- **Web Audio API** for sound effects to enhance user experience

## State Management

- **React Context API** for managing global app state  
- React hooks: `useState`, `useEffect`, `useRef`, and `useContext`

## Development Tools

- **TypeScript** for static type checking and safer code  
- **ESLint** for code linting and maintaining code quality  
- **PostCSS** with **autoprefixer** for vendor prefixing in CSS

## Build & Deployment

- **Vite** for fast bundling and optimized builds  
- TypeScript configurations tailored for both app runtime and Node.js environments

---

## Features

- Add and manage reminders with easy inputs
- Voice notes and recognition to store and recall important details
- PDF certificate generation upon milestones
- Interactive UI with smooth animations and sound feedback
- Responsive design with accessible fonts and icons

## Challenges Faced

- Integrating Web Speech API consistently across browsers
- Managing global state efficiently with React Context
- Handling PDF generation dynamically with jsPDF
- Optimizing build with Vite and fixing deployment issues on Netlify

## License
- MIT License © Harsh Sawant

## Acknowledgments
- Built with Bolt.new and powered by React, Vite, and open web technologies.
