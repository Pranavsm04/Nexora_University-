# Nexora University Website

A modern, responsive university website built with Next.js 15, React, and Tailwind CSS.

## Overview

Nexora University is a comprehensive institutional website featuring multiple sections for different audiences including students, faculty, families, visitors, and alumni. The website showcases the university's academics, research, healthcare services, campus life, athletics, and admissions.

## Features

### Main Sections
- **Hero Section** - Dynamic landing with university branding
- **About** - University mission and overview
- **Academics** - Academic programs and schools
- **Research** - Research initiatives and centers
- **Healthcare** - University health services
- **Campus Life** - Student experience and activities
- **Athletics** - Sports programs and facilities
- **Admissions** - Application information with interactive form
- **Events** - Upcoming university events
- **News** - Latest university news and announcements

### Audience Pages
- **Students** - Resources and information for current students
- **Faculty & Staff** - Tools and resources for employees
- **Families** - Information for parents and families
- **Visitors** - Campus visit information and tours
- **Alumni** - Alumni network and engagement

### Interactive Features
- **Chatbot** - AI-powered assistant for common questions about admissions, programs, campus life, and more
- **Application Modal** - Interactive admission application form with name, email, phone, and address fields
- **Smooth Scroll Animations** - Content reveals on scroll for engaging user experience
- **Mobile Responsive** - Fully responsive design for all device sizes

## Tech Stack

- **Framework**: Next.js 15 (App Router)
- **UI Library**: React 19
- **Styling**: Tailwind CSS v4
- **Components**: shadcn/ui
- **Icons**: Lucide React
- **Fonts**: Playfair Display (serif), Inter (sans-serif)
- **Theme**: next-themes for dark/light mode support

## Project Structure

```
├── app/
│   ├── page.tsx              # Main homepage
│   ├── layout.tsx            # Root layout
│   ├── globals.css           # Global styles
│   ├── students/page.tsx     # Students page
│   ├── faculty/page.tsx      # Faculty & Staff page
│   ├── families/page.tsx     # Families page
│   ├── visitors/page.tsx     # Visitors page
│   └── alumni/page.tsx       # Alumni page
├── components/
│   ├── hero-section.tsx      # Landing hero component
│   ├── scroll-sections.tsx   # All scrollable sections
│   ├── chatbot.tsx           # AI chatbot component
│   ├── theme-provider.tsx    # Theme context provider
│   └── ui/                   # shadcn/ui components
├── public/
│   └── images/               # Static images
├── hooks/                    # Custom React hooks
└── lib/                      # Utility functions
```

## Getting Started

### Prerequisites
- Node.js 18+ 
- pnpm (recommended) or npm

### Installation

1. Clone the repository
```bash
git clone <repository-url>
cd nexora-university
```

2. Install dependencies
```bash
pnpm install
```

3. Run the development server
```bash
pnpm dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser

## Scripts

- `pnpm dev` - Start development server
- `pnpm build` - Build for production
- `pnpm start` - Start production server
- `pnpm lint` - Run ESLint

## Design System

### Colors
- **Primary**: Stone palette (stone-900, stone-800, etc.)
- **Background**: White and stone-50
- **Text**: Stone-900 (headings), stone-600 (body)
- **Accents**: White buttons on dark backgrounds

### Typography
- **Headings**: Playfair Display (serif)
- **Body**: Inter (sans-serif)

## Authors

Published by **Pranav SM**, **Vignesh MS**, and **Neha Shenoy A**

## License

© 2026 Nexora University. All rights reserved.
