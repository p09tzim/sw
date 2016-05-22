#Ανάπτυξη νέας σελίδας για το di.ionio.gr
Μαραγκός - Μπέλμπας Ελπιδοφόρος
ΑΜ Π2013016

##Tελική Αναφορά

Η εργασία αφορά την υλοποίηση νέας σελίδας για το τμήμα της Πληροφορικής.

Η παλαιά σελίδα χρησιμοποιούσε EOL έκδοση του CMS Joomla που σύντομα θα προκαλούσε προβλήματα ασφαλείας καθώς πλέον δεν υποστηρίζεται απο το Joomla Community.
Ο σχεδιασμός της δεν ήταν responsive καθιστώντας δύσκολη την περιήγηση απο κινητά και tables.
Υπηρχαν πολλά παλαιά άρθρα και ανακοινώσεις που δεν είχαν λόγο ύπαρξης και έκαναν τη σελίδα χαοτική.

Έγινε αλλαγή CMS απο Joomla 2.5.28 EOL σε WordPress.
Πριν το migration έγινε ένα γενικό "καθάρισμα" απο παλαιά άρθρα και ανακοινώσεις.

Μεταφέρθηκαν επιτυχώς πάνω απο 500 σελίδες, μαζί με όλα τα αρχεία και media καθώς και έγινε αλλαγή σε παραπάνω απο 800 εσωτερικούς συνδέσμους ανάμεσα στις σελίδες.

Η νέα υλοποίηση είναι κανονικά όπως και πριν, δίγλωσση χρησιμοποιώντας το premium plugin του WordPress WPML.

Ο νέος σχεδιασμός είναι μοντέρνος και πλέον responsive (φιλικός με smartphones και tablets κάθε ανάλυσης).

Έχουν λυθεί τα προβλήματα ασφαλείας που είχε η παλαιά σελίδα (εξαιτίας της outdated έκδοσης του cms που χρησιμοποιούσε).
Πλέον η ενημέρωση στην τελευταία έκδοση του CMS θα γίνεται πολύ εύκολα καθώς το WordPress παρέχει μηχανισμούς αυτόματου update.

Σιγά σιγά θα μπορούν να γίνουν και πολλές βελτιώσεις σε θέματα SEO, ταχύτητας, ασφάλειας και αξιοπιστίας όσο και νέες δυνατότητες όπως newsletter και σύνδεση με social media.

Η τελική υλοποίηση έχει ανέβει στον server του Πανεπιστημίου στον παρακάτω σύνδεσμο.

##http://corfu.ionio.gr/depts/di/

=================================
##Logs απο το migration

=== START test_database 2016-04-25 20:57:19 ===
Connected with success to the Joomla database
Joomla data found:
53 categories
243 articles
0 web links
2 users

=== END test_database 2016-04-25 20:57:19 ===

=== START save 2016-04-25 20:57:55 ===
Settings saved
=== END save 2016-04-25 20:57:55 ===

=== START import 2016-04-25 20:58:10 ===
Importing categories...
52 categories imported
Importing posts...
[ERROR] Can't copy http://emaragkos.gr/dijoomla/images/stories/cv/vlamos_cv_en_2014.pdf to /home/tsakmamg/public_html/emaragkos.gr/di/wp-content/uploads/2010/06/vlamos_cv_en_2014.pdf :
[ERROR] Can't copy http://emaragkos.gr/dijoomla/images/stories/cv/avlonitis_cv_gr_2013.pdf to /home/tsakmamg/public_html/emaragkos.gr/di/wp-content/uploads/2010/06/avlonitis_cv_gr_2013.pdf :
[ERROR] Can't copy http://emaragkos.gr/dijoomla/images/stories/news/smartbuilt.png to /home/tsakmamg/public_html/emaragkos.gr/di/wp-content/uploads/2013/03/smartbuilt.png : Not Found
[ERROR] Can't copy http://emaragkos.gr/dijoomla/images/stories/news/smartbuilt.png to /home/tsakmamg/public_html/emaragkos.gr/di/wp-content/uploads/2013/03/smartbuilt.png : Not Found
243 posts imported
138 medias imported
0 links categories imported
Importing web links...
0 web links imported
Importing users...
1 user imported
Importing menus...
126 menu items imported
Importing modules...
10 modules imported
233 Joom!Fish translations imported
Don't forget to modify internal links.
IMPORT COMPLETE
=== END import 2016-04-25 20:59:15 ===

=== START modify_links 2016-04-25 21:00:53 ===
893 internal links modified
=== END modify_links 2016-04-25 21:02:57 ===

=================================

##Logs από την εγκατάσταση στον server του Πανεπιστημίου

