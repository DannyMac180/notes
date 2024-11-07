# Mirror v0 UI Specifications

## Global Style Guide
- Use a minimalist, modern web aesthetic
- Color palette: Monochromatic grayscale (#FFFFFF to #000000)
- Primary accent color: #404040
- Secondary accent color: #737373
- Background color: #FAFAFA
- Text colors: 
  - Primary: #171717
  - Secondary: #525252
- Font: Inter for headings, system-ui for body text
- Consistent padding and spacing using 4px increments
- Subtle shadows for elevated elements
- Rounded corners (8px) on cards and interactive elements

## Authentication Screens

### Login Screen
Create a centered login form with:
- Large "Mirror" logo text at top (36px, light weight)
- Email input field with mail icon
- Password input field with lock icon
- "Remember me" checkbox below fields
- Primary action button "Sign In"
- Secondary link "Forgot password?"
- "Sign up" link below for new users
- Subtle background pattern of overlapping circles in light gray
- White card container with subtle shadow

### Sign Up Screen
Create a centered registration form with:
- "Join Mirror" heading
- Name input field
- Email input field
- Password input field with strength indicator
- Confirm password field
- Terms of service checkbox
- Primary action button "Create Account"
- "Already have an account?" link below
- Same styling as login screen

## Main Application Screens

### Dashboard
Create a full-width dashboard with:
- Top navigation bar with:
  - Mirror logo (left)
  - Navigation links: Journal, Library, Goals, Insights
  - Profile dropdown (right)
- Main content area divided into 3 columns:
  - Left column (25%):
    - Daily reflection prompt card
    - Quick journal entry button
  - Middle column (50%):
    - Progress overview card
    - Recent journal entries preview
  - Right column (25%):
    - Goals progress card
    - Values alignment indicator
- All cards should have subtle hover effects

### Journal Interface
Design a full-screen journal editor with:
- Minimal top bar containing:
  - Save status indicator
  - Entry date
  - Tags input
- Large, distraction-free writing area with:
  - Clean, serif font for writing
  - Subtle line height (1.6)
  - Comfortable maximum width (680px)
- Right sidebar (collapsible):
  - AI insights panel
  - Previous entries calendar
  - Entry metadata

### Content Library
Create a grid layout with:
- Top section:
  - Search bar with filters
  - View toggle (grid/list)
  - Add new content button
- Main content area:
  - Content cards displaying:
    - Content type icon
    - Title
    - Author/source
    - Completion status
    - Last accessed date
  - Cards arranged in responsive grid (3-4 columns)
- Left sidebar:
  - Content type filters
  - Tags filter
  - Date range filter

### Goals & Values
Design a split-screen layout:
- Left side (Goals):
  - Active goals list
  - Goal cards with:
    - Progress indicator
    - Target date
    - Related activities
  - Add goal button
- Right side (Values):
  - Values statement cards
  - Value alignment metrics
  - Edit values button
- Connection lines showing relationships between goals and values

### Insights Dashboard
Create an analytics-style layout with:
- Top section:
  - Time period selector
  - Key metrics cards
- Main content area with:
  - Growth trend graph
  - Activity patterns visualization
  - Values alignment radar chart
- Bottom section:
  - AI-generated insights cards
  - Actionable recommendations
  - Journal entry correlations

### Settings Screen
Design a settings interface with:
- Left sidebar navigation:
  - Profile
  - Notifications
  - Privacy
  - Integration
  - Account
- Main content area:
  - Section heading
  - Form elements for selected section
  - Save/Cancel buttons
- Consistent spacing and alignment
- Clear visual hierarchy

## Mobile Adaptations

All screens should be responsive with:
- Single column layouts on mobile
- Bottom navigation bar replacing top nav
- Collapsible sidebars becoming full-screen overlays
- Touch-friendly tap targets (minimum 44px)
- Maintained typography hierarchy
- Preserved white space
