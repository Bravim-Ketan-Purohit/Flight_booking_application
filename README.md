
# Flight Booking app

## FEATURES

User / Admin login and sign UP

Add / Remove flights

Search and filter flights

Dynamic seating for each flights

STRIPE payment gateway(please use dummy credentials while testing)

Logout feature



## Screenshots

![App Screenshot](https://github.com/Bravim-Ketan-Purohit/Flight_booking_application/blob/main/client/screenshots/register.png)

![App Screenshot](https://github.com/Bravim-Ketan-Purohit/Flight_booking_application/blob/main/client/screenshots/login.png)

![App Screenshot](https://github.com/Bravim-Ketan-Purohit/Flight_booking_application/blob/main/client/screenshots/home1.png)

![App Screenshot](https://github.com/Bravim-Ketan-Purohit/Flight_booking_application/blob/main/client/screenshots/addflight.png)

![App Screenshot](https://github.com/Bravim-Ketan-Purohit/Flight_booking_application/blob/main/client/screenshots/bookflight.png)

![App Screenshot](https://github.com/Bravim-Ketan-Purohit/Flight_booking_application/blob/main/client/screenshots/users.png)


## STEPS FOR USAGE/TESTING

to run this app you should clone this repo into your local device using git clone <Repo_url.git> and

go to folder named Flight_booking_application

now in terminal write  "npm i"

whilst this happens open another terminal and come to yhis app again now goto "cd client"

there again write npm i

now in the previous terminal write "nodemon server" (note :  please give your environment variables in .env file for mongodb since it is only for my local env)

in another treminal write npm start

YOUR APP IS NOW UP AND RUNNING;

(in your database go to users collection and do is admin true for one user (yhia is task done by DBA) that user will be able to create and remove flights as well as make users admin and remove admin also)



