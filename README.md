Markdown files used to organize anything I (Larus Thor/lalli-oni) can think of.

## Tasks
1. [TODO] Figure out if this is a good platform to handle tasks management
2. [TODO] Figure out whether/how to integrate it my trello
## Growing garden
I have this personal "digital garden" which was intended to at least publish my notes. Right now the notes simply exist as `.md` files inside that repo. It only has 2 types of files.
1. `articles` which are both meant for me personally and to share publicly
2. `experiments` which are hybrid text content and web applications
It is written using SvelteKit and hosted using vercel.
- [TODO] Investigate whether we can use our synched public GitHub repo to build the content for the Growing Garden (or pull the content on runtime?)
- [TODO] Represent this obsidian solution in the Growing Garden.
- [TODO] Really "Growing Garden"? Shitty name IMHPO, I wanted to represent it's at least losely based on the digital garden concept and that it's very much a WIP
- [TODO] If we are to use the GitHub synched repo as a data source, we need to consider the synching process. I was already using the markdown metadata to control which articles are published, but should the growing garden be updated on synching? And if so, how to secure unintended synching? 
## Integrations
GitHub syncing plugin. Syncs between local files and [https://github.com/lalli-oni/notes](lalli-oni/notes) public repo.
## Patterns
Extensive use of tables. Use tags to connect entries between files.
1. [TODO] Find a structure that lends itself to relatively self contained concepts while promoting "views" across different dimensions. Fx. [[Generic Frontend]] has plenty of "misc." entries that spans other concepts
## Templates
```dataview
LIST
FROM "Markdown templates"
```
