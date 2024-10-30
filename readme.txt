=== Messesinfo ===
Contributors: sebastienserre
Tags: messes, horaires, messesinfo, egliseinfo, catholique
Requires at least: 4.6
Requires PHP: 7.0
Tested up to: 5.7
Stable tag: 1.5.8
Donate link: https://github.com/sponsors/sebastienserre/
License: GPL V3

== Description ==

Display mass schedule with shortcode in your WordPress Website
This service is freely provided by [Paroisse-catholique.fr](https://template.paroisse-catholique.fr/)

== Installation ==
1. unzip
2. upload to wp-content/plugin
3. Go to your dashboard to activate it
4. have fun!

== Frequently Asked Questions ==
= Comment afficher mes horaires de messes ? =
Avec le code court [messesinfo data-localityId=carmaux data-displayDetails=true data-display=TREE ].
* data-egliseinfo peut avoir 3 choix: horaires, lieu & communauté
ou le code court [messesinfo_no_option code_to_insert= '<div class="EgliseInfo-container"><div data-egliseinfo="communaute" data-communityid="ab/81/carmaux" data-open-in-egliseinfo="true"></div><script type="text/javascript" language="javascript" src="https://messes.info//Widget/Widget.nocache.js"></script>
                 <p>Retrouvez tous les horaires des célébrations sur <a href="https://messes.info//communaute/ab/81/carmaux">www.messes.info</a></p></div>']


= Where can I found the LocalityID? =
Sur le site de MessesInfo. Vous allez le trouver dans le code fourni par messesinfo pour partager les horaires sur vos
sites.

= Quelle différence entre les 2 codes courts proposés ?
* [messesinfo_no_option] n'attends qu'un seul paramètre `code_to_insert` qui sera le code entre guillemet fourni par
Messesinfos.
* [messesinfo] lui attends plusieurs parametres et peu donc être plus finement paramétrable.

= Where can I found help? =
Please ask your question on the WordPress forum // Tab Support


== Upgrade Notice ==

use automatic upgrade

== Changelog ==
* 1.5.8 Improve [messesinfo] Shortcode // Add [messesinfo_no_option]
* 1.5.7 Tested up to WordPress 5.7, Correct shortcode to make it working.
* 1.5.6 Rewrite Shortcode to work without Messesinfo API
* 1.5.0 rewrite the plugins to improve speed and maintenance
* 1.4.0 Add shortcode messeinfo_search
* 1.3.0 Ok with 4.8 -- Improve Shortcode and Widget search
* 1.2.5 Ok with WP 4.7
* 1.2.4 Correct API call after changement of API URL
* 1.2.0 Improve Shortcode and Widget by searching on the localityID.
* 1.1.0 add a widget and a Shortcode
* 1.0.1 & 1.0.2 translation bugfix
* 1.0.0 Initial version
