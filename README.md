# hugosource
Source for Hugo Built danylaksono.github.io

## workflow for Hugo built

* made the change in source - content (e.g. new blog post)
* run hugo executable to compile 'public' directory
* cd to 'public' directory 
* (this is a submodule created prior to this steps using `git submodule --add <my github io repo> public`
* `git add --all && git commit -am "message" && git push origin master`
* cd back to /source and git push

