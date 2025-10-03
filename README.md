
A modern, cross-platform mobile application built with React Native and Expo for tracking daily water intake and maintaining healthy hydration habits.

## �� Features

### Core Functionality
- **Daily Water Tracking**: Log water intake with customizable amounts
- **Progress Visualization**: Beautiful circular progress indicator showing daily goal completion
- **Quick Add Buttons**: Predefined amounts (250ml, 500ml, 750ml, 1000ml) for easy logging
- **Customizable Daily Goals**: Set your personal hydration target (default: 2000ml)

### History & Analytics
- **Weekly Progress Chart**: Visual representation of your hydration patterns
- **Daily History**: Detailed view of water intake entries with edit/delete capabilities
- **Historical Data**: Track your progress over time with comprehensive statistics

### Achievement System
- **Gamification**: Unlock badges and achievements for consistent hydration
- **Progress Tracking**: Monitor achievements like "First Drop", "Goal Crusher", "Week Warrior"
- **Motivation**: Stay engaged with visual progress indicators and unlockable content

### Reminders & Notifications
- **Smart Reminders**: Pre-configured daily reminders for optimal hydration timing
- **Customizable Schedule**: Enable/disable reminders and set custom times
- **Notification Sounds**: Choose from different alert sounds for reminders

### Settings & Customization
- **Personal Goals**: Adjust daily water intake targets
- **Data Management**: Export your hydration data or reset all information
- **App Preferences**: Customize notification sounds and app behavior

## 🛠️ Technology Stack

- **Framework**: React Native with Expo
- **Navigation**: Expo Router for seamless screen transitions
- **State Management**: React hooks with AsyncStorage for local data persistence
- **UI Components**: Custom-built components with consistent design system
- **Charts**: React Native Chart Kit for data visualization
- **Icons**: Expo Vector Icons for consistent iconography

## 📱 Screens

### Home Screen (`/app/index.tsx`)
- Main dashboard with water progress circle
- Quick add buttons for common amounts
- Today's statistics and recent achievements
- Navigation to other app sections

### History Screen (`/app/history.tsx`)
- Weekly progress chart visualization
- Daily breakdown of water intake
- Historical data with edit/delete capabilities
- Period selection (week/month view)

### Achievements Screen (`/app/achievements.tsx`)
- Achievement badges and progress tracking
- Recently unlocked achievements
- Progress indicators for ongoing challenges

### Settings Screen (`/app/settings.tsx`)
- Daily goal configuration
- Notification sound preferences
- Data export and reset options
- Hydration tips and app information

### Reminders Screen (`/app/reminders.tsx`)
- Daily reminder management
- Enable/disable individual reminders
- Custom reminder creation (planned feature)
- Hydration tips and best practices

## �� Design System

### Color Palette
- **Primary**: `#2196F3` (Vibrant Blue)
- **Secondary**: `#1976D2` (Darker Blue)
- **Accent**: `#64B5F6` (Light Blue)
- **Background**: `#F8FAFE` (Light blue-white)
- **Text**: `#263238` (Dark gray)
- **Success**: `#4CAF50` (Green)
- **Error**: `#F44336` (Red)

### Components
- **WaterProgress**: Circular progress indicator with water icon
- **QuickAddButtons**: Predefined amount buttons for quick logging
- **TodayStats**: Detailed breakdown of today's entries
- **AchievementBadge**: Visual achievement indicators
- **WeeklyChart**: Chart component for historical data
- **Button**: Consistent button component with multiple variants

## 📊 Data Structure

### Water Entry
```typescript
interface WaterEntry {
  id: string;
  amount: number;
  timestamp: number;
  date: string;
}
```

### Achievement
```typescript
interface Achievement {
  id: string;
  title: string;
  description: string;
  icon: string;
  unlocked: boolean;
  progress?: number;
  target?: number;
  unlockedDate?: string;
}
```

### Reminder
```typescript
interface Reminder {
  id: string;
  time: string;
  enabled: boolean;
  label: string;
}
```

## 🚀 Getting Started

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn
- Expo CLI (`npm install -g @expo/cli`)

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd water-hydrate
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Run on your device**
   - Install Expo Go app on your mobile device
   - Scan the QR code from the terminal
   - Or run on simulator: `npm run ios` or `npm run android`

### Available Scripts

- `npm run dev` - Start development server with tunnel
- `npm run android` - Run on Android device/emulator
- `npm run ios` - Run on iOS device/simulator
- `npm run web` - Run in web browser
- `npm run build:web` - Build for web deployment
- `npm run build:android` - Build Android APK
- `npm run lint` - Run ESLint for code quality

## �� Platform Support

- **iOS**: Full support with native components
- **Android**: Full support with Material Design adaptations
- **Web**: Progressive Web App (PWA) support
- **Cross-platform**: Consistent experience across all platforms

## �� Configuration

### App Configuration (`app.json`)
- App name: "Natively"
- Version: 1.0.0
- Dark theme support
- Splash screen and icons
- Platform-specific settings

### Dependencies
- **Core**: React Native, Expo
- **Navigation**: Expo Router, React Navigation
- **Storage**: AsyncStorage for local data persistence
- **UI**: Custom components with consistent styling
- **Charts**: React Native Chart Kit
- **Icons**: Expo Vector Icons

## 🎯 Key Features Implementation

### Data Persistence
- Uses AsyncStorage for local data storage
- Automatic data loading on app startup
- Real-time updates across all screens

### Achievement System
- Dynamic achievement checking based on user actions
- Progress tracking for ongoing challenges
- Visual feedback for unlocked achievements

### Responsive Design
- Adapts to different screen sizes
- Consistent spacing and typography
- Touch-friendly interface elements

## 🔮 Future Enhancements

- **Cloud Sync**: Backup data to cloud storage
- **Social Features**: Share achievements with friends
- **Advanced Analytics**: Detailed hydration insights
- **Custom Reminders**: Full reminder customization
- **Dark Mode**: Toggle between light and dark themes
- **Widgets**: Home screen widgets for quick logging

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## �� Acknowledgments

- Built with React Native and Expo
- Icons provided by Expo Vector Icons
- Chart components from React Native Chart Kit
- Design inspiration from modern mobile app patterns

---


**Stay hydrated, stay healthy! ��**"# Water-Hydrate" 
"# Water-Hydrate" 
