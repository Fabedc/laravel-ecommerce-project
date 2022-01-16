<p align="left"><img src="https://rahul.btao.in/wp-content/uploads/2021/09/F_Image.jpg" width="400"></p>

 

## Ecommerce Website using Laravel 5.8 

Gainaloe is my first e-commerce platform developed for the client, Really it was a great experience for me I have learned a lot from this project.
## Features
- User Dashboard 
- Admin Dashboard 
- Mobile-Friendly Website
- PayU Money Integrated
- Subscribe 
- 3 Step Booking Process
- Order Tracking 
- Email Notifications
- Pre-Defined Content with High-Resolution Photos 

## Requirements 
-   Laravel <=5.8
-   PHP <= 7.1.3
-   Composer Version 2 
## Installation Steps 

1.  <code> composer create-project rahulvijayam/ecommerce </code>
2. Create database for  your project with the name as <code>gainaloe</code>
3. Now Run <code>php artisan migrate</code> command for creating all the tables 
4. Add your email credentials in <code>.env</code> file
5. Add PayuMoney <code>merchant key and salt</code> on <code> config/indipay.php</code> file at line number 30 and 31
6. Start yor project using <code>php artisan serve</code>

## Generate Sample Data ( Optional)
1. Remove tables(products, users) from the  database.
2. Run two files present in this link https://github.com/RahulVijayam/ecommerce/tree/master/public/sql on your database
3. Finished, Now Check it in your browser using http://127.0.0.1:8000

### Dashboard Details
- Admin : http://127.0.0.1:8000/admin-dash
    -   Login Id : rahulvijayanagaram@gmail.com
    -   Password : 111111111
- User  : http://127.0.0.1:8000/dashboard 
 
### Watch Video
 [![Everything Is AWESOME](https://user-images.githubusercontent.com/36434065/141663839-bb06d652-1be7-4124-b3ba-76e6354bf456.png)](https://www.youtube.com/watch?v=TRr5OQ3YVIE "Watch Video")

## Security Vulnerabilities

If you discover a security vulnerability within project, please send an e-mail to me via [contact@rahulvijayam.com](mailto:contact@rahulvijayam.com). All security vulnerabilities will be promptly addressed.

## License

The project developed using laravel framework is open-source software licensed under the [MIT license](https://opensource.org/licenses/MIT).
