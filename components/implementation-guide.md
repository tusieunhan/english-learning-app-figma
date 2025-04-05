# Component Implementation Guide

## 🎨 Design System Setup

1. **Colors**
   - Create color styles for both light and dark mode
   - Use semantic naming: `primary-light`, `primary-dark`, etc.
   - Include hover and active states for interactive elements

2. **Typography**
   - Set up text styles with Inter font family
   - Define styles for all text variants (headings, body, captions)
   - Ensure proper line height and letter spacing

## 🧩 Components

### Navigation Bar
- Height: 64px
- Fixed to bottom
- Include active/inactive states for items
- Add smooth transitions for state changes
- Implement both light/dark variants

### Lesson Card
- Size: 280x320px
- Image container: 180px height
- Progress bar at bottom
- Shadow and hover effects
- Maintain text contrast in both modes

### Practice Exercise Card
- Full width layout
- Badge system for difficulty levels
- Clear typography hierarchy
- Interactive hover states
- Consistent padding and spacing

### Conversation Bubble
- Max width: 80% of container
- Different styles for user/other
- Translation text with proper spacing
- Rounded corners: 16px
- Clear visual hierarchy

### Button
- Three size variants: sm, md, lg
- Two style variants: primary, secondary
- Include hover and active states
- Consistent padding ratios
- Proper text alignment

### Implementation Steps

1. **Start with Color Styles**
   - Create all color variables
   - Set up dark mode variants
   - Test contrast ratios

2. **Typography System**
   - Set up text styles
   - Create component-specific text styles
   - Ensure responsive scaling

3. **Component Variants**
   - Build base components
   - Create all variants
   - Add auto-layout properties
   - Set up constraints

4. **Interactive States**
   - Add hover states
   - Include active states
   - Set up transitions

5. **Documentation**
   - Add usage guidelines
   - Include property descriptions
   - Document component variants

## 🔍 Quality Checklist

- [ ] All components support dark mode
- [ ] Text meets WCAG contrast requirements
- [ ] Interactive states are clearly visible
- [ ] Consistent spacing system
- [ ] Proper component organization
- [ ] Clear naming conventions
- [ ] Responsive behavior defined
- [ ] Animation properties set
- [ ] Component descriptions added
- [ ] Usage guidelines documented