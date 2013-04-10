autogen-onetomany-annotations
=============================

Symfony2 での Entity 自動生成時に OneToMany 参照を自動生成させるパッチです。  
Doctrine の以下のファイルを修正します。  

	vendor/doctrine/orm/lib/Doctrine/ORM/Mapping/Driver/DatabaseDriver.php

対象バージョン：Symfony2.0 〜 Symfony2.2

参考：[(Symfony2) Entity の OneToMany のアノテーションを自動生成させる - モンモンブログ](http://monmon.hatenablog.com/entry/2013/04/10/150115)