********************************************************************************
DUPLICATOR INSTALL-LOG
STEP1 START @ 05:43:17
NOTICE: Do NOT post to public sites or forums
********************************************************************************
VERSION:    1.1.6
PHP:        5.5.9-1ubuntu4.16 | SAPI: apache2handler
SERVER:     Apache/2.4.7 (Ubuntu)
DOC ROOT:   /var/www/depts/di
DOC ROOT 755:   false
LOG FILE 644:   true
BUILD NAME: 20160518_ceb9cf8ccebdceb9cebfcf80ceb1ce_573e206b75d4c4141160519202203
REQUEST URL:    http://corfu.ionio.gr/depts/di/installer.php
 
********************************************************************************
ARCHIVE SETUP
********************************************************************************
NAME:   20160518_ceb9cf8ccebdceb9cebfcf80ceb1ce_573e206b75d4c4141160519202203_archive.zip
SIZE:   52.32MB
ZIP:    Enabled (ZipArchive Support)
EXTRACTING
ZipArchive Object
(
    [status] => 0
    [statusSys] => 0
    [numFiles] => 6526
    [filename] => /var/www/depts/di/20160518_ceb9cf8ccebdceb9cebfcf80ceb1ce_573e206b75d4c4141160519202203_archive.zip
    [comment] =>
)
COMPLETE: true
 
WEB SERVER CONFIGURATION FILE RESET:
- Backup of .htaccess/web.config made to .orig
- Reset of .htaccess/web.config files
 
UPDATED FILES:
- SQL FILE:  '/var/www/depts/di/installer-data.sql'
- WP-CONFIG: '/var/www/depts/di/wp-config.php'
 
ARCHIVE RUNTIME: 9.2751 sec.
 
 
********************************************************************************
DATABASE-ROUTINES
********************************************************************************
--------------------------------------
SERVER ENVIROMENT
--------------------------------------
MYSQL VERSION:  5.5.49-0ubuntu0.14.04.1
TIMEOUT:    5000
MAXPACK:    16777216
--------------------------------------
DATABASE RESULTS
--------------------------------------
ERRORS FOUND:   0
DROP TABLE: removed (0) tables
QUERIES RAN:    18844
 
wp_bp_activity: (70)
wp_bp_activity_meta: (82)
wp_bp_friends: (6)
wp_bp_groups: (4)
wp_bp_groups_groupmeta: (16)
wp_bp_groups_members: (7)
wp_bp_messages_messages: (1)
wp_bp_messages_notices: (0)
wp_bp_messages_recipients: (2)
wp_bp_notifications: (11)
wp_bp_user_blogs: (1)
wp_bp_user_blogs_blogmeta: (7)
wp_bp_xprofile_data: (11)
wp_bp_xprofile_fields: (6)
wp_bp_xprofile_groups: (1)
wp_bp_xprofile_meta: (6)
wp_commentmeta: (0)
wp_comments: (8)
wp_duplicator_packages: (3)
wp_fg_redirect: (112)
wp_icl_content_status: (0)
wp_icl_core_status: (0)
wp_icl_flags: (64)
wp_icl_languages: (64)
wp_icl_languages_translations: (4096)
wp_icl_locale_map: (2)
wp_icl_message_status: (0)
wp_icl_node: (0)
wp_icl_reminders: (0)
wp_icl_string_positions: (0)
wp_icl_string_status: (0)
wp_icl_string_translations: (0)
wp_icl_strings: (0)
wp_icl_translate: (0)
wp_icl_translate_job: (0)
wp_icl_translation_batches: (0)
wp_icl_translation_status: (0)
wp_icl_translations: (1111)
wp_links: (0)
wp_options: (1629)
wp_postmeta: (7409)
wp_posts: (2237)
wp_rt_rtm_activity: (0)
wp_rt_rtm_api: (0)
wp_rt_rtm_media: (10)
wp_rt_rtm_media_interaction: (19)
wp_rt_rtm_media_meta: (8)
wp_signups: (0)
wp_term_relationships: (1159)
wp_term_taxonomy: (245)
wp_termmeta: (53)
wp_terms: (243)
wp_usermeta: (36)
wp_users: (2)
wp_wysija_campaign: (1)
wp_wysija_campaign_list: (1)
wp_wysija_email: (2)
wp_wysija_email_user_stat: (0)
wp_wysija_email_user_url: (0)
wp_wysija_form: (1)
wp_wysija_list: (2)
wp_wysija_queue: (0)
wp_wysija_url: (0)
wp_wysija_url_mail: (0)
wp_wysija_user: (12)
wp_wysija_user_field: (2)
wp_wysija_user_history: (0)
wp_wysija_user_list: (12)
Removed '51' cache/transient rows
 
