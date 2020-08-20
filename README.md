# HerokuHello
Springbootのhello worldをherokuにデプロイしました  

https://herohe.herokuapp.com/  


herokuの公式が残念  
system.propertiesでjavaのversionを指定する必要がある  
Defaultは8系  
@Controllerと@RestControllerまちがってる  
heroku create filenameとかちゃんとかいてない  
windowsだとgit bashではheroku loginできないからloginだけcmdでやる必要あった  
pom関連はちゃんとやれば大丈夫だった  


