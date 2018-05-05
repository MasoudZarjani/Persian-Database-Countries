# All Countries DataBase
دیتابیس و لیست کشورهای دنیا به زبان فارسی

Persian DataBase for use in mysql

### Getting started

#### Create Table

```php
CREATE TABLE `tbl_countries` (
  `CountryId` int(11) NOT NULL,
  `CountrySummary` varchar(3) COLLATE utf8mb4_persian_ci NOT NULL,
  `CountryName` varchar(40) COLLATE utf8mb4_persian_ci NOT NULL,
  `PhoneCode` int(11) NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_persian_ci;
```

