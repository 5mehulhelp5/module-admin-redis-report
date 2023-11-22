<div align="center">

<!-- Module Image Here -->

</div>

<h1 align="center">element119 | Admin Redis Report</h1>

## 📝 Features
✔️ See a snapshot of the health of Redis from the comfort of the Magento admin

✔️ Supports Magento Open Source and Adobe Commerce

✔️ Built in accordance with Magento best practises

✔️ Dedicated module configuration section and custom admin user controls

✔️ Seamless integration with Magento

✔️ Built with developers and extensibility in mind to make customisations as easy as possible

✔️ Installable via Composer

✔️ Theme agnostic

### Upcoming
⏳ Data visualisation for both current and historic Redis health data

<br/>

## 🔌 Installation
Run the following command to *install* this module:
```bash
composer require element119/module-admin-redis-report
php bin/magento setup:upgrade
```

<br/>

## ⏫ Updating
Run the following command to *update* this module:
```bash
composer update element119/module-admin-redis-report
php bin/magento setup:upgrade
```

<br/>

## ❌ Uninstallation
Run the following command to *uninstall* this module:
```bash
composer remove element119/module-admin-redis-report
php bin/magento setup:upgrade
```

<br/>

## 📚 User Guide
Configuration for this module can be found in the Magento admin under `Stores -> Settings -> Configuration -> Advanced
-> System -> Redis Report`.

<br>

### Redis Report
The Redis information can be found in the admin under `System -> Tools -> Redis Report`.

<br>

### Enable/Disable Historic Data
The periodic capture of Redis information can be disabled by setting this option to `No`. This is set to `Yes` by
default.

<br>

### Historic Data Retention Period
The value specified here determines how long Magento will store historic Redis report data, measured in days.
An empty value means data will be kept indefinitely.

## 📸 Screenshots & GIFs
### Admin Configuration
![admin-config](https://github.com/element119/module-admin-redis-report/assets/40261741/853aea10-d995-4cb1-a4d7-9dc7cdccafd3)


<br>

### Admin Report
![admin-report](https://github.com/element119/module-admin-redis-report/assets/40261741/c679fd5f-802c-49b3-b279-a8cce75e5c44)
