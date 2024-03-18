# Silverstripe 3 Driver for Laravel Herd

A driver for Laravel Herd that allows the execution of Silverstripe 3 websites. 

## Installation

Add the Silverstripe3ValetDriver.php to the valet driver directory for your Herd installation, as described here: https://herd.laravel.com/docs/1/extending-herd/custom-drivers

E.g. directories (you'll have one or the other)
* `~/Library/Application Support/Herd/config/valet/Drivers`
* `~/Users/yourusernamehere/Library/Application Support/Herd/config/valet/Drivers`

I'm not sure if restarting is required, but I would recommend doing so just in case

## Tips

I recommend adding a symlink for the `Application Support` directory, as the space in the name breaks Silverstripe when attempting to run tasks via sake. I've just setup a symlink in the same folder for `ApplicationSupport` that points to `Appliction Support`

## Thanks

Thanks to Mattyboddy and his original driver: https://github.com/mattyboddy/valet-silverstripe-driver

I took his code and updated it to be compatible with PHP7 and Larevel Herd
