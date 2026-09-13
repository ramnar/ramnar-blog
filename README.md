# ramnar-blog

# Steps to Install Hugo

Download Hugo from the below location and install it

https://github.com/gohugoio/hugo/releases/tag/v0.166.0

hugo new project blog
Congratulations! Your new Hugo project was created in /home/ramnar/Documents/ramnar-blog/blog.

Just a few more steps...

1. Change the current directory to /home/ramnar/Documents/ramnar-blog/blog.
2. git submodule add https://github.com/michaelneuper/hugo-texify3.git themes/hugo-texify3
3. Edit hugo.toml, setting the "theme" property to the theme name.
4. Create new content with the command "hugo new content <SECTIONNAME>/<FILENAME>.<FORMAT>".
5. Start the embedded web server with the command "hugo server --buildDrafts".
