**Falcon**
```
pip install falcon
pip install falcon-cors
pip install falcon-multipart
pip install waitress
waitress-serve --port=8000 main:app
```

**Tools**
maldrolyzer <br>
https://github.com/maldroid/maldrolyzer <br>
Installation <br>
```
pip install -U androguard
pip install pycrypto
pip install pyelftools
pip install yara
```
<br>
androwarn
<br>

```
pip install androwarn
```

<br>
Deleted fields in androwarn report
<br>

**Application**
'package_name'         ,
'description'

**APK**
'file_name'            ,
'fingerprint'          ,
'file_list'                 

**Manifest**
'main_activity'        ,
'sdk_versions'         ,
'activities'           ,
'services'             ,
'receivers'            ,
'providers'            ,
'features'             ,
'libraries'

**APIs**
'classes_list'         ,
'internal_classes_list',
'external_classes_list',
'classes_hierarchy'    ,
'intents_sent'

<br>

```
pip install mysql-connector

CREATE DATABASE cybsec;

USE cybsec;

CREATE TABLE IF NOT EXISTS `status` (
  `id` int(11) NOT NULL AUTO_INCREMENT,
  `status` varchar(255) NOT NULL,
  `name` varchar(255) NOT NULL,
  `finish_time` varchar(50) DEFAULT NULL,
  PRIMARY KEY (`ID`)
);
```
