# Healthcare Contact Section - Get in Touch

A modern, responsive React component for healthcare booking platform contact section built with React and Tailwind CSS.

## Features

- 📱 Fully responsive design
- 🎨 Modern UI with Tailwind CSS
- 📝 Interactive contact form with validation
- 📞 Contact information display with icons
- ✨ Smooth animations and hover effects
- 🏥 Healthcare-themed design

## Contact Information Sections

- **Phone Support**: 24/7 available for urgent inquiries
- **Email Support**: Response within 2-4 hours
- **Office Location**: Physical address details
- **Business Hours**: Operating schedule

## Contact Form Features

- First Name and Last Name fields
- Email Address (validated)
- Phone Number
- Subject line
- Message textarea
- Form validation
- Submit with visual feedback

## Installation

1. Install dependencies:
```bash
npm install
```

2. Start the development server:
```bash
npm run dev
```

3. Build for production:
```bash
npm run build
```

## Technologies Used

- React 18
- Tailwind CSS
- Vite (build tool)
- PostCSS
- Heroicons (SVG icons)

## Project Structure

```
src/
  components/
    GetInTouch.jsx    # Main contact section component
  App.jsx             # Main app component
  main.jsx            # Entry point
  index.css           # Tailwind CSS imports
```

## Customization

The component is highly customizable through Tailwind CSS classes. You can easily modify:

- Colors (currently using green theme)
- Spacing and layout
- Typography
- Form styling
- Icons and imagery

## Form Handling

The contact form includes basic state management and console logging. To integrate with a backend:

1. Replace the `handleSubmit` function in `GetInTouch.jsx`
2. Add your API endpoint
3. Implement proper error handling
4. Add success/failure notifications

## License

MIT License