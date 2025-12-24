Breathe Please is a minimalist web application designed to help users mitigate anxiety and overthinking through rhythmic breathing and curated wisdom. It features a dynamic 3D-effect visual breather, ambient soundscapes, and an extensive library of philosophical and psychological quotes.

Features

  1.	Guided Breathing Animation
  The background features a responsive 3D sphere that expands and contracts to guide the user's breath.
  Visual transitions are handled via a breathing-active animation using a cubic-bezier timing function for a natural feel.
  Users can toggle the animation speed between 1 and 2 cycles to match their preferred breathing pace.
  
  3.	Curated Wisdom Library
  The app contains a vast collection of quotes from diverse sources, including Buddha, Marcus Aurelius, Rumi, and modern thinkers like Adam Grant and Sam Harris.
  Quotes automatically refresh in sync with the breathing cycles or can be updated manually using the "Inspire me" button.
  The display logic includes a fast-mode transition to ensure manual updates feel responsive.
  
  5.	Immersive Audio
  Includes a gapless audio looping system for the ambient track.
  Uses an equal-power crossfade algorithm to ensure seamless transitions between audio tracks.
  Offers three volume presets (Low, Mid, High) and a quick-toggle mute function.
  
  7.	Visual Customization
  Four Professional Themes:
  Light: Pantone Coconut Milk/Caviar palette.
  Dark: Pantone Jet Black/Soft White palette.
  Blue: Inspired by Pantone Classic Blue for deep tranquility.
  Green: Inspired by Pantone Green Gables for a grounded, natural feel.
  Typography Options: Toggle between Serif (Crimson Text) and Sans-Serif (Source Sans 3).

Technical Implementation
  1. Frontend: Built with HTML5, CSS3, and Vanilla JavaScript.
  2. Styling: Utilizes CSS custom properties for theme switching and clamp() for fluid, responsive typography.
  3. Audio Engine: Implements a dual-track HTMLAudioElement system to prevent gaps during loop iterations.
  4. Animation: Driven by CSS @keyframes and synced with JavaScript animationiteration events.
  
How to Use
  1. Start: Match your inhalation to the expansion of the central sphere and your exhalation to its contraction.
  2. Interact:
    a. Settings: Click the settings button or the central lotus graphic to access the menu.
    b. Audio: Click the sound button at the bottom-left or click anywhere on the background to toggle the ambient track.
    c. Fonts: Click the quote text directly to instantly switch between Serif and Sans-Serif styles.
    d. Manual Inspiration: Use the "Inspire me" button at the bottom-right to skip to a new quote.
