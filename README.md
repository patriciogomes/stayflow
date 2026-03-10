# StayFlow AI

StayFlow AI is a lightweight booking request assistant built for small guesthouses.

Guests submit a booking inquiry through a simple web form. The request is instantly stored in **Google Sheets via Sheet Ninja**, and a **reply draft is generated automatically** for the host.

This helps reduce repetitive communication and keeps all booking inquiries organized in one place.

## Demo

Live demo:  
https://patriciogomes.github.io/stayflow/

## How it works

1. Guest fills out the booking request form.
2. The request is sent to the **Sheet Ninja API**.
3. Sheet Ninja stores the data directly in **Google Sheets**.
4. The app generates a reply draft for the host to send to the guest.

## Tech Stack

- **Sheet Ninja** – Google Sheets as backend
- **Google Sheets** – request storage
- **Vanilla JavaScript** – frontend logic
- **GitHub Pages** – hosting

## Why this project

I built this as a quick prototype for the **Sheet Ninja Vibe Coder in Residence challenge**.

The idea comes from real hospitality workflows where hosts manually respond to booking inquiries every day. This tool shows how quickly a working product can be built using Sheet Ninja as a backend.

## Author

Patrício Gomes
