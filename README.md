````markdown
# 160-Day DSA Odyssey ✨

An interactive web application that chronicles a 160-day journey through Data Structures and Algorithms. Explore problems as planets in a beautiful 3D galaxy, view detailed notes, and get AI-powered code solutions on demand.

### 🔴 **[Live Demo](https://dsa-odssey-mobile.onrender.com/)**

[![Live Demo](https://img.shields.io/badge/Deployment-Live%20Demo-brightgreen?style=for-the-badge)](https://dsa-odssey-mobile.onrender.com/)



---

## 🚀 Key Features

* **Interactive 3D Visualization**: Journey through a spiral galaxy where each star represents a solved DSA problem. The visualization is built with **Three.js**.
* **AI-Powered Code Solutions**: Integrated with the **Google Gemini API** to generate code solutions for any problem in any programming language, complete with detailed explanations.
* **Detailed Problem Information**: Click on any "planet" to view comprehensive details, including problem difficulty, topics covered, personal notes, and links to the original problem and social media posts.
* **Search and Filter**: Easily find specific problems by searching for their name or filtering by topic.
* **Responsive Design**: A sleek, modern interface that works seamlessly on both desktop and mobile devices.
* **Dynamic Content**: The entire journey is rendered dynamically from a `journeyData.json` file, making it easy to update and expand.

---

## 🛠️ Tech Stack

This project is built with a combination of modern web technologies:

* **Backend**: Python with **Flask**
* **Frontend**: HTML, CSS, and modern JavaScript (ES6 Modules)
* **3D Graphics**: **Three.js**
* **AI Integration**: **Google Gemini API**
* **Deployment**: **Render**

---

## ⚙️ Setup and Installation

To get this project running on your local machine, follow these simple steps:

### 1. Clone the Repository

```bash
git clone [https://github.com/your-username/DSA-Odssey.git](https://github.com/your-username/DSA-Odssey.git)
cd DSA-Odssey
````

### 2\. Create a Virtual Environment

It's highly recommended to use a virtual environment to manage project dependencies.

```bash
# For Windows
python -m venv venv
venv\Scripts\activate

# For macOS/Linux
python3 -m venv venv
source venv/bin/activate
```

### 3\. Install Dependencies

Install all the required Python packages using pip.

```bash
pip install -r requirements.txt
```

### 4\. Set Up Environment Variables

The application uses the Google Gemini API, which requires an API key.

  * Create a new file named `.env` in the root directory of the project.
  * Add your API key to this file as shown below:
    ```
    GEMINI_API_KEY="YOUR_API_KEY_GOES_HERE"
    ```

*Replace `"YOUR_API_KEY_GOES_HERE"` with your actual API key from Google AI Studio.*

### 5\. Run the Application

Start the Flask development server.

```bash
flask run
```

Your application should now be running\! Open your web browser and navigate to `http://127.0.0.1:5000` to see the DSA Odyssey in action.

-----

## 📖 How to Use

1.  **Explore the Galaxy**: Use your mouse to rotate, pan, and zoom the 3D scene.
2.  **View Problem Details**: Click on any glowing star (planet) to view the details of the DSA problem solved on that day. This will automatically open the sidebar.
3.  **Get AI Solutions**: In the details view, click the "Get AI Code Solution" button. A full-screen modal will appear.
4.  **Enter Language**: Type your desired programming language (e.g., `Python`, `Java`, `C++`) into the input field.
5.  **Generate**: Click "Generate Solution" to receive a complete code solution and a detailed explanation, neatly organized into two cards.

-----

## 📁 Project Structure

```
.
├── app.py              # Main Flask application logic
├── Procfile            # For deployment (e.g., Heroku)
├── requirements.txt    # Python dependencies
├── .env                # For API keys (not committed)
├── static/
│   ├── css/
│   │   └── style.css   # Main stylesheet
│   ├── js/
│   │   └── main.js     # Three.js and frontend logic
│   └── journeyData.json # Data for all DSA problems
└── templates/
    └── index.html      # Main HTML file
```

-----

## 🤝 Contributing

Contributions, issues, and feature requests are welcome\! Feel free to check the [issues page](https://www.google.com/search?q=https://github.com/your-username/DSA-Odssey/issues).

-----

## 📄 License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

-----

Created with ❤️ by **Khurram Rashid**.

```
```
