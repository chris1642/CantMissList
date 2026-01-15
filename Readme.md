# Can't Miss List

A monthly curated list of important updates for the St. Louis Microsoft Fabric / Power BI Meetup Group.

## About

This website showcases the latest and most important updates in the Microsoft Fabric and Power BI ecosystem for our meetup community. Each month's content is preserved in its own archive page, allowing members to reference past editions.

**Meetup Group:** [St. Louis Microsoft Fabric / Power BI Meetup](https://www.meetup.com/saint-louis-microsoft-fabric-power-bi-meetup-group/)

## Viewing the Website

Simply open `index.html` in your web browser to access the main archive page, or visit the GitHub Pages URL once deployed. From there, you can navigate to any monthly edition.

## Archive Structure

- **index.html** - Main landing page with links to all monthly archives
- **month.html** - Dynamic monthly view page with month switcher
- **monthly-items.json** - JSON data file containing all monthly content with keys: month, title, description, url

Adding new monthly editions is now as simple as adding a new entry to the `monthly-items.json` file - no need to create new HTML files!

## How It Works

The website now uses a JSON-based system to manage monthly content efficiently:

1. **monthly-items.json** - Contains all monthly data in a structured format
2. **index.html** - Dynamically loads and displays the current month and archive
3. **month.html** - Shows individual month content with a dropdown switcher to navigate between months

This approach significantly reduces AI resource usage when adding new monthly editions - simply update the JSON file instead of creating new HTML pages!

## Current Month's Topics (January 2026)

- T-SQL magic command in Fabric Python notebooks
- Service Principal support for Fabric item creation (Fabric-Prefab)
- SharePoint CSV shortcuts with file transformations
- New refresh options in Power BI Desktop (data only, schema only, or both)

## Design

The website features:
- Microsoft Fabric/Power BI color scheme (purple and blue gradients)
- Modern, responsive design that works on desktop and mobile
- Interactive hover effects on topic cards
- Clean, professional layout optimized for readability

## License

Created for the St. Louis Microsoft Fabric / Power BI Meetup Group community.