SECTION RUNTIME: 8.0371 sec.
 
********************************************************************************
STEP1 COMPLETE @ 05:43:34 - TOTAL RUNTIME: 17.4651 sec.
********************************************************************************
 
 
 
********************************************************************************
DUPLICATOR INSTALL-LOG
STEP2 START @ 05:45:17
NOTICE: Do not post to public sites or forums
********************************************************************************
CHARSET SERVER: latin1
CHARSET CLIENT:  utf8
 
--------------------------------------
SERIALIZER ENGINE
[*] scan every column
[~] scan only text columns
[^] no searchable columns
--------------------------------------
wp_bp_activity~ (70)
wp_bp_activity_meta~ (82)
wp_bp_friends~ (6)
wp_bp_groups~ (4)
wp_bp_groups_groupmeta~ (16)
wp_bp_groups_members~ (7)
wp_bp_messages_messages~ (1)
wp_bp_messages_notices^ (0)
wp_bp_messages_recipients~ (2)
wp_bp_notifications~ (11)
wp_bp_user_blogs~ (1)
wp_bp_user_blogs_blogmeta~ (7)
wp_bp_xprofile_data~ (11)
wp_bp_xprofile_fields~ (6)
wp_bp_xprofile_groups~ (1)
wp_bp_xprofile_meta~ (6)
wp_commentmeta^ (0)
wp_comments~ (8)
wp_duplicator_packages^ (0)
wp_fg_redirect~ (112)
wp_icl_content_status^ (0)
wp_icl_core_status^ (0)
wp_icl_flags~ (64)
wp_icl_languages~ (64)
wp_icl_languages_translations~ (4096)
wp_icl_locale_map~ (2)
wp_icl_message_status^ (0)
wp_icl_node^ (0)
wp_icl_reminders^ (0)
wp_icl_string_positions^ (0)
wp_icl_string_status^ (0)
wp_icl_string_translations^ (0)
wp_icl_strings^ (0)
wp_icl_translate^ (0)
wp_icl_translate_job^ (0)
wp_icl_translation_batches^ (0)
wp_icl_translation_status^ (0)
wp_icl_translations~ (1111)
wp_links^ (0)
wp_options~ (1579)
wp_postmeta~ (7409)
wp_posts~ (2237)
wp_rt_rtm_activity^ (0)
wp_rt_rtm_api^ (0)
wp_rt_rtm_media~ (10)
wp_rt_rtm_media_interaction~ (19)
wp_rt_rtm_media_meta~ (8)
wp_signups^ (0)
wp_term_relationships~ (1159)
wp_term_taxonomy~ (245)
wp_termmeta~ (53)
wp_terms~ (243)
wp_usermeta~ (36)
wp_users~ (2)
wp_wysija_campaign~ (1)
wp_wysija_campaign_list~ (1)
wp_wysija_email~ (2)
wp_wysija_email_user_stat^ (0)
wp_wysija_email_user_url^ (0)
wp_wysija_form~ (1)
wp_wysija_list~ (2)
wp_wysija_queue^ (0)
wp_wysija_url^ (0)
wp_wysija_url_mail^ (0)
wp_wysija_user~ (12)
wp_wysija_user_field~ (2)
wp_wysija_user_history^ (0)
wp_wysija_user_list~ (12)
--------------------------------------
SEARCH1:    'http://emaragkos.gr/difinal'
REPLACE1:   'http://corfu.ionio.gr/depts/di'
SEARCH2:    '/home/tsakmamg/public_html/emaragkos.gr/difinal/'
REPLACE2:   '/var/www/depts/di/'
SCANNED:    Tables:68 | Rows:18721 | Cells:120596
UPDATED:    Tables:5 | Rows:2327 |Cells:3451
ERRORS:     1
RUNTIME:    6.545800 sec
====================================
DATA-REPLACE ERRORS (Serialization):
SELECT option_value, autoload FROM `wp_options`  WHERE option_id = "7008";
 
 
********************************************************************************
START FINAL CLEANUP: 05:45:24
********************************************************************************
NEW WP-ADMIN USER: Username 'admin' already exists in the database.  Unable to create new account
 
UPDATE `wp_blogs` SET domain = 'corfu.ionio.gr' WHERE domain = 'emaragkos.gr'
 
--------------------------------------
WARNINGS
--------------------------------------
 
WEB SERVER CONFIGURATION FILE BASIC SETUP:
created basic .htaccess file.  If using IIS web.config this process will need to be done manually.
********************************************************************************
STEP 2 COMPLETE @ 05:45:24 - TOTAL RUNTIME: 6.5680 sec.
********************************************************************************