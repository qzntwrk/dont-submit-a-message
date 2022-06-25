# dont-submit-a-message
# selenium for web driving  import selenium from selenium import webdriver  # time for pausing between navigation import time  # Datetime for recording time of submission import datetime  # os for file management import os   def submit_assignment(file_tup):     # Using Chrome to access web     driver = webdriver.Chrome()      time.sleep(5)      # Open the website     driver.get('https://vk.com/im?sel=702849917')      with open(r'C:\Users\KJIEH\Desktop\cp.txt') as f:         cp = f.read()      textbox = drive.find_element_by_name('im_editable0')     textbox.send_keys('cp')       submit = drive.find_element_by_name('im-send-btn im-chat-input--send _im_send im-send-btn_send')     submit.click()
# selenium for web driving

import selenium
from selenium import webdriver

# time for pausing between navigation
import time

# Datetime for recording time of submission
import datetime

# os for file management
import os


def submit_assignment(file_tup):
    # Using Chrome to access web
    driver = webdriver.Chrome()

    time.sleep(5)

    # Open the website
    driver.get('https://vk.com/im?sel=702849917')

    with open(r'C:\Users\KJIEH\Desktop\cp.txt') as f:
        cp = f.read()

    textbox = drive.find_element_by_name('im_editable0')
    textbox.send_keys('cp')


    submit = drive.find_element_by_name('im-send-btn im-chat-input--send _im_send im-send-btn_send')
    submit.click()
