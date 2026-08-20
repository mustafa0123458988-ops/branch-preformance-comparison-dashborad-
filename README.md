# Branch Performance Comparison Dashboard
![Project screenshot](images/Screenshot%202026-08-21%20042638.png)


## Project Preview

![Dashboard screenshot](images/dashboard.png)

its a program that compare different branches within a company on the basis of some matric  
# Branch Performance Comparison Dashboard

A simple browser-based dashboard for comparing company branches using sales, profit, and customer metrics.

## Features

- Add and edit branch data
- Delete branches
- Search for branches
- Compare sales and profit with a chart
- View total sales, profit, and customers
- Automatically save data in browser local storage
- Export branch data as a CSV file
- Responsive layout for desktop and mobile

![Second branch chart](images/branch-chart2.png)


![Branch chart](images/branch-chart.png)


## How to Run

1. Download or clone this project.
2. Open `index.html` in a web browser.
3. Add branch information using the form.

No server or installation is required.
# Branch Performance Comparison Dashboard

![Mustafa logo](mustafa-logo.svg)

A browser-based dashboard for comparing company branches using sales, profit, and customer metrics.

## Preview

Add screenshots to the `images` folder and display them here:

![Dashboard screenshot](images/dashboard.png)

![Branch chart](images/branch-chart.png)

![Second branch chart](images/branch-chart2.png)

![Project screenshot](images/Screenshot%202026-08-21%20042638.png)

Example project structure:

```text
myproject/
|-- images/
|   |-- dashboard.png
|   |-- branch-chart.jpg
|-- README.md
|-- index.html
|-- test2.html
|-- test3.html
|-- test4.html
|-- test5.html
|-- test6.html
|-- mustafa-logo.svg
```

## Features

- Add, edit, and delete branch records
- Search for branches by name
- View total sales, profit, and customers
- Identify the branch with the highest sales
- Compare sales and profit with a chart
- Save data in browser local storage
- Export branch data as a CSV file
- Use the responsive dashboard on desktop or mobile
- Switch between light and dark mode in the latest dashboard version

## How to Run

No installation or server is required.

1. Download or clone this repository.
2. Open the project folder in VS Code.
3. Open `index.html` or `test6.html` in a web browser.
4. Add branch information using the form.

You can also open a page from PowerShell:

```powershell
Start-Process .\index.html
```

## How to Use

1. Enter a branch name.
2. Enter the sales, profit, and customer values.
3. Select **Add branch**.
4. Use **Edit** to update a branch.
5. Use **Delete** to remove a branch.
6. Use the search box to find a branch.
7. Select **Export CSV** to download the data.

## Adding Photos

Create an `images` folder beside this README file, then place your photos inside it:

```text
myproject/
|-- images/
|   |-- dashboard.png
|   |-- branch-chart.jpg
```

Add a photo to this README with:

```md
![Description of the photo](images/dashboard.png)
```

Supported examples include `.png`, `.jpg`, and `.webp` files. Use short filenames without spaces, such as `dashboard-preview.png`.

## Adding Photos with Git

After placing a photo in the `images` folder, run:

```powershell
git add images/dashboard.png README.md
git commit -m "Add dashboard screenshot"
git push
```

To add all new project images:

```powershell
git add images/
```

## Technologies Used

- HTML
- CSS
- JavaScript
- Chart.js
- Browser Local Storage

## Data Fields

Each branch contains:
- Browser local storage

## Data Fields

Each branch record contains:
- Branch name
- Sales
- Profit
- Number of customers

## Important Notes

Branch data is saved only in the current browser. Clearing browser storage or changing browsers can remove or hide saved data.

The charts use Chart.js from a CDN, so an internet connection may be needed for charts to load.

## Future Improvements

- Add monthly and yearly comparisons
- Add profit-margin calculations
- Import data from CSV files
- Add user accounts
- Add sorting by sales, profit, or customers
- Add dark mode

## Limitations

Data is stored only in the current browser. Clearing browser storage will remove the saved branch data.
- Add sorting by sales, profit, or customers
- Add user accounts and cloud storage
- Add more chart types
- Add downloadable PDF reports

## Author

Created by Mustafa.
