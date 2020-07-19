# README #

All different config and components created to run different REST APIs (hosted on local RPi) that are used by Alexa skills goes here.

### What is this repository for? ###

Placeholder to dump Apache config for Rest APIs called on RPi by Alexa.

### How do I get set up? ###

Create a folder with name ircc inside var/www
Create a file with name ircc.wsgi in the var/www/ircc folder
create another folder wth name ircc in var/www/ircc
keep all the py codes, your other json and txt files inside the newly created folder

In your /etc/apache2/sites-available, create ircc.conf and pt your csr and key files
make sure to link your irrc.conf inside your /etc/apache2/sites-enabled.

### Who do I talk to? ###

For any issues/help/suggestion contact piyushkumar.jiit@gmail.com
