# hzhseed

This library allow to generate a seeder file from existing table in current database (Laravel).

Installation:

composer require hzh/seeder

Use:

1. After Installation you must put this line in your config/app.php inside a providers array:

      Hzh\Seeder\HzhServiceProvider::class
      
      
2. Use this command to generate the seeder File:

      php artisan hzh:seeder tableName ModelName
      
3. Enjoy it!

