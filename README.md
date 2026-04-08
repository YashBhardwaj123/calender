# 📅 Interactive Wall Calendar

A beautiful, interactive wall calendar built with React, featuring smooth page-flip animations, date range selection, and persistent notes storage.

![Calendar Preview](https://images.unsplash.com/photo-1506744038136-46273834b3fb?q=80&w=1000&auto=format&fit=crop&ixlib=rb-4.0.3)

## ✨ Features

- **📆 Interactive Calendar**: Click dates to select ranges with visual highlighting
- **🎨 Page Flip Animation**: Smooth slide transitions when changing months
- **📝 Notes System**: Add month-specific and range-specific notes
- **💾 Persistent Storage**: Notes saved to localStorage
- **📱 Responsive Design**: Works on desktop and mobile devices
- **🎭 Modern UI**: Clean design with Tailwind CSS and custom styling

## 🚀 Live Demo

View the live calendar: [GitHub Pages Link](https://yashbhardwaj123.github.io/calender/)

## 🛠️ Technologies Used

- **React 18** - Component-based UI
- **Tailwind CSS** - Utility-first CSS framework
- **date-fns** - Modern JavaScript date utility library
- **Babel** - JavaScript transpiler for JSX
- **LocalStorage** - Client-side data persistence

## 📖 How to Use

1. **Navigate Months**: Use the arrow buttons to move between months
2. **Select Dates**: Click on dates to select a start date, then click another to create a range
3. **Add Notes**:
   - **Month Notes**: General notes for the entire month
   - **Range Notes**: Specific notes for selected date ranges
4. **Data Persistence**: Your notes are automatically saved and will persist between sessions

## 🏃‍♂️ Running Locally

Since this is a single HTML file with inline scripts, you can simply:

1. Download `index.html`
2. Open it in any modern web browser
3. No server required!

For development:
```bash
# Clone the repository
git clone https://github.com/YashBhardwaj123/calender.git
cd calender

# Open index.html in your browser
# Or serve with a local server for better experience
python -m http.server 8000
# Then visit http://localhost:8000
```

## 🎯 Key Components

- **Date Selection**: Visual feedback with blue highlighting for selected ranges
- **Animation System**: CSS-based slide animations for month transitions
- **Notes Management**: Separate storage for general and range-specific notes
- **Responsive Layout**: Adapts to different screen sizes

## 📸 Screenshots

### Main Calendar View
- Beautiful mountain background with month/year overlay
- Clean calendar grid with hover effects
- Navigation arrows for month switching

### Date Range Selection
- Start date: Blue background with white text
- Range: Light blue highlighting
- End date: Blue background with white text

### Notes Section
- Month notes textarea
- Range-specific notes (appears when dates are selected)
- Auto-save functionality

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Unsplash** for the beautiful background image
- **Tailwind CSS** for the amazing utility classes
- **date-fns** for robust date handling
- **React** for the component architecture
