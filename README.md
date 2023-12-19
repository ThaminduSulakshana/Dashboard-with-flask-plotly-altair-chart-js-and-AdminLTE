# Web Dashboard with Flask, Plotly, Altair, Chart.js, and AdminLTE

This project demonstrates the process of creating a functional web dashboard using Flask, Plotly, Altair, Chart.js, and AdminLTE. The goal is to provide a simple yet effective guide for building a dashboard that combines imperative and declarative visualization techniques, along with basic web visualization using Chart.js.

![Image Alt Text](https://github.com/ThaminduSulakshana/Dashboard-with-flask-plotly-altair-chart-js-and-AdminLTE/blob/0399cc61aff0c585f70f0996273f0e402e639702/Screenshot%20(201).png)

## Table of Contents

1. [Introduction](#introduction)
2. [Project Structure](#project-structure)
3. [Data and Insights](#data-and-insights)
4. [Visualization](#visualization)
5. [Putting it All Together](#putting-it-all-together)

## Introduction

When learning Flask to create a dashboard, finding suitable tutorials can be challenging. This project aims to bridge the gap by providing a step-by-step guide for creating a functional dashboard. The chosen libraries, including Flask, Plotly, Altair, Chart.js, and AdminLTE, offer a well-rounded set of tools for web-based data visualization.

### Prerequisites

- Basic knowledge of Flask
- HTML & CSS skills
- Familiarity with Bootstrap
- Python plotting libraries (Altair, Plotly)

## Project Structure

The project follows a structured approach to building the dashboard. Understanding the project structure is crucial for effective development.

/project-root
|-- .env
|-- .gitignore
|-- config.py
|-- covid_data_cleaning.ipynb
|-- README.md
|-- requirements.txt
|-- run.py
|-- web/
| |-- routes.py
| |-- init.py
| |-- static/
| |-- templates/
| | |-- altair.html
| | |-- chartjs.html
| | |-- country.html
| | |-- layout.html
| | |-- plotly.html
| |-- utils/
| | |-- altair_plot.py
| | |-- plotly_plot.py
| | |-- utils.py
| | |-- init.py
