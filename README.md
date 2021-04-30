# 🍩 Donut
> Do not save in cookies, protect with donuts.


## What for?
Donuts is a simple database system, where it creates a cookie as a key, and with this unique key the user can have his own database, VERY useful for oAuth connections, permissions for pages, passwords and others.

## Resources
- 🧠 **Super** fast, no crashes.
- 📚 **Organized** php code.
- 🔐 Automatically **protected**.
- 🎊 Save any type of string, object, arrays..
- 🔧 **Practical** installation.

## How to use

### ⚠ Important warning:
**To activate the key system, you need to set `$isprivate` to `true` in the donuts file.**

### 🔨 Installation
- To get started, download the `donuts` file and place it in the folder where your php code is.
- After that, insert this into your php code:
```php
require 'donuts';
```
- The installation is already finished! time to learn to use.

> 💡 Donuts changes the permission of the database.json file automatically, if the file permissions are not `600`, change it manually.

The system is based on 2 things, tag and value.
For you to save an item, you need to define the tag, I will define as an example "fruit", now you will define the value, I will give the example as "banana".
```php
store_ ("fruit", "banana");
```
it will return true, so you can use it in the if without additional text. now if i want to get this value i will define only the tag, which was fruit.
Would be like this:
```php
echo get_ ("fruit");
```
it will return the value that I had set before: `banana`
If I want to delete the `fruit` from the database, I will give an example below:
```php
delete_ ("fruit");
```

I hope that you enjoyed. (✿◠‿◠)
