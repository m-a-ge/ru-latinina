## A Problem the project is meant to solve

As a user I want to be able to read updates from ru-latinina.livejournal.com LiveJournal community on social networks (vk.com, facebook.com, twitter.com)
Whenever a new post is published in LiveJournal community it should be posted into social networks using pre-configured accounts

Associated Diagrams - [drive.google.com](https://drive.google.com/file/d/0Byhl_4Rt3a8kWm5nOEJvX2N4ejg/view?usp=sharing)

## To Do

* find out if livejournal.com has an API for that task
* consult vk.com API docs to see how to post content on their social network

# Details

## Methods or functions to implement

| Method | Description |
| ------ | ------------ |
| `get_posts_from_livejournal()` | Requests posts from livejournal.com and returns them in designed format |
| `post_updates_to_vk()` | Posts any updates to a configured account |

## LiveJournal XML-RPC API

* http://wh.lj.ru/s2/developers/f/LiveJournal_XML-RPC_Specification_(EN).pdf
* http://www.livejournal.com/doc/server/ljp.csp.xml-rpc.protocol.html
* http://www.livejournal.com/bots/

Implementations:

* https://github.com/daniilr/python-lj
* https://www.npmjs.com/package/livejournal
* http://thinkpython.blogspot.ru/2007/02/livejournal-flat-api.html

## vk.com API

* https://new.vk.com/dev/wall.post
