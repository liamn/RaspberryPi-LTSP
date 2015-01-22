RaspberryPi-LTSP for Kirkbie Kendal School
================

### Development should be undertaken on the develop branch. Liam will then merge to master and perform update on server.

This is a fork of RaspberryPi-LTSP by Andrew Mulholland. Most of the work here is specific to Kirkbie Kendal School, but we'll be sending pull requests to the main project for any interesting features that we develop.
      
##Raspi-LTSP Documentation Site - http://pi-ltsp.net   
------   
###"*Raspi-LTSP is a utility for setting up the infrastructure required for a permanent classroom set of Raspberry Pis."*    
RaspberryPi-LTSP is has been written to help support educators in using the Raspberry Pi computer in their classrooms   
Its main features include
- **Network based user accounts** - A student can log onto any Raspberry Pi in the classroom and have access to their files. Their files are stored centrally on the server.
- **Centralised master operating system** - All the Raspberry Pis boot a single master operating system from the server every boot. So no more need to flash Raspbian onto 30+ SD cards. Just copy 30mb onto the SD cards.
- **Automated work submission and collection system** - A teacher can easily collect work from students digitally completely automatically for marking without the need for printing.
- **Shared folders** - Teachers can set up shared folders which are available to every Raspberry Pi in the classroom. These can be set up as read-only or read/write for students.   
- **Easy installation of software** - Software can be easily installed with from a menu of suggested packages including Libreoffice, ScratchGPIO5 and Python hardware libraries (like the Pibrella library).  
- **Epoptes classroom management software integration** - Epoptes classroom management software is integrated automatically allowing educators to blank students screens, reboot or shutdown all Raspberry Pis.
- **Easy to configure backups** - Educators can easily setup backups for the entire classes work to be saved on an external hard drive on a daily or weekly basis.   
- **It is completely free and open-source** - RaspberryPi-LTSP is completely free and open-source for everybody!   
- **Extensive documentation** - Alongside RaspberryPi-LTSP, there is also an extensive website of documentation with currently over 30 sections covering all features with over 100 images/screengrabs. This can be found at [http://pi-ltsp.net](http://pi-ltsp.net).   
- **Fully supports the OCR GCSE CS A452 task\*** - RaspberryPi-LTSP full supports the OCR GCSE Computer Science A452 Linux task which requires students to be able to work with files, create users and groups and also install software. All of this is possible with RaspberryPi-LTSP.   
     
          
RaspberryPi-LTSP is designed for teachers to setup their own mini Raspberry Pi networks. 
The installation process is extremely simple and well supported by the documentation. 
It is so simple, we even have an 11 year old who manages his entire schools RaspberryPi-LTSP network for the teachers of the school in his spare time.      
   
Simplicity is the key to RaspberryPi-LTSP.   

\* The OCR GCSE CS A452 task is not supported on the original Raspberry Pi model B revision 1 with 256mb of RAM as it is unable to install ```tree``` due to a lack of RAM.

![Lapdocks](images/lapdock-ltsp.jpg)

##Feedback
A number of schools across the world have been trialing the Alpha versions of RaspberryPi-LTSP for a number of months now.   
The overall feedback has been excellent with overwhelmingly positive feedback from educators.   

----
   
*"I see no other way an educator can use Raspberry Pi effectively in a classroom on a day to day basis without RaspberryPi-LTSP"* - **Ben Smith, ArnoldKEQMS school.**   

*"After the initial setup of Raspi-LTSP, the server makes running a Pi club so much easier. The user accounts make it ideal for having multiple sessions with different students without the hassle of knowing who's work is on what Raspberry Pi"* - **Ryan Walmsley, North Hertfordshire College
Raspberry Pi Club.**


##WARNING

The software included should work but is not heavily tested with every new code change. Consider it Alpha quality software.   
It is recommended, if you are interested in bringing this into your school, feel free to contact Andrew (lead developer) via the [support page](http://pi-ltsp.net/support.html).  
For details on the licence of this project, see the LICENCE file.
