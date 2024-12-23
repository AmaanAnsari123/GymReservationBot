




<img src="https://user-images.githubusercontent.com/36112125/113499920-e8431a00-94e7-11eb-977a-0f0810a3a0e8.png" alt="Bot Logo" width="120"/>
[Gym Booking Automation Bot-Amaan]
:muscle: I created a Python-based bot to automate my gym time bookings at midnight effortlessly.

Problem:
Due to the COVID-19 pandemic, gyms in Varanasi implemented an online system requiring members to book specific workout slots. The booking system opens at midnight daily, which is inconvenient for me. To solve this, I developed a bot that handles the booking process autonomously.

Tools & Technologies Used:
Selenium WebDriver
Amazon EC2
Development Process:
:arrow_right: Analyzed and scraped my gym's website by inspecting the HTML elements.
:arrow_right: Automated the booking process with Selenium, using ChromeDriver to handle browser interactions.
:arrow_right: Deployed the script on AWS EC2 to ensure it runs in the cloud without local intervention.
:arrow_right: Used Putty to securely connect to the AWS EC2 instance.
:arrow_right: Scheduled a cron job to execute the script daily at midnight.

How to Use It:
:arrow_right: Clone this repository and set it up on your local system.
:arrow_right: Download and configure ChromeDriver to enable browser automation.
:arrow_right: Follow this guide here to set up and connect to an AWS EC2 instance for cloud execution.
:arrow_right: If cloud deployment isn’t feasible, you can use a local task scheduler (e.g., Windows Task Scheduler) to execute the script while your system is powered on.

Stay worry-free and let the bot secure your gym slots while you enjoy a good night’s sleep!
