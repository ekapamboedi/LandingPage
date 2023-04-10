<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About Project

This is a project for my thesis on Uni. It's a CRM base that Admin and User from different pages. The basic idea is user can order with 2 options, 
1. Order onsite.
user order from the cashier.
2. Order Online.
User using their phone and scans barcode that printed on each table to access User Page.

**ADMIN PANEL**
Only Admin that registered can access this page.
The page login for users is using barcode that admin generated.
![Admin Login](https://user-images.githubusercontent.com/88288391/188733331-f6bf2b58-56b5-4ecb-bf49-83d45a13818e.png)

**DASBOARD** 
Dashboard for Admin.
![Dashboard](https://user-images.githubusercontent.com/88288391/188733732-a55e0524-a966-4442-9cfa-d6c6983a15ea.png)

**CRUD PRODUCT**
Admin need to input data of product, this data will shows on User page side.
![CRUD Produk](https://user-images.githubusercontent.com/88288391/188735061-ecb26ac6-49c6-43c4-835c-ab4187e6a6b8.png)

**CASHIER** 
This cashier is uses for user that order onsite.
![GIF Kasir Offline](https://user-images.githubusercontent.com/88288391/188735263-ac5a46bc-be58-4133-a156-5338684f173f.gif)

**TRACKING ORDER** 
On the real place we have a screen for user to track their order, for user that did order online they can track thier order from phone by access detail order too. 
![Halaman Proses Order](https://user-images.githubusercontent.com/88288391/188735425-b5df4fcc-d73a-496c-a65d-64b721f830ab.gif)

**ORDER LIST**
Admin can see incoming order whether its online or onsite. Admin can also see detail from order.
![Riwayat Order GIF](https://user-images.githubusercontent.com/88288391/188736295-af78dada-85cf-4eae-b940-bafe859aef99.gif)

**REPORT PDF** 
Admin can Export of report to PDF.
![EXport_pdf](https://user-images.githubusercontent.com/88288391/188736997-e378a428-b70b-4bef-99ec-904d0089afb4.gif)


## User Side
**HOME**
Page User need to scan barcode that printed on each table. The barcode is generated from Admin Panel.
![Home user](https://user-images.githubusercontent.com/88288391/188736816-c15b4bd6-2f93-42a5-b238-aca8c70ac975.png)

**CEHCKOUT** 
After user choosed item, the data will shows on checkout page. User can edit item if it needed.
![Checkout](https://user-images.githubusercontent.com/88288391/188737181-8f6d2b87-09ae-429c-a5bf-d230e84be331.png)

**PAYMENT** 
This web integerate with Midtrans Payment Gateway.
![Payment](https://user-images.githubusercontent.com/88288391/188737439-7f9000a7-3422-4049-8674-40c0b0af22ba.gif)

## Contributing

Thank you for considering contributing to the Laravel framework! The contribution guide can be found in the [Laravel documentation](https://laravel.com/docs/contributions).

## Code of Conduct

In order to ensure that the Laravel community is welcoming to all, please review and abide by the [Code of Conduct](https://laravel.com/docs/contributions#code-of-conduct).

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via [taylor@laravel.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed.

## License
The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
