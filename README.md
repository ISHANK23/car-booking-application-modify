# car-booking-application-modify

SE4030 - Secure Software Development Assignment
================================================

Member
------------
1. E.A.K. Hamangoda (IT20247218)


Project Links
-------------
Original project repository: https://github.com/ISHANK23/car-booking-application-Not_modify.git
Hardened project repository: https://github.com/ISHANK23/car-booking-application-modify.git

Video Walkthrough
-----------------
YouTube link: <insert video URL demonstrating the fixes and OAuth flow>


## Configuration
Inside this file 'inc/connection.inc.php' configure your details. 

$host = getenv('DB_HOST') ?: 'localhost';
$user = getenv('DB_USER') ?: 'root';
$password = getenv('DB_PASSWORD') ?: 'Add your password here';
$database = getenv('DB_NAME') ?: 'rentcar';

## Database
Import the updated schema located in `rentcar.sql`. It contains secure default credentials:

- **Admin login**: `admin` / `admin`
