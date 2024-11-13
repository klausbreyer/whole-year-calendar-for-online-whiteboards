# Quarterly Calendar Generator

A simple, client-side quarterly calendar that displays a calendar for a specific year and quarter. The calendar highlights weekends and holidays (including the applicable federal states in Germany) and offers customizable rows with pastel colors for team members or tasks.


## Motivation

This project was developed to provide an uncomplicated and visually appealing way to create quarterly calendars for planning and organizational purposes. It is entirely client-side and requires no backend or server-side code. Users can easily view the calendar and personalize it by adjusting parameters in the URL.

## Features

- Displays a calendar for a specific quarter and year.
- Highlights weekends and German public holidays.
- Shows the name of the holiday and the corresponding federal states.
- Offers customizable rows with pastel colors for team members or tasks.
- Responsive design that can be viewed in any modern web browser.

## Usage

1. **Download or Clone the Repository**

   Download the repository as a ZIP file or clone it using Git:

   ```bash
   git clone https://github.com/klausbreyer/whole-year-calendar-for-online-whiteboards.git
   ```

2. **Open index.html in a Web Browser**

   Navigate to the project folder and open index.html in your preferred web browser:
   - Windows: Right-click on index.html, select "Open with," and choose your browser.
   - macOS/Linux: Use your file manager to open index.html with your browser.

3. **View the Calendar**

   By default, the calendar displays the current year and quarter.

## Changing Parameters

You can customize the calendar by specifying the year and quarter parameters in the URL.

### Syntax

```
index.html?year=YYYY&quarter=Q
```

- YYYY: The four-digit year (e.g., 2023)
- Q: The quarter number (1, 2, 3, or 4)

### Examples

Display the second quarter of 2023:
```
index.html?year=2023&quarter=2
```

Display the fourth quarter of 2024:
```
index.html?year=2024&quarter=4
```

### Steps to Change Parameters

1. **Adjust the URL**

   In your browser's address bar, add the desired year and quarter parameters to the URL.

2. **Reload the Page**

   After adjusting the URL, press Enter or click the refresh button to update the calendar with the new parameters.

## Customization

### Adjusting Team Row Colors

The calendar provides 10 rows with different pastel colors for team members or tasks. You can customize these colors by editing the CSS classes in the `<style>` section of the index.html file.

```css
/* Example: Change the background color of the first team row */
.team-row-1 {
    background-color: #ffd1dc; /* Light pink */
}
```

### Editing Holidays

The holidays are based on German public holidays. You can modify or add holidays by adjusting the `getHolidays(year)` function in the JavaScript code within index.html.

### Changing Fonts and Styles

You can customize fonts, font sizes, and other style elements by editing the CSS in the `<style>` section.

## License

This project is open-source and available under the MIT License.

## Contributing

Contributions are welcome! Please feel free to submit issues or pull requests to improve the project.

## Acknowledgments

- The calendar uses pure JavaScript and requires no external libraries or frameworks.
- The project was inspired by the need for a simple and customizable quarterly calendar for team planning.
