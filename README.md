### Thank you for choosing the Arix Pterodactyl Theme.

To initiate the installation of the Arix Pterodactyl Theme, ensure that you have installed all the necessary assets:
https://pterodactyl.io/community/customization/panel.html

Simply drag and drop the files into your Pterodactyl folder.

Once the files are uploaded, execute the following 
> php artisan arix

In case the that you're experiencing an error anywhere during the installation process, try the following step: 
> php artisan migrate --force && php artisan optimize:clear && php artisan optimize && chmod -R 755 storage/* bootstrap/ccach

If you require more detailed information, please consult our documentation:
https://arix.gg/docs
