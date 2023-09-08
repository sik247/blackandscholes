NYU Hack 2023 - Black and Scholes (Option Price)

Description:

This Python code is an implementation of the Black-Scholes model for options pricing, integrated into an interactive web application using Streamlit. The Black-Scholes model is a widely-used mathematical formula for calculating the theoretical prices of European-style call and put options.

Key Components:

Black-Scholes Functions:

The code defines functions for calculating intermediate terms (d1 and d2) and option prices (calculate_call_price and calculate_put_price) based on the Black-Scholes model. These functions are fundamental for pricing options.
Interactive Visualization:

The code uses Streamlit to create an interactive web application with sliders for users to input various parameters, such as stock price, strike price, risk-free interest rate, volatility, and time until maturity.
Plotting Option Prices:

It generates dynamic graphs of option prices for both call and put options based on the input parameters. Users can visualize how option prices change concerning changes in the stock price, strike price, and other factors.
Navigation Menu:

The application includes a navigation menu with options to explore the Home page, learn about options, and visualize Black-Scholes formulas.
Usage:

Users can input their desired option parameters via the sidebar sliders.
The application calculates and displays the call and put option prices in real-time.
Users can observe how these option prices change as they adjust the input parameters.
Project Purpose:

The project aims to provide an educational and interactive platform for users to understand options pricing through the Black-Scholes model.
It allows users to explore the impact of different factors on option prices and gain insights into options trading.
How to Use:

Clone the repository containing this code.
Install the necessary Python libraries, including Streamlit, Matplotlib, and NumPy.
Run the Streamlit app using streamlit run filename.py, where filename.py is the name of the Python script.
Access the interactive web application through the provided URL.
This project serves as a valuable resource for anyone interested in learning about options trading and the Black-Scholes model. Users can experiment with different scenarios and gain a deeper understanding of options pricing dynamics.
