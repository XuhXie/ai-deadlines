## AI Deadlines [![Build Status](https://travis-ci.com/abhshkdz/ai-deadlines.svg?branch=gh-pages)](https://travis-ci.com/abhshkdz/ai-deadlines)

The project forks from [abhshkdz](https://github.com/abhshkdz/ai-deadlines)

Countdown timers to keep track of a bunch of **CCF papers** for **NLP / ML / Data Mining/Software** conference deadlines.

## Contributing

To add or update a deadline:

- Fork the repository
- Update `_data/conferences.yml`
- Make sure it has the `title`, `year`, `id`, `link`, `deadline`, `timezone`, `date`, `place`, `sub` attributes
    + See available timezone strings [here](https://momentjs.com/timezone/).
- Optionally add a `note` and `abstract_deadline` in case the conference has a separate mandatory abstract deadline
- Send a pull request
