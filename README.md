# First Flask App — AWS EC2 Deployment

My first cloud deployment. A simple Python Flask app running on AWS EC2 — this is where I learned how to launch a server, connect to it, and get a web app running on the internet for the first time.

---

## What this project does

A basic Flask web server that displays output in the browser. Simple app — but the real learning was the infrastructure around it.

---

## What I set up

- Launched an AWS EC2 instance (Ubuntu Linux)
- Connected to the server via EC2 terminal
- Installed Python and Flask on the server
- Ran the Flask app directly on EC2
- Accessed the output from a browser using the EC2 public IP

---

## What I learned

This was my first time working with a real cloud server. Key things I understood here:
- How EC2 instances work (launch, connect, configure)
- How to run a Python app on a remote Linux server
- How a browser connects to a server using an IP address
- The difference between running code locally vs on a cloud server

---

## How this project led to the next one

After this, I built a multi-page Flask app with HTML templates and CSS. Then I went further — deploying with Nginx, Gunicorn, SSL, and PEM key authentication in my 3rd project.

---

## Why it's not live

Deployed and tested successfully. EC2 instance stopped to avoid AWS charges.

---

## Stack

Python · Flask · AWS EC2 · Ubuntu Linux

---

## Run locally

```bash
git clone https://github.com/Kishore-infra/first-cloud-project.git
cd first-cloud-project
pip install flask
python app.py
```
