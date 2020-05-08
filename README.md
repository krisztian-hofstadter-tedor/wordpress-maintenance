# wordpress-maintenance
workflow for wordpress maintenance

// somewhere along these lines the .maintenance file is deleted; 

0. PageSpeed test; 
1. backup files in CyberDuck;
2. backup database from CloudDashboard;
3. download up to date WP theme; 
4. switch to maintenance mode (based on http://sivel.net/) 
- 2 files needed: 
.maintenance-remove
/wp-content/maintenance.php

upload these to root; 
to enable maintenance mode, remove “-remove” from .maintenance-remove;
amend the maintenance.php file with the text you need to see; 
access the admin via /wp-admin

5. download plugin settings e.g: 
contact forms (tools>export) 
theme settings
theme CSS (should be in theme settings)
rev-sliders

6. update CMS
7. update plugins you can; 
8. update theme
- move current theme folder to another folder (one above)
- drag new theme folder (theme forest download) to theme folder;
9. update plugins again (MPC extensions?)
10. import theme settings;
11. validate contact forms? 
12. (CMS ask for database to be upgraded - did - is this necessary?)



upload custom CSS



