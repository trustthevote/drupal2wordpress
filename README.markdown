Drupal2Wordpress
================

We started with [Mike Smullin's script](http://www.mikesmullin.com/development/migrate-convert-import-drupal-5-to-wordpress-27/) and tweaked it to work with the versions we are running (Drupal v5.1 blog to WordPress v2.7.1) and for our specific needs.

**Always work on local database copies!** Our data conversion approach is simple:

1. Dump the "live" Drupal database and use it to create a "local" Drupal database.
2. [Install WordPress](http://wordpress.org/download/) as your "local" Drupal database. Now you should have a "local" WordPress database running too.
3. Run the `drupal2wordpress.sql` script.
4. Check out your local WordPress site. All the posts and comments should be there.

This is only the database piece to the Drupal-WordPress migration. We'll be writing up more about our experience and posting it later.