# qr_email_send_by_gsheet

Goggle colab notebook for create qr-code with data from google sheet and send it by e-mail

Goggle colab ноутбук для генерации qr-кодов с данными из google таблицы и отправки e-mail

libraries and modules /библиотеки и модули

## генерация qr

import qrcode

## отправка e-mail smtp

import smtplib

## формирование тела письма

from email.mime.text import MIMEText

from email.mime.multipart import MIMEMultipart

from email.mime.base import MIMEBase

## кодирования информации в 64-разрядный код (6 бит), широко используемый в приложениях электронной почты

from email import encoders

## BeautifulSoup для парсинга html в текст

from bs4 import BeautifulSoup as bs

## Для работы с таблицей

import pandas as pd

## Для подулючения google drive

from google.colab import drive

from google.colab import auth

## Для работы с google sheets

import gspread

from oauth2client.client import GoogleCredentials

## Для работы с датой

from datetime import datetime
