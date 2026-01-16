<svg width="800" height="300" xmlns="http://www.w3.org/2000/svg">
  <!-- Modifiable timing parameters (change these to adjust animation speed) -->
  <!-- charDelay: delay between each character appearing (in seconds) -->
  <!-- loopDuration: total time before animation repeats (in seconds) -->
  <defs>
    <style>
      :root {
        --char-delay: 0.15s;
        --loop-duration: 4s;
      }
    </style>
  </defs>
  
  <!-- Background -->
  <rect width="800" height="300" fill="#f5f5f5"/>
  
  <!-- Cleaver GIF in center -->
  <image href="https://github.com/user-attachments/assets/95e16bd3-86b3-495f-a4a9-7ed93c8ddb8e" x="300" y="50" width="200" height="200"/>

  <!-- "Angus" - left side, typewriter from middle outward (s->A) -->
  <text x="280" y="160" font-size="64" font-weight="bold" font-family="Arial, sans-serif" fill="#2c3e50" text-anchor="end">
    <!-- Characters animate from middle (s) to start (A) -->
    <tspan>A<animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.6;0.95;1" dur="4s" repeatCount="indefinite"/></tspan>
    <tspan>n<animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.45;0.95;1" dur="4s" repeatCount="indefinite"/></tspan>
    <tspan>g<animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.3;0.95;1" dur="4s" repeatCount="indefinite"/></tspan>
    <tspan>u<animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.15;0.95;1" dur="4s" repeatCount="indefinite"/></tspan>
    <tspan>s<animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.05;0.95;1" dur="4s" repeatCount="indefinite"/></tspan>
  </text>
  
  <!-- "Thacker" - right side, typewriter from middle outward (T->r) -->
  <text x="520" y="160" font-size="64" font-weight="bold" font-family="Arial, sans-serif" fill="#2c3e50" text-anchor="start">
    <!-- Characters animate from middle (T) to end (r) -->
    <tspan>T<animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.05;0.95;1" dur="4s" repeatCount="indefinite"/></tspan>
    <tspan>h<animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.15;0.95;1" dur="4s" repeatCount="indefinite"/></tspan>
    <tspan>a<animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.25;0.95;1" dur="4s" repeatCount="indefinite"/></tspan>
    <tspan>c<animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.35;0.95;1" dur="4s" repeatCount="indefinite"/></tspan>
    <tspan>k<animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.45;0.95;1" dur="4s" repeatCount="indefinite"/></tspan>
    <tspan>e<animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.55;0.95;1" dur="4s" repeatCount="indefinite"/></tspan>
    <tspan>r<animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.65;0.95;1" dur="4s" repeatCount="indefinite"/></tspan>
  </text>
</svg>

## About Me
