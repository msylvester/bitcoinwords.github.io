# [WORDS](https://bitcoinwords.github.io/)

![](/assets/images/splash-about.png)

**WORDS** is a monthly journal of Bitcoin commentary. For the uninitiated, getting up to speed on Bitcoin can seem daunting. Content is scattered across the internet, in some cases behind paywalls, or even lost forever. **WORDS** was created to preserve and further the understanding of Bitcoin.

### [Read WORDS](https://bitcoinwords.github.io/)

## Goals and Scope
**WORDS** is one of the first Bitcoin journals, established February 13, 2019. It's purpose is to archive and spread commentary and research in the disciplines of particular interest to various Bitcoin communities. The journal is broad in scope, publishing content from original research, essays, blog posts, and tweetstorms from a wide variety of fields, especially technology, philosophy, politics, economics, and finance, but also game theory, law, history, criticism, and social or cultural analysis. It's broader mission is to capture the conversations and think pieces about Bitcoin for current and future researchers.

## History
There exists a gap in Bitcoin publishing. For authors with commentary and on Bitcoin topics, the choice of publication outlets is relatively limited. The number of journals that serve as outlets for Bitcoin research is **too small**, as the number of Bitcoin thinkers continues to grow with each epoch.

This generation of Bitcoin thinkers have limited places to submit thought pieces for publication. Content is scattered across the web, and in some cases behind paywalls which prevent the free flow of information. With the advent of Twitter and blogging, authors also now have the option of self-publishing: they post the content to their own site or a private site, link it in a blog post, or post a working paper. But this is obviously not the best way to document and publish. What is needed is a journal that takes full advantage of the possibilities of the digital age as a go to resource for think pieces in the Bitcoin space. 

Enter **WORDS**. Published independently, **WORDS** is a Bitcoin journal that welcomes submissions on a range of topics of interest to various Bitcoin communities.  In addition to conventional research articles, we welcome review essays blog posts, tweets as well as papers in other formats, such as distinguished lectures. Authors retain ownership without restriction of all rights under copyright in their articles. **WORDS** is open access, and we encourage readers to “[read, download, copy, distribute, print, search, or link to the full texts of these articles… or use them for any other lawful purpose.](https://doaj.org/faq#definition)”. This is an archival project on a mission to capture the spirit and voice of the Bitcoin community for future generations.

## Free and Open Source
**WORDS** follows the philosophy of Bitcoin by making this project open source. Because open source code is publicly accessible, students and can easily study the contents of **WORDS** as they do their own research. Users can easily fork **WORDS** and build their own copy.

[![](https://badgen.net/badge/Built%20with/❤️%20by%20Joe/F96854)](https://twitter.com/_joerodgers)

## Building 
In order to run locally, ensure you have Rails installed. Using HOMEBREW:

```ALGOLIA_API_KEY='848a5f8d9bfed7c9f51a3f795c9a6735' bundle exec jekyll algolia
brew install rails
```bash

Next, update **_config.yml** with the account information from [Algolia](https://www.algolia.com/). In order to build, you will need the ApplicationID, Frontend API key and Admin API Key. You also need to provide a value for the index key in **_config.yml**; although it can be any reasonable string. 

Once the config file is updated, prepare to build as follows:

```
bundle install
```bash

This preceding command builds the gem file and installs Rails dependecies. 

```
ALGOLIA_API_KEY='USEYOUROWN' bundle exec jekyll algolia

```bash
