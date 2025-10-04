

# User Experience Design IA - 2

## Implementation of Accessibility & Inclusivity Principles

#### Division: LY Comps C

#### Student Details:
- **Student 1**: Harikrishnan Gopal, Roll No: 16010122284
- **Student 2**: Aditya Raut, Roll No: 16010122288
- **Student 3**: Rohit Sharan, Roll No: 16010122307


---

# Somaiya Vidyavihar Library Online Catalogue

**Original Website**- https://opac.somaiya.edu/
**Redesigned Website** - https://hk151109.github.io/UED_IA/

## Accessibility, Usability & Inclusivity Implementation Report

This report documents the implementation of accessibility and inclusivity principles as part of the User Experience Design Internal Assessment 2. The project follows the prescribed methodology of identifying accessibility issues, analyzing user challenges, providing recommendations, and developing a working prototype.



### 1. Selection of Application
**Application Selected**: Somaiya Vidyavihar Library Online Catalogue
- **Rationale**: The existing library website lacked modern accessibility and inclusivity principles
- **User Base**: Students, faculty, researchers, and general public with diverse abilities and device preferences
- **Daily Usage**: Academic research, book borrowing, information access

### 2. Challenges Faced by Different User Groups

#### Visual Impairments
- **Screen Reader Users**: Lack of ARIA labels, semantic HTML, and proper heading structure
- **Low Vision Users**: Insufficient color contrast, non-resizable text, lack of high contrast mode
- **Color Blind Users**: Poor color differentiation, reliance on color-only information

#### Motor Disabilities
- **Keyboard-only Users**: Missing focus indicators, non-keyboard accessible controls
- **Limited Dexterity**: Small touch targets, complex multi-step interactions
- **Motor Control Issues**: Lack of sufficient time for interactions, motion sensitivity

#### Cognitive Disabilities
- **Navigation Complexity**: Confusing menu structures, lack of clear visual hierarchy
- **Information Overload**: Dense content without clear organization
- **Memory Issues**: No persistent user preferences, inconsistent interface patterns

#### Mobile/Situational Impairments
- **Mobile Users**: Fixed desktop layout, non-responsive design
- **Situational Impairments**: Bright light conditions, noisy environments, time constraints
- **Device Limitations**: Small screens, touch-only interfaces, limited bandwidth

### 3. Recommendations to Address Challenges

#### Technical Recommendations
- Implement WCAG 2.1 AA compliance standards
- Add comprehensive ARIA labeling and semantic HTML
- Create responsive design with mobile-first approach
- Implement user preference controls (theme, font size, motion)

#### Design Recommendations
- Simplify navigation with clear visual hierarchy
- Add skip links and keyboard navigation support
- Implement consistent interaction patterns
- Provide multiple ways to access information

#### Content Recommendations
- Use clear, concise language
- Provide alternative text for all images
- Create logical content flow
- Add contextual help and guidance

### 4. Working Prototype Implementation

#### Prototype Features Implemented

##### Accessibility Features
- **Skip Navigation**: "Skip to main content" link for keyboard users
- **ARIA Implementation**: Comprehensive labeling and semantic structure
- **Focus Management**: Custom focus indicators with proper contrast
- **Screen Reader Support**: Proper heading hierarchy and landmark regions

##### Inclusivity Features
- **Theme Switching**: Light/dark mode with system preference detection
- **Font Scaling**: Adjustable text size (80%-160%) with persistent storage
- **Motion Control**: Reduced motion toggle for vestibular disorder accommodation
- **Multi-language Support**: Language switcher for diverse linguistic needs

##### Usability Enhancements
- **Mobile-First Design**: Responsive layout optimized for all devices
- **Advanced Navigation**: Slide-out mobile menu with accessibility panel
- **Catalogue Filtering**: Four-filter system with visual active filter display
- **Interactive Feedback**: Clear hover states and transition effects

#### Technical Implementation
- **Framework**: Vanilla HTML/CSS/JavaScript with Tailwind CSS
- **Accessibility**: WCAG 2.1 AA compliant color contrast and interaction patterns
- **Performance**: Optimized loading and interaction times
- **Cross-browser**: Compatible with modern browsers and assistive technologies

### 5. Summary Report

#### Key Improvements Summary

### Before vs After Comparison

| Aspect | Original Website | Redesigned Website |
|--------|------------------|-------------------|
| **Responsiveness** | Fixed desktop layout | Fully responsive across all devices |
| **Navigation** | Basic desktop menu | Mobile-first navigation with accessibility panel |
| **Accessibility** | Minimal ARIA support | Comprehensive WCAG 2.1 AA compliance |
| **Visual Design** | Basic styling | Modern design with dark mode support |
| **User Controls** | None | Font scaling, motion control, theme switching |
| **Search Experience** | Basic search bar | Advanced filtering system with visual feedback |

## 🔍 Detailed Implementation Analysis

### Accessibility Features Implemented

#### Skip Navigation
- **Implementation**: "Skip to main content" link that appears on keyboard focus
- **Benefit**: Allows keyboard users to bypass navigation and reach content quickly
- **WCAG Guideline**: 2.4.1 Bypass Blocks

#### ARIA Implementation
- **Implementation**: Comprehensive ARIA labels, roles, and states
- **Features**:
  - `aria-label` for icon buttons
  - `aria-expanded` for collapsible menus
  - `aria-pressed` for toggle buttons
  - `aria-live` for dynamic content
  - `role="menubar"` and `role="menuitem"` for navigation
- **Benefit**: Screen readers can properly announce interactive elements

#### Focus Management
- **Implementation**: Custom focus rings with theme-aware colors
- **Features**: High contrast focus indicators that work in both light and dark themes
- **Benefit**: Keyboard navigation is clear and accessible

