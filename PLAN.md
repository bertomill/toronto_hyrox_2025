# Berto & Katy's Hyrox Strategy App - Plan

## Overview
A clean, visual timeline display of the Hyrox Mixed Doubles race strategy for Berto and Katy - just like your handwritten notes but beautifully presented digitally.

## Target Time
**57:15** + 5min ROX Zone

## Core Features

### 1. Timeline Display
- **Station Cards**: Visual timeline showing each segment in order
- **Cumulative Times**: Progressive timing (3:50, 7:20, 11:10, etc.)
- **Athlete Assignments**: Clear breakdown of who does what (Berto vs Katy)
- **Split Details**: Exact distances and percentages per athlete

### 2. Visual Design
- **Modern UI**: Clean, gradient-based design with cards
- **Color Coding**: 
  - Berto: Green (#4CAF50)
  - Katy: Pink (#E91E63)
- **Responsive**: Works on mobile and desktop
- **Animations**: Smooth transitions and hover effects

### 3. Race Stations (16 total)

#### Running Segments (8 x 1km)
- Target: 3:50 each (except final push)
- Strategy: Maintain consistent pace @ 6 min/km

#### Workout Stations (8)
1. **Ski Erg** (1000m) - 3:30
   - Berto: 70% (700m)
   - Katy: 30% (300m)

2. **Sled Push** (50m) - 1:35
   - Berto: 70% (35m)
   - Katy: 30% (15m)

3. **Sled Pull** (50m) - 2:30
   - Berto: 70% (35m)
   - Katy: 30% (15m)

4. **Burpee Broad Jumps** (80m) - 2:05
   - Switch every 5-7 reps
   - Call switch ~60-70% (Katy)

5. **Rowing** (1000m) - 4:05
   - Berto: 300m → Katy: 250-300m → Berto: 400m

6. **Farmers Carry** (200m) - 1:35
   - Berto: 80m (60-70m) → Katy: 40m → Berto: 50m

7. **Sandbag Lunges** (100m) - 2:30
   - Berto: 40m → Katy: 40m → Berto: 20m

8. **Wall Balls** (100 reps) - 3:40
   - Alternating sets of 20 reps each
   - Final push strategy

## Technical Implementation

### Core Features (Timeline Visualization Only)
- [x] Create project structure
- [x] Build HTML layout with station cards showing timeline
- [x] Add CSS styling with Berto/Katy color coding
- [x] Display cumulative time progression (3:50, 7:20, 11:10, etc.)
- [x] Show athlete assignments per station
- [x] Implement responsive design for mobile viewing
- [x] Add basic animations and visual polish

### Future Enhancements (Optional)
- [ ] Export strategy to PDF for printing
- [ ] Shareable link functionality
- [ ] Print-optimized version

## File Structure
```
hyrox_race_plan/
├── index.html          # Main app file
├── styles.css          # Styling (if separated)
├── script.js           # JavaScript functionality
├── PLAN.md            # This planning document
└── README.md          # Project documentation
```

## Design Principles
1. **Clarity**: Information should be instantly readable during race prep
2. **Visual Hierarchy**: Important timing info prominently displayed
3. **Team Focus**: Equal representation of both athletes
4. **Mobile-First**: Usable on phones during race day
5. **Performance**: Fast loading, minimal dependencies

## Success Metrics
- Clean digital version of your handwritten strategy
- Clear timeline progression showing cumulative times
- Easy identification of athlete responsibilities per station
- Mobile-friendly for quick reference during race prep
- Printable version for race day backup

## Next Steps
1. Create the main HTML structure
2. Implement the station cards with timing
3. Add athlete assignment visualization
4. Style with modern UI components
5. Test on mobile devices
6. Add interactive features (timer, progress tracking)