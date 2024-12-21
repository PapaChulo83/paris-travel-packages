# CielaTravel Paris Packages

## Overview
This repository contains the data structure and components for CielaTravel's Paris travel packages. It provides a comprehensive system for managing and displaying various travel packages, from basic to luxury options.

## Package Types

### Basic Package ($1,099)
- Flight (Economy with stopover)
- 3* Hotel accommodation with breakfast
- Perfect for budget-conscious travelers

### Essential Package ($1,299)
Includes Basic Package plus:
- Seine River Cruise
- Eiffel Tower Access
- 7-day Paris transport pass

### Half Board Packages
1. **Economy ($1,499)**
   - Essential package features
   - 6 dinners
   - 2 additional activities

2. **Comfort ($2,699)**
   - Direct flights
   - 4* Hotel accommodation
   - 6 upscale dinners
   - 3 premium activities

3. **Luxury ($7,999)**
   - Business Class flights
   - 5* Luxury hotel
   - 6 gourmet dinners
   - 4 VIP experiences

### Full Board Packages
Includes all Half Board features plus daily lunches:
1. **Economy ($1,699)**
2. **Comfort ($2,999)**
3. **Luxury ($8,499)**

## Add-on Options
- Cultural Tours
- Special Experiences
- Transportation Upgrades
- Additional Activities

## Package Structure
All packages include:
- Return flights from Los Angeles (LAX)
- 6 nights accommodation (double occupancy)
- Daily breakfast
- Selected activities based on package level
- Basic travel insurance
- 24/7 support

## Technical Implementation
- React components for package display
- JSON data structure for package information
- Modular design for easy updates
- Responsive layout for all devices

## Usage
```javascript
import { PriceCalculator, PackageSelector } from './components';
import packagesData from './data/packages.json';
```

## Documentation
Detailed documentation is available in the /docs folder:
- Package Specifications
- Pricing Structure
- Component API
- Customization Guide