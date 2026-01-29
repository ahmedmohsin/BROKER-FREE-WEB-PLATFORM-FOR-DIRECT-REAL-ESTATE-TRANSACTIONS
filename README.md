##Key Features of the  Real Estate Website.

•	Admin Panel.

•	User Management.

•	Property Listing Management.

•	Blog Management System.

•	Agent Registration and Login.

•	Client Registration and Login.

•	Add Location Coordinates.

•	Advanced Property Search and Filters.

•	Enquiry system.

•	User Property Ratings and Reviews.

•	Comment and Reply System.

•	Image Gallery Management.

•	Slider/Image Banner Management.

•	Website Settings Control.

•	Service and Testimonial Management.

•	Dashboard Stats.

•	Message Notification System.

Installing Tools.
VS CODE.
XAMPP/WAMPP.
LARAVEL.
COMPOSER.
PHP.


## IMPOTANT NOTE

First, make sure you have Composer installed on your system. For Laravel projects, PHP Version 7 or higher is required as older versions are not compatible with Composer. As a result, you’ll need to manage your PHP version (only if you’re using the old version) at the moment.

## Instructions: How to Run?

•	After you finish downloading the project, unzip the project file.
•	Open the project folder, check for the env file, and update the database credentials as needed (DB name, username, password)
•	Create a MySQL database with the name defined in the env file.
•	Then, open the project in the Terminal or Command Prompt.
•	Install the composer dependencies: composer install
•	For the database, you can run the migration files to create a new one following the command lines.
•	Migrate the tables: php artisan migrate
•	Run seeder: php artisan db:seed
•	Then generate the key: php artisan key:generate
•	Create a symbolic link to the storage folder: php artisan storage:link
•	And finally, run the project: php artisan serve
•	It will start the application and give you a URL.
•	At last, open the URL in your preferred browser; we recommend using Google Chrome for the best performance.
•	All the login details are provided in the text files inside the project folder. Check them and enter them to use it.


## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
