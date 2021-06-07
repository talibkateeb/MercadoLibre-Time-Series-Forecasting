# MercadoLibre-Time-Series-Forecasting

A time series forecasting analysis on search trends, stock price, and sales of MercadoLibre. With over 200 million users, MercadoLibre is the most popular e-commerce site in Latin America.


---

## Technologies

This application runs on python version 3.7, with the following add-ons:

* [Google Colab](https://colab.research.google.com/) - A development tool for interactive programming.

* [Pandas](https://pandas.pydata.org/) - A python librart for data analysis and manipulation.

* [Facebook Prophet](https://facebook.github.io/prophet/) - A forecasting library developed by Facebook. 

* [hvplot](https://hvplot.holoviz.org/) - A high level API for plotting data.

---

## Installation Guide

Download and install [Anaconda](https://www.anaconda.com/products/individual-b)

Open terminal and install Pandas by running this command:

    pip install pandas

Open Google Colab and upload the notebook file to open it. 

Facebook Prophet has some trouble getting installed on some machines so instead in the notebook you will see this block of code at the top to install Facebook Prophet:

    from IPython.display import clear_output
    try:
        !pip install pystan
        !pip install fbprophet
        !pip install hvplot
        !pip install holoviews
    except:
        print("Error installing libraries")
    finally:
        clear_output()
        print('Libraries successfully installed')

Click on each cell to run individually:

    Shift + Enter

---

## Example

Running this cell plots the components of the forecasting so that you can get a better understanding of the data.

![Code Example]()

---

## Contributors

*  Talib Kateeb

---

## License

[Click Here To View](https://github.com/talibkateeb/MercadoLibre-Time-Series-Forecasting/blob/main/LICENSE)
