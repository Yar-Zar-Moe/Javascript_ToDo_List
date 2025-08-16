# 📝 To-Do List Application

See my project here - https://todolistappwithjs.netlify.app/

A modern, responsive to-do list application built with vanilla JavaScript, HTML5, and CSS3. Features a clean, intuitive interface with local storage persistence, task filtering, and real-time statistics.

## ✨ Features

- **📱 Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices
- **💾 Local Storage** - Tasks persist between browser sessions
- **🔍 Smart Filtering** - Filter tasks by status (All, Pending, Completed)
- **📊 Real-time Statistics** - Live task counters and progress tracking
- **✏️ Task Management** - Add, edit, delete, and mark tasks as complete
- **🎨 Modern UI** - Beautiful gradient design with smooth animations
- **🔔 Notifications** - Visual feedback for all user actions
- **⌨️ Keyboard Support** - Enter key support for quick task addition

## 🚀 Quick Start

1. **Clone or download** the project files
2. **Open** `index.html` in your web browser
3. **Start adding tasks** - no setup required!

## 🎯 Usage

### Adding Tasks
- Type your task in the input field
- Press **Enter** or click the **+** button
- Tasks are automatically saved to local storage

### Managing Tasks
- **Complete**: Click the checkbox to mark as done
- **Edit**: Click the edit icon (✏️) to modify task text
- **Delete**: Click the trash icon (🗑️) to remove a task

### Filtering Tasks
Use the filter buttons to view:
- **All** - Shows all tasks
- **Pending** - Shows only incomplete tasks
- **Completed** - Shows only finished tasks

### Bulk Actions
- **Clear Completed** - Remove all completed tasks at once

## 🛠️ Technical Details

### Built With
- **HTML5** - Semantic markup and accessibility
- **CSS3** - Flexbox, Grid, and modern styling
- **Vanilla JavaScript** - ES6+ features, no external dependencies
- **Font Awesome** - Icons for enhanced UI
- **Google Fonts** - Poppins font family

### Browser Support
- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers (iOS Safari, Chrome Mobile)

### File Structure
```
todo-list/
├── index.html      # Main HTML structure
├── styles.css      # Styling and responsive design
├── script.js       # Application logic and functionality
└── README.md       # Project documentation
```

## 🎨 Design Features

### Color Scheme
- **Primary**: Purple gradient (#667eea → #764ba2)
- **Accent**: Gold (#ffc107) for edit actions
- **Danger**: Red (#dc3545) for delete actions
- **Success**: Green (#28a745) for notifications

### Responsive Breakpoints
- **Mobile**: < 480px (single column layout)
- **Tablet**: 481px - 768px (optimized grid)
- **Desktop**: > 768px (full features)

### Animations
- Smooth slide-in effects for new tasks
- Hover transitions for interactive elements
- Notification pop-ups with slide animation

## 🔧 Customization

### Styling
Edit `styles.css` to customize:
- Color scheme (update gradient values)
- Font family (change Google Fonts import)
- Spacing and sizing (CSS variables)
- Animation timing

### Functionality
Modify `script.js` to:
- Change task character limit (currently 50)
- Add due dates or priorities
- Implement categories or tags
- Add drag-and-drop reordering

## 📱 Mobile Experience

The application is fully optimized for mobile devices with:
- Touch-friendly buttons (minimum 44x44px)
- Responsive typography using `clamp()`
- Flexible layouts that adapt to screen size
- Swipe-friendly task items

## 🐛 Troubleshooting

### Common Issues

**Tasks not saving?**
- Check if localStorage is enabled in your browser
- Try refreshing the page
- Check browser console for errors

**Layout looks broken?**
- Ensure all files are in the same directory
- Check if CSS file is properly linked
- Try clearing browser cache

**Notifications not showing?**
- Ensure JavaScript is enabled
- Check if browser blocks pop-ups

## 🤝 Contributing

Feel free to fork and improve! Some ideas:
- Add task categories/tags
- Implement task priorities
- Add dark mode toggle
- Export tasks to CSV/JSON
- Add task search functionality
- Implement recurring tasks

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙋‍♂️ Support

If you encounter any issues or have suggestions:
1. Check the troubleshooting section above
2. Open an issue on GitHub (if available)
3. Contact the project maintainer

---

**Made with ❤️ using vanilla JavaScript**
