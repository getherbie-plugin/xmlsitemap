# Herbie XML-Sitemap Plugin

`Xml-Sitemap` ist ein [Herbie](http://github.com/getherbie/herbie) Plugin, das aus deinen Seiten und Blogposts 
automatisch XML-Sitemap generiert und als Seite für Google und andere Suchmaschinen bereit stellt.


## Installation

Das Plugin installierst du via Composer.

	$ composer require getherbie/plugin-xmlsitemap

Danach aktivierst du das Plugin in der Konfigurationsdatei.

    plugins:
        enable:
            - xmlsitemap


## Konfiguration

Unter `plugins.config.xmlsitemap` stehen dir die folgenden Optionen zur Verfügung:

    # if set no pages will be included (you do it manually)
    no_page: false


## Eigene Seite

Falls du mit `plugins.config.xmlsitemap.no_page` das automatische Hinzufügen der Seiten deaktiviert hast, kannst
du eigene Seiten hinzufügen. Wie eine solche Seite aufgebaut sein sollte, schaust du am Besten im Code des
Xmlsitemap-Plugins nach. 


## Demo

<https://www.getherbie.org/sitemap.xml>
