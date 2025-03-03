# claudportunity-tracker : Professional Opportunity Tracker

A standalone web application for managing professional development opportunities, networking contacts, and career notes in one place. Perfect for job seekers and those looking to strategically manage career opportunities.

![Opportunity Tracker Dashboard](https://via.placeholder.com/800x400?text=Opportunity+Tracker+Dashboard)

## Features

- **Dashboard**: Visual analytics showing your opportunity pipeline, conversion rates, and regional distribution
- **Opportunity Management**: Track job applications, VC roles, and professional opportunities with detailed status tracking
- **Contact Management**: Organize networking connections and link them to specific opportunities
- **Notes System**: Record meeting notes, research, and insights with tagging for easy retrieval
- **Browser Extension**: Capture opportunities directly from LinkedIn, job boards, and company websites
- **Data Import/Export**: Easily backup and transfer your data between devices

## Getting Started

### Option 1: Use the GitHub Pages Version

You can access the tracker directly at: https://[your-username].github.io/opportunity-tracker/

This version runs entirely in your browser and stores data locally.

### Option 2: Run Locally

1. Clone this repository:
   ```
   git clone https://github.com/[your-username]/opportunity-tracker.git
   ```

2. Open `index.html` in your web browser.

3. No server required! The application runs entirely in your browser.

## Data Synchronization

Since the tracker uses browser localStorage, you need to manually sync data between devices:

1. From your current device, click "Export Data" and save the JSON file
2. Commit this file to the `data/` folder in this repository (or another secure location)
3. On your new device, click "Import Data" and select the saved JSON file

## Browser Extension Setup

For quick capturing of opportunities while browsing:

1. Install a userscript manager extension like [Tampermonkey](https://www.tampermonkey.net/) (Chrome) or [Greasemonkey](https://addons.mozilla.org/en-US/firefox/addon/greasemonkey/) (Firefox)

2. Create a new userscript and paste the code from the "Extension" tab in the application

3. The extension will add three commands to your browser's context menu:
   - Capture Opportunity
   - Capture Contact
   - Capture Note

4. Use these commands on websites like LinkedIn, job boards, or company pages to quickly save information

## Usage Tips

### For Opportunities

- Use the status filters to focus on specific stages (New, Applied, Interview, Offer, Rejected)
- Set application deadlines to see them highlighted on your dashboard
- Create detailed notes for each application to track your customized approach

### For Networking

- Connect contacts to specific opportunities to build relationship maps
- Record key details from conversations to reference in follow-ups
- Use notes with the "networking" tag to track conversation topics

### For Tracking Progress

- Review your dashboard weekly to identify patterns
- Use the region and type filters to focus your efforts where you're seeing traction
- Export data regularly as a backup and to create a version history

## Development and Contribution

This is a personal tool built with plain HTML, CSS, and JavaScript. It intentionally avoids server dependencies for simplicity and privacy.

To modify the tool:

1. Edit `index.html` for all functionality (the application is self-contained)
2. Test changes locally before committing
3. For major feature additions, consider creating a branch

## Data Privacy

- All data is stored in your browser's localStorage
- No data is sent to any server
- Manual export/import gives you complete control over your information

## Future Enhancements

Planned features include:

- [ ] Automatic GitHub synchronization
- [ ] Email notification for upcoming deadlines
- [ ] Calendar integration
- [ ] Enhanced data visualization
- [ ] LinkedIn profile scraping

## License

This project is licensed under the MIT License - see the LICENSE file for details.
