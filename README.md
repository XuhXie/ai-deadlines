## AI Deadlines [![Build Status](https://travis-ci.com/abhshkdz/ai-deadlines.svg?branch=gh-pages)](https://travis-ci.com/abhshkdz/ai-deadlines)

The project forks from [abhshkdz](https://github.com/abhshkdz/ai-deadlines)

This site is for [CCF Recommendation](https://www.ccf.org.cn/Academic_Evaluation/AI/)  papers.

This site focous on field of **NLP / ML / Data Mining/Software**

Countdown timers to keep track of a bunch of **NLP / ML / Data Mining/Software** conference deadlines.

## Contributing

To add or update a deadline:

- Fork the repository
- Update `_data/conferences.yml`
- Make sure it has the `title`, `year`, `id`, `link`, `deadline`, `timezone`, `date`, `place`, `sub` attributes
    + See available timezone strings [here](https://momentjs.com/timezone/).
- Optionally add a `note` and `abstract_deadline` in case the conference has a separate mandatory abstract deadline
- Send a pull request

## Usage

1. Update _data/conferences.yml

2. Run Script (You Need Ruby enviroment )

   bundle exec jekyll build --future

   bundle exec htmlproofer ./_site --only-4xx --check-favicon --check-html --url-ignore "/#.*/" --http-status-ignore "400,441"

3. Replace files in _site to your Server ( Like webapps in tomcat)