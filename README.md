# PopX

## Technologies Used

- React.js
- React Router for navigation
- CSS3 for styling
- Modern JavaScript (ES6+)

## Getting Started

### Prerequisites

- Node.js (v14.0.0 or higher)
- npm (v6.0.0 or higher)

### Installation

1. Clone the repository:
```bash
gh repo clone LivingWithPaaji/educase-india-assessment
```

2. Navigate to the project directory:
```bash
cd Educase-India-Assessment
```

3. Install dependencies:
```bash
npm install
```

4. Start the development server:
```bash
npm run dev
```

The application will open in your default browser at `http://localhost:3000`.

## Development Workflow

### Available Scripts

In the project directory, you can run:

```bash
npm start        # Runs the app in development mode
npm test         # Launches the test runner
npm run dev      # Builds the app for production
```

## Project Structure

```
src/
├── App.jsx          # Main application component with routing
├── App.css          # Global styles
└── components/      # React components
```

## Features in Detail

### Create Account
- Form validation for required fields
- Input fields for:
  - Full Name
  - Phone Number
  - Email Address
  - Password
  - Company Name
  - Agency selection

### Login
- Email validation
- Dynamic button state changes
- Password field
- Form validation

### Account Settings
- Displays user information
- Profile section
- Back navigation
- Responsive layout

## Styling Guidelines

The project uses a consistent color scheme:
- Primary Color: #7646ff
- Secondary Color: #ede6fd
- Text Colors: #232323, #666
- Background Colors: #fafbfc, #fcfcfc

## Troubleshooting

Common issues and solutions:

1. **Module not found errors**
   - Run `npm install` to ensure all dependencies are installed
   - Clear npm cache: `npm cache clean --force`

2. **Port already in use**
   - Kill the process using the port: `kill -9 $(lsof -t -i:3000)`
   - Or use a different port: `PORT=3001 npm start`

3. **Build errors**
   - Clear build cache: `rm -rf build`
   - Rebuild the project: `npm run build`

### Code Style

- Use consistent indentation (2 spaces)
- Follow React best practices
- Write meaningful commit messages
- Add comments for complex logic
