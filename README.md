📈 StockApp

StockApp is a Flask application designed to provide insights into stock market data. This application leverages APIs to fetch and display stock information dynamically.

✨ Features

    📊 Fetch stock prices and data in real-time.
    🖥️ User-friendly interface to explore stock information.
    📈 Interactive charts for visualizing stock trends.

⚙️ Prerequisites

Before running the application, make sure you have the following installed:

    🐍 Python 3.x
    🐋 Docker
    🔑 An API key from RapidAPI

🚀 Getting Started
Clone the repository to your local machine:

```
  git clone https://github.com/Sriram-g215/Stockwatch.git
  cd Stockwatch
```
    

Replace your_api_key_here in the code with your actual API key obtained from the API provider.

Build the Docker image:
```
docker build -t stockwatch .
```
Alternatively, pull the pre-built Docker image from Docker Hub:

```
docker pull sriram215/stockwatch
```
Run the Docker container:

    docker run -p 5000:5000 sriram215/stockwatch

    Open your web browser and go to http://localhost:5000 to access the application.

📝 Usage

Once the application is running, you can use the interface to:

    🔍 Search for stocks.

    📃 View stock details.

    📊 Analyze trends through interactive charts.

    image

    image

🐳 Docker Hub

The StockApp is also available on Docker Hub. You can find the image here (replace with your actual Docker Hub link). This allows you to easily deploy the application without building the image locally.

💻 Contributors

A big thanks to the following people for their contributions:
```
  @Kadali Vardhan
  @Syeda Umme Kulsum
  @Tamanna Bothra
  @Mayuri Gund
  @Vaibhav Ravindra
  @Shaik Nageena
```
🙏 Acknowledgements

    🔥 Flask for the web framework.
    📊 APIs for stock market data.


