# Product Recommendation System
This is a simple product recommendation system built using Python and Streamlit. The application provides product recommendations based on similarity scores and displays them in a visually appealing format.

## Features
- Select a product from the dropdown menu to get recommendations.
- Display top 3 recommended products with images.

## Getting Started
### Prerequisites
1. Python 
2. Streamlit
3. Pandas
4. NumPy
5. Pickle

### Installation
1. Clone the repository:
```bash
git clone https://github.com/shaadclt/Product-Recommendation-System.git
cd Product-Recommendation-System
```
2. Install the required packages:
```bash
pip install -r requirements.txt
```

3. Ensure you have the `data.pkl` and `similarity.pkl` files in the root directory. These files should contain your dataset and the similarity matrix, respectively.

### Usage
1. Run the Streamlit application:
```bash
streamlit run app.py
```
2. Open your web browser and navigate to the URL displayed in the terminal (usually **http://localhost:8501**).

3. Select a product from the dropdown menu and click the "Recommend" button to see the recommendations.

### Example
The application recommends products based on their similarity scores and displays the top 3 similar products in a row.


## License
This project is licensed under the MIT License.
