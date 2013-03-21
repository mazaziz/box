box
---
environments via vagrant and chef

quick setup
-----------

- clone *box* files into your project folder i.e: ***myproject*** :  
```
$ git clone --recursive https://github.com/mazaziz/box.git myproject
```

- cd into newly created project folder :  
```
$ cd myproject
```

- select a vagrant configuration that you want to build, i.e: ***nginx-php-postgresql*** :  
```
$ cp vagrantfiles/nginx-php-postgresql Vagrantfile
```

- you may further modify this *Vagrantfile* according to your needs  

- let vagrant and chef do all the remaining tasks :  
```
$ vagrant up
```
