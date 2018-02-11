cmake_minimum_required(VERSION 3.9)
project(woongh_github_io)

set(CMAKE_CXX_STANDARD 11)

include_directories(.)
include_directories(_posts)
include_directories(assets)

add_executable(woongh_github_io
        _posts/2017-10-20-welcome-to-jekyll.markdown
        _posts/2017-10-21-is.md
        _posts/markdown.markdown
        assets/JrO0PUj.jpg
        assets/TheSchoolOfAthens.jpg
        404.html
        _config.yml
        about.md
        Gemfile
        Gemfile.lock
        index.md)
