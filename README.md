# whmcs-autologin-email

Esto es una adaptación del código facilitado por WHMCS en https://docs.whmcs.com/AutoAuth

Debes subir el archivo mail-auto-login.php en la ruta /includes/hooks/ de tu WHMCS.

Debes incluir $autoauthkey = "aquíunaclavesegura"; en el archivo configuration.php de WHMCS

Una vez hecho esto podrás mostrar el link añadiendo {$linkauto} en cualquiera de las plantillas de email especificadas en el archivo mail-auto-login.php

Un saludo.
