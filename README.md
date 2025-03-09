# India Map with Clickable States

An interactive India map project where users can click on any state to view detailed information about that state.

## 🌟 Features
- Interactive SVG map of India.
- Each state is clickable, displaying relevant information.
- Easy navigation between states using links.
- Responsive design for smooth viewing on all devices.

## 🛠️ Technologies Used
- **HTML** for structure
- **CSS** for styling
- **JavaScript** for interactivity

## 📂 Project Structure
```
📦 IndiaMapProject
 ┣ 📂 css
 ┃ ┗ 📄 style.css
 ┣ 📂 js
 ┃ ┗ 📄 script.js
 ┣ 📂 states
 ┃ ┣ 📄 andhra-pradesh.html
 ┃ ┣ 📄 karnataka.html
 ┃ ┗ 📄 tamil-nadu.html
 ┣ 📄 index.html
 ┗ 📄 README.md
```

## 🚀 How to Run
1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/IndiaMapProject.git
   ```

2. **Navigate to the Project Directory**
   ```bash
   cd IndiaMapProject
   ```

3. **Open `index.html` in Your Browser**
   ```
   Right-click on `index.html` and select "Open with Browser"
   ```

## 🔎 Usage Instructions
1. Click on any state on the map.
2. A detailed information box will appear beside the map.
3. Each state page will provide facts, history, and cultural details.

## 🖥️ Sample Code
### `index.html`
```html
<!DOCTYPE html>
<html>
<head>
    <title>India Map</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <svg id="india-map">
        <a href="states/andhra-pradesh.html"><path id="andhra-pradesh" d="M350,500 L400,480 L450,500..."></path></a>
        <a href="states/karnataka.html"><path id="karnataka" d="M300,480 L350,500 L380,560..."></path></a>
        <a href="states/tamil-nadu.html"><path id="tamil-nadu" d="M380,560 L430,550 L440,600..."></path></a>
    </svg>
</body>
</html>
```

### `style.css`
```css
#india-map path {
    fill: #4CAF50;
    stroke: #FFFFFF;
    cursor: pointer;
}

#india-map path:hover {
    fill: #FF5722;
}
```

## 📝 Contribution
Contributions are welcome! Feel free to:
- Fork the repository.
- Create a new branch.
- Make improvements and submit a pull request.

## 📄 License
This project is licensed under the **MIT License**. Feel free to modify and use it as needed.

## 📧 Contact
For questions or suggestions, feel free to reach out to me on **[GitHub](https://github.com/Krishnendu-Ghosh-Web)** or via **bkrishnendughosh@gmail.com**.

