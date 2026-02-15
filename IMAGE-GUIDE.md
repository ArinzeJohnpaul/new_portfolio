# Image Placement Guide

## Current Image Setup

Your portfolio now has images in these strategic locations:

### 1. Hero Section (Home Page)
**Left Side Portrait:**
- **Location:** Left of "Hello, I'm ODOH ARINZE JOHNPAUL"
- **Current Image:** `images/professional-portrait.jpg`
- **Style:** Circular frame with glowing border effect
- **Size:** 400x400px recommended
- **Purpose:** Creates immediate personal connection with visitors

**Background Overlay:**
- **Current Image:** `images/presentation.jpg`
- **Style:** Subtle grayscale overlay at 5% opacity
- **Purpose:** Adds professional atmosphere

### 2. About Section
**Profile Image:**
- **Location:** Right side of About text
- **Current Image:** `images/professional-portrait.jpg`
- **Style:** Square frame with decorative corners
- **Size:** 350x350px
- **Purpose:** Formal professional portrait

### 3. Professional Gallery Section
Three images showcasing your work environment:

**Gallery Image 1:**
- **File:** `images/presentation.jpg`
- **Caption:** "Data Presentation - Delivering insights to stakeholders"

**Gallery Image 2:**
- **File:** `images/office-desk.jpg`
- **Caption:** "Daily Analytics - Transforming data into actionable insights"

**Gallery Image 3:**
- **File:** `images/office-casual.jpg`
- **Caption:** "Strategic Planning - Collaborating on data-driven solutions"

### 4. Project Icons (NEW!)
Each project now has a **circular icon** at the top of its card:

**WACS Project:**
- **File:** `images/project-wacs.jpg`
- **Recommended:** Screenshot of WACS dashboard, credit scheme logo, or financial chart
- **Style:** 80x80px circle with blue border

**IDEC Project:**
- **File:** `images/project-idec.jpg`
- **Recommended:** Import/export graphics, Ministry of Finance logo, or customs document

**POSSAP Project:**
- **File:** `images/project-possap.jpg`
- **Recommended:** Police badge, security shield, or platform dashboard

**NASIMS Project:**
- **File:** `images/project-nasims.jpg`
- **Recommended:** Social program icon, beneficiary map, or impact statistics

## How to Replace Images

### Option 1: Replace Existing Files
Simply replace the files in the `images/` folder with your own images using the same filenames.

### Option 2: Use New Filenames
1. Add your images to the `images/` folder
2. Open `index.html` in a text editor
3. Find and replace the image paths:
   - Search for: `images/professional-portrait.jpg`
   - Replace with: `images/your-new-image.jpg`

## Image Specifications

### Hero Portrait (Left Side)
- **Format:** JPG or PNG
- **Dimensions:** 400x400px (square)
- **Style:** Professional headshot or upper body
- **Background:** Any (will be cropped to circle)
- **File Size:** Under 200KB

### Project Icons (All 4 Projects)
- **Format:** JPG or PNG
- **Dimensions:** 200x200px minimum
- **Style:** Logo, icon, or representative image
- **Background:** Contrasting color works best
- **File Size:** Under 100KB each
- **Tips:** 
  - Use project logos if available
  - Screenshots of dashboards work well
  - Icons representing the project theme
  - Ensure good contrast with dark blue theme

### Gallery Images
- **Format:** JPG
- **Dimensions:** 800x1000px (4:5 ratio)
- **Style:** Professional work photos
- **File Size:** Under 300KB

## Quick Tips for Best Results

1. **Project Icons:**
   - Use square images (they'll be cropped to circles)
   - Ensure main subject is centered
   - High contrast helps visibility
   - Consider using project-specific colors

2. **Portrait Images:**
   - Face should be clearly visible
   - Professional attire recommended
   - Good lighting is essential
   - Neutral or simple background works best

3. **File Optimization:**
   - Compress images before uploading
   - Use tools like TinyPNG or Squoosh
   - Maintain quality while reducing file size

## Current Placeholder Status

**Note:** The project icons currently use temporary placeholders from your existing photos. Replace these with actual project-related images for best results:

- `project-wacs.jpg` - Currently: presentation photo → Replace with WACS-related image
- `project-idec.jpg` - Currently: office desk photo → Replace with IDEC-related image
- `project-possap.jpg` - Currently: office casual photo → Replace with POSSAP-related image
- `project-nasims.jpg` - Currently: professional portrait → Replace with NASIMS-related image

## Finding Project Images

Where to get project-specific images:

1. **Project Screenshots:** Dashboard or interface captures
2. **Project Logos:** Official branding if available
3. **Thematic Icons:** Related to project domain (finance, law enforcement, etc.)
4. **Data Visualizations:** Charts or graphs from the project
5. **Free Icon Resources:** 
   - Flaticon.com
   - Icons8.com
   - Iconfinder.com
   - Font Awesome icons (can screenshot)

## Need Help?

If you need to change image locations or add more images, the main files to edit are:
- `index.html` - Contains image references
- `styles.css` - Controls image styling and sizing
