# IQ Calculator

A modern web application that evaluates cognitive abilities through interactive tests, providing personalized IQ scores and detailed insights into your cognitive strengths and weaknesses.

![IQ Calculator Screenshot](https://images.unsplash.com/photo-1565711561500-49678a10a63f?auto=format&fit=crop&q=80&w=2070)

## Features

- 🧠 **Comprehensive Cognitive Assessment**
  - Logical reasoning challenges
  - Pattern recognition tests
  - Mathematical aptitude evaluation

- 📊 **Detailed Results Analysis**
  - Personalized IQ score calculation
  - Strength identification
  - Areas for improvement
  - Performance breakdown by category

- 💫 **Modern User Experience**
  - Clean, intuitive interface
  - Real-time progress tracking
  - Smooth transitions between questions
  - Mobile-responsive design

## Tech Stack

- React 18
- TypeScript
- Tailwind CSS
- Lucide React Icons
- Vite

## Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/iq-calculator.git
cd iq-calculator
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:5173`

## Project Structure

```
src/
├── components/         # React components
│   ├── Results.tsx    # Test results display
│   └── TestQuestion.tsx # Question component
├── data/
│   └── questions.ts   # Test questions database
├── types/
│   └── index.ts      # TypeScript definitions
├── App.tsx           # Main application component
└── main.tsx         # Application entry point
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Brain icons provided by [Lucide Icons](https://lucide.dev)
- UI design inspired by modern cognitive assessment tools
- Test questions developed based on standard IQ test patterns