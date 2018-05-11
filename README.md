# Magento2-language-es_cl

## Magento 2 Spanish (Chile) language package - Paquete de idioma Español (Chile) para Magento 2
Magento2 Spanish (Chile) language pack

## Instalación Automática

### Lo añadimos al composer del proyecto:

```
composer require semexpert/magento2-language-es_cl dev-master
```

### Lo instalamos a través de la consola de Magento

```
php bin/magento i18n:pack --mode=replace -d vendor/semexpert/magento2-language-es_cl/es_CL.csv es_CL
```

### Actualizamos el contenido estático

```
php bin/magento setup:static-content:deploy es_CL
```

### Recuerda limpiar la caché después de instalar el paquete de idioma