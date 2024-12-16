# Glulam Project

## Project Overview
This repository contains a web-based RFQ (Request for Quotation) system for Glulam beam specifications and ordering.

## Current Status
- Created and implemented basic RFQ form (`forms/rfq.html`)
- Form includes comprehensive technical specifications for Glulam beams
- Basic styling implemented

### Form Fields Include:

#### Technical Specifications
- Application Type (Snow Load/Non-Snow Load/Floor/etc.)
- Span Length
- Beam Dimensions
- Load Type
- Camber Requirement
- Appearance Grade
- Environmental Treatment
- Quantity

#### Customer Information
- Company Name
- Contact Name
- Email
- Phone
- Project Name
- File Upload capability for additional documentation

## Pending Implementation
1. JavaScript form validation
2. Form submission handler
3. Backend integration

## File Structure
```
/forms
  - rfq.html (main RFQ form)
```

## Development Notes
- Form is currently static HTML/CSS
- Required fields are marked with asterisks (*)
- Responsive design implemented for various screen sizes
