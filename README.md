# Immunization

It is a web app to take patient's medical history which helps to access patient's medical records and do analytics like the spread of immunization based on location.

Ideated and designed a web app to track widespread diseases using Django, Python, and HTML.

Implemented a notification system to send out reminder emails to get the vaccination to patients using Django framework APIs.

Implemented a Geo-location based heat map to track the spread of immunization using google map APIs.

# Summary

The advancement in usage of information and communication technology has changed the operational activities of most organization in recent times. The digitalization of health records and medication notes has made individual health data more readily accessible to a wide range of users including patients, doctors, researchers, statisticians, and data scientists. The problem of epidemic spreading has been widely studied by scientists from various fields, so the corresponding immunization strategy is also been extensively concerned. This project seeks the knowledge of some patients with respect to their data recorded in the healthcare system and the spread of vaccination. The paper further researched through statistical analysis of recorded data and predicts the mean of dependent variable given specific values of the independent variable.

The idea of this project is to store and retrieve the child medical records with mandatory vaccination schedule for each child based on their date of vaccination.

In this project, we would be predicting healthcare in various districts of India using past years records, Web scrapping of disease outbreak, diseases spread data from various websites, Associating the scrapped data with healthcare prediction to predict increase in immunization, decrement in number of people infected from diseases in all parts of India, Plotting Heat maps and data visualization of predicted data.

A web application with access to both parents and Doctor are proposed with necessary privileges. Reminders on timely vaccination are also proposed to parents regularly till the vaccination coverage of child is complete. Capturing and storing medical records in a common database can skip the need of carrying paperwork and can help in providing efficient and qualitative treatment to child. Applying analytics on the data can help in research findings in future.

# Installation Instructions
## Using Docker

1. Build the docker image
```bash
cd /path/to/this/folder
docker build -t immunization .
```
2. Run the image
```bash
docker run -it --rm --name immunization -p 8000:8000 immunization:latest
```
> NOTE: On windows, it might not work in Powershell, try it using cmd instead

---
## Using local python3

You can also run it locally, but might need to install additional system dependencies `build-deps gcc python3-dev musl-dev libxlt-dev postgresql-dev` - which may or may not exist on Windows.

1. This step is only required to be run once
```bash
pip3 install -r req.txt
```
2. Run the server
```bash
python3 manage.py runserver 0.0.0.0:8000
```
3. Use the following to check all available Django based sub-commands
```bash
python3 manage.py
```
> NOTE: Depending upon your python installation, you might need to replace `python3` with `python` and `pip3` with `pip`.

---