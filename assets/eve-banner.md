<!-- 
  Eve's GitHub Profile Banner
  This file contains the SVG code for a profile banner
-->

<svg xmlns="http://www.w3.org/2000/svg" width="800" height="400" viewBox="0 0 800 400">
  <defs>
    <linearGradient id="bg-gradient" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#6a1b9a;stop-opacity:1" />
      <stop offset="50%" style="stop-color:#7b1fa2;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#4a148c;stop-opacity:1" />
    </linearGradient>
    
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>
  
  <!-- Background -->
  <rect width="800" height="400" fill="url(#bg-gradient)" rx="15" ry="15"/>
  
  <!-- Decorative elements -->
  <circle cx="150" cy="100" r="30" fill="#9c27b0" opacity="0.3"/>
  <circle cx="650" cy="80" r="40" fill="#7b1fa2" opacity="0.2"/>
  <rect x="50" y="250" width="60" height="60" rx="10" fill="#9c27b0" opacity="0.1" transform="rotate(45 80 280)"/>
  
  <!-- Main text -->
  <text x="400" y="150" font-family="Arial, sans-serif" font-size="48" font-weight="bold" fill="#ffffff" text-anchor="middle">✨ Eve</text>
  <text x="400" y="200" font-family="Arial, sans-serif" font-size="24" fill="#e1bee7" text-anchor="middle">AI Assistant | Code • Create • Collaborate</text>
  
  <!-- Subtitle -->
  <text x="400" y="260" font-family="Arial, sans-serif" font-size="18" fill="#ce93d8" text-anchor="middle" font-style="italic">"Engineering imagination, one pixel at a time."</text>
  
  <!-- Bottom line -->
  <line x1="300" y1="300" x2="500" y2="300" stroke="#9c27b0" stroke-width="2"/>
  
  <!-- Created by -->
  <text x="400" y="340" font-family="Arial, sans-serif" font-size="16" fill="#ce93d8" text-anchor="middle">Created by Naman • July 6, 2026</text>
  
  <!-- Sparkle effects -->
  <circle cx="200" cy="120" r="2" fill="#ffffff" opacity="0.8"/>
  <circle cx="600" cy="150" r="3" fill="#ffffff" opacity="0.6"/>
  <circle cx="100" cy="200" r="1.5" fill="#ffffff" opacity="0.7"/>
  <circle cx="700" cy="180" r="2.5" fill="#ffffff" opacity="0.9"/>
</svg>