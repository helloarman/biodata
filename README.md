# Professional Biodata Generator

A modern, responsive web application for creating, editing, and printing professional biodata documents. Designed to generate beautifully formatted A4-sized biodata sheets with real-time preview.

Live Link: https://helloarman.github.io/biodata

## Features

### Core Functionality
- **Profile Photo Upload** - Add a professional photo (PNG, JPG, up to 5MB)
- **Real-time Preview** - Live preview of your biodata as you type
- **Print/Save as PDF** - Generate printable PDF documents directly from your browser
- **Data Persistence** - Automatically saves all data to browser storage between sessions
- **Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices

### Sections

#### Personal Information
- Full Name
- Father's Name & Mother's Name
- Date of Birth
- Sex (Male/Female)
- Religion (Islam, Hinduism, Christianity, Buddhism, Other)
- Nationality
- Marital Status (Single, Married, Divorced, Widowed)
- Conditional divorce/family notes
- Contact Number
- Present Address
- Permanent Address

#### Family Information
- Father's Occupation with notes
- Mother's Occupation with notes
- Siblings (dynamic list - add/remove as needed)
- Aunts/Uncles (dynamic list - add/remove as needed)

#### Educational Information
- Dynamic exam records with fields for:
  - Exam Name
  - Group
  - Board
  - Year
  - Result
- Presented in a professional table format

#### Occupation
- Job Designation
- Company Name

#### Custom Fields
- Add unlimited custom fields with flexible labels and values
- Perfect for additional certifications, hobbies, or any extra information

#### Description
- Free-form text area for personal description or additional details

## Usage

### Getting Started
1. Open `index.html` in your web browser
2. Fill in your personal information in the left form panel
3. Watch your biodata preview update in real-time on the right side
4. Upload a profile photo using the file upload zone at the top

### Adding Multiple Entries
- **Education**: Click "+ ADD EXAM" to add multiple educational qualifications
- **Siblings**: Click "+ ADD" in the Siblings section
- **Aunts/Uncles**: Click "+ ADD" in the Aunts/Uncles section
- **Custom Fields**: Click "+ ADD FIELD" to add unlimited custom information

### Saving Your Data
Your data is automatically saved to your browser's local storage. The application remembers all entries between sessions.

To clear all data, click the **"Clear Data"** button at the top right.

### Printing & PDF Export
1. Click the **"Print / Save PDF"** button at the top right
2. Use your browser's print dialog (`Ctrl+P` or `Cmd+P`)
3. Select "Save as PDF" as the destination
4. Adjust margins and settings as needed (A4 format recommended)
5. Save or print the document

## Technical Details

### Technology Stack
- **HTML5** - Semantic markup structure
- **Tailwind CSS** - Utility-first CSS framework
- **JavaScript (Vanilla)** - No dependencies required
- **localStorage** - Browser-based data persistence
- **Google Fonts** - Professional typography (Inter & Noto Serif)

### Browser Compatibility
- Chrome/Chromium (recommended for PDF export)
- Firefox
- Safari
- Edge
- Any modern browser with JavaScript and localStorage support

### File Structure
- `index.html` - Complete single-file application with embedded CSS and JavaScript

## Styling Features

### Design Elements
- Clean, professional interface
- A4-size output optimized for printing
- Responsive layout that adapts to screen size
- Print-friendly CSS with optimized page breaks
- Indigo color scheme (#4F46E5) for professional appearance
- Drag-and-drop file upload area
- Smooth transitions and focus states

### Print Optimization
- Automatic page break handling
- Professional margins and padding
- Hides the form on print (form-only elements)
- Photo positioned professionally in top-right corner
- Maintains formatting consistency across pages
- Optimized for A4 paper size (210mm × 297mm)

## Customization

### Modifying Styles
Edit the CSS in the `<style>` block to customize:
- Color scheme (change `--primary` and `--bg` variables)
- Font families (modify Google Fonts link)
- Spacing and layout
- Print margins and page settings

### Adding New Sections
The application structure makes it easy to add new form sections and preview areas by:
1. Adding a new form section in the left panel (after line 430 approx.)
2. Creating corresponding preview elements in the right panel
3. Updating the JavaScript data handling logic

## Installation

No installation required! Simply:
1. Download or clone the repository
2. Open `index.html` in any web browser
3. Start creating your biodata

## Tips for Best Results

1. **Photo**: Use a clear, professional passport-style photo
2. **Content**: Keep descriptions concise and relevant
3. **Format**: Use consistent formatting for dates (e.g., DD/MM/YYYY)
4. **Education**: List qualifications in reverse chronological order
5. **Printing**: Preview the print layout before saving as PDF
6. **Backup**: Periodically clear browser cache to avoid data loss

## Troubleshooting

### Data Not Saving?
- Check if browser localStorage is enabled
- Try clearing browser cache and cookies
- Use a modern browser with localStorage support

### Photo Not Showing?
- Ensure file size is under 5MB
- Use PNG or JPG format
- Check browser console for error messages

### Print Layout Issues?
- Use landscape orientation for wider content
- Adjust browser print margins
- Try a different print destination (PDF, physical printer)
- Test in print preview mode first

## License

This project is provided as-is for personal and professional use.

## Support

For issues or feature requests, refer to the browser's developer console for error messages, which may help identify issues.

---

**Version**: 1.0  
**Last Updated**: February 2026