#### Semantic HTML Structure
- **Implementation**: Proper use of `<nav>`, `<main>`, `<header>`, `<section>` elements
- **Benefit**: Better screen reader navigation and SEO

### Usability Features Implemented

#### Mobile-First Responsive Design
- **Implementation**: Mobile-first CSS with progressive enhancement
- **Breakpoints**: sm (640px), md (768px), lg (1024px), xl (1280px)
- **Features**: Touch-friendly targets, optimized layouts, responsive typography
- **Benefit**: Usable across all devices and screen sizes

#### Advanced Navigation System
- **Desktop**: Clean horizontal navigation with Material Icons
- **Mobile**: Slide-out navigation menu with backdrop overlay
- **Accessibility Panel**: Quick access to all accessibility controls
- **Benefit**: Improved mobile user experience

#### Advanced Catalogue Filtering
- **Implementation**: Four-filter system (Branch, Material Type, Location, Language)
- **Features**:
  - Dropdown selection interface
  - Visual active filter display
  - Removable filter tags
  - localStorage persistence
- **Benefit**: Efficient search result narrowing with clear feedback

#### Interactive Feedback
- **Implementation**: Smooth transitions with motion preference respect
- **Features**: Hover states, focus indicators, loading feedback
- **Benefit**: Clear user interaction feedback

### Inclusivity Features Implemented

#### Theme Support (Dark/Light Mode)
- **Implementation**: CSS custom properties with class-based theme switching
- **Features**:
  - System preference detection
  - Manual toggle option
  - Persistent user preference
  - Consistent color scheme across themes
- **Benefit**: Accommodates light sensitivity and visual preferences

#### Font Scaling System
- **Implementation**: JavaScript-controlled font size adjustment
- **Range**: 80% to 160% scaling
- **Features**:
  - Real-time adjustment
  - Visual percentage indicator
  - localStorage persistence
  - Responsive scaling
- **Benefit**: Helps users with visual impairments

#### Motion Control
- **Implementation**: CSS class toggle for reduced motion
- **Features**:
  - Respects `prefers-reduced-motion` system setting
  - Manual override option
  - Disables CSS transitions when active
- **Benefit**: Prevents motion sickness for sensitive users

#### Multi-Language Support
- **Implementation**: Language switcher with proper HTML lang attributes
- **Languages**: English, Hindi, Marathi
- **Features**: UI language switching (content localization ready)
- **Benefit**: Serves diverse linguistic communities

#### High Contrast Design
- **Implementation**: WCAG AA compliant color contrast ratios
- **Features**:
  - Minimum 4.5:1 contrast ratio for normal text
  - 3:1 ratio for large text
  - Theme-aware focus indicators
- **Benefit**: Better readability for visual impairments

## 🛠️ Technical Implementation Details

### CSS Architecture
- **Tailwind CSS**: Utility-first framework with custom configuration
- **CSS Custom Properties**: Dynamic theming system
- **Dark Mode**: Class-based theme switching
- **Responsive Design**: Mobile-first breakpoint system

### JavaScript Implementation
- **Vanilla JavaScript**: No external dependencies for core functionality
- **localStorage**: User preference persistence
- **Event Handling**: Efficient event delegation
- **Progressive Enhancement**: Works without JavaScript

### Performance Optimizations
- **Minimal CSS**: Utility classes prevent code bloat
- **Efficient JavaScript**: Lightweight implementation
- **Fast Loading**: Optimized asset delivery
- **Smooth Interactions**: Hardware-accelerated animations

## 📱 Device Compatibility

### Supported Devices
- **Mobile Phones**: 320px and up (iOS Safari, Chrome Mobile)
- **Tablets**: 768px and up (iPad, Android tablets)
- **Laptops**: 1024px and up
- **Desktop**: 1280px and up

### Browser Support
- **Modern Browsers**: Chrome 90+, Firefox 88+, Safari 14+, Edge 90+
- **Progressive Enhancement**: Graceful degradation for older browsers
- **Assistive Technology**: Compatible with NVDA, JAWS, VoiceOver, screen readers


## 📚 References & Resources

### Original Application Screenshots
Located in `screenshots/old_screenshots/`:
- `old_home.png` - Original homepage design
- `old_login.png` - Original login interface
- `old_MyAccount.png` - Original account management
- `old_OpacSearchCatalogue.png` - Original catalogue search
- `old_FAQ.png` - Original help section
- `old_AskLibrarian.png` - Original contact interface
- `old_phoneview.png` - Original mobile experience

### Standards & Guidelines Referenced
- [WCAG 2.1 AA Guidelines](https://www.w3.org/TR/WCAG21/)
- [WAI-ARIA Authoring Practices Guide](https://www.w3.org/WAI/ARIA/apg/)
- [Material Design Accessibility Guidelines](https://material.io/design/usability/accessibility.html)
- [Web Content Accessibility Guidelines](https://www.w3.org/WAI/WCAG21/quickref/)

---

## Conclusion

This implementation successfully addresses the accessibility and inclusivity challenges identified in the original Somaiya Vidyavihar Library website. The redesigned system provides a comprehensive solution that meets WCAG 2.1 AA standards while offering an enhanced user experience for all users, regardless of their abilities or device preferences.

The project demonstrates how modern web development practices can create inclusive digital experiences that serve diverse user needs while maintaining usability and performance standards.


## 👥 Contributing

When adding new features, ensure they meet the established accessibility, usability, and inclusivity standards:

1. **Test with keyboard navigation**
2. **Verify screen reader compatibility**
3. **Check color contrast ratios**
4. **Test on mobile devices**
5. **Validate with automated tools**

---

*This redesigned library system demonstrates how modern web development practices can create inclusive, accessible, and user-friendly experiences for all users, regardless of their abilities or device preferences.*