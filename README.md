<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- 1. Web Server: Have a web server (e.g., Apache, Nginx) installed and properly configured on your system.
- 2. PHP: Ensure you have PHP 7.1 or higher installed with necessary extensions like PDO, JSON, and XML.
- 3. Database Server: Set up a MySQL or MariaDB database server to store osTicket data.
- 4. Composer: Install Composer, a PHP dependency manager, to facilitate package installation.
- 5. Web Browser: Make sure you have a web browser to access the osTicket web-based interface.
- 6. Operating System: Compatible with Linux, Windows, or macOS operating systems.
- 7. File Permissions: Set appropriate file permissions to allow the web server to read and write necessary files.
- 8. SMTP Server (Optional): Configure an SMTP server if you wish to enable email notifications.
- 9. GD Library (Optional): If you plan to use images, ensure the GD library for image manipulation is installed.
- 10. Cron Jobs (Optional): For automation, set up cron jobs to handle scheduled tasks.
- 11. SSL Certificate (Recommended): Implement an SSL certificate for secure communication.
<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 1. Download: Clone or download the latest osTicket release from the official repository.
Step 2. Database Setup: Create a MySQL/MariaDB database and user for osTicket.
Step 3. Configuration: Rename include/ost-sampleconfig.php to include/ost-config.php. Edit with your database details.
</p>
<br />

<p>
<img ![image](https://github.com/Guled26/osticket-prereqs/assets/140678217/f162efd9-0ce6-4bee-b573-c327cee33774)
/>
</p>
<p>
Step 4. Web Server: Point your web server to osTicket's upload directory.
Step 5. Install Dependencies: Run composer install in osTicket's root directory.
Step 6. Web Installation: Open a browser, visit your osTicket URL, and follow the web installer.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 7. Setup Admin: Provide admin details, organization info, and email settings.
Step 8. Test & Done: Verify installation, and you're ready to manage tickets efficiently!
</p>
<br />
