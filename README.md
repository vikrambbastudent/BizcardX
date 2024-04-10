# BizCardX-Extracting-Business-Card-Data-with-OCR
Problem Statement

"BizCardX-Extracting-Business-Card-Data-with-OCR" appears to involve the challenge of efficiently extracting data from business cards using OCR (Optical Character Recognition) technology. This suggests a desire to automate and streamline the process of capturing information from business cards, potentially eliminating manual data entry and enhancing the overall efficiency of handling business card data. The goal is likely to develop a solution that can accurately and quickly extract relevant information, improving the user experience and reducing the time and effort traditionally associated with managing business card data.

Technology stack used:
import streamlit as st
from streamlit_option_menu import option_menu
import easyocr
from PIL import Image
import pandas as pd
import numpy as np
import re
import io
import sqlite3

Features

(1) streamline the process of extracting text information from business card images.
(2) Leveraging EasyOCR, it employs OpenCV for image preprocessing tasks like resizing, cropping, and enhancement.
(3) The use of regular expressions (RegEx) facilitates the parsing and extraction of specific fields such as name, designation, company, and contact details.
(4) To ensure easy retrieval and analysis, the extracted information is stored in a MySQL database.
(5) For user convenience, a friendly interface built with Streamlit allows users to effortlessly upload images, extract information, and interact with the database, providing a seamless experience in managing business card data

Acknowledgments

*Streamlit: Used for building interactive web applications with ease, providing a user-friendly interface for tasks like uploading images, extracting information, and interacting with the database.

*EasyOCR: Employed for text extraction from images, facilitating the process of extracting relevant information from business card images.

*MySQL: Chosen as the database management system to store and manage the extracted information, making it easily retrievable and available for analysis.
