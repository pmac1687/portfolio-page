basic hugo theme configuration. only theme templates being used in /layouts are index.html as home page, /_default/single.html and /_default/list.html.
-$ rm -rf public/ <--erases compiled site in /public
-$ hugo --verbose <--compiles new site into /public from files
-$ hugo server -D <--start webserver