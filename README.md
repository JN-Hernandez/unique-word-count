# Unique Word Counter

## Description

A unique word counter designed as an exercise to learn Ruby on Rails.  This small Rails app will take a text input, count the number of words, count the number of unique words, and display the number of occurences for each unique word in order of most frequently used to least frequently used.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Tests](#tests)
- [How to Contribute](#how-to-contribute)
- [Credits](#credits)
- [License](#license)

## Installation

### Prerequisites

- Ruby 3.2.2
- Rails 7.0.6
- RubyGems
- SQLite3 3.32.3
- Chrome

### Instructions

1. Clone the repository locally

2. Run a database migration

`bin/rails db:migrate`

3. Run the Rails server application

`bin/rails server`

## Usage

1. Traverse to the application landing page in a web browser

`http://127.0.0.1:3000/`

*NOTE: This application has been tested in Chrome.*

2. Click `Article Listing`

3. Click `Create new article`

4. Enter in a `Title` and paste the article to word count in the `Text` field

5. Click `Create Article`

## Features

1. The unique word counter is not case sensitive!  "happy Happy HAPPY" would be considered to have a total word count of 3, with a unique word count of 1.

2. The unique word counter handles contractions - words like "can't", "don't", and "should've" will not mess up the counting process.

## Tests

Coming Soon

## How to Contribute

You're invited to contribute!  This project follows the [Contributor Covenant](https://www.contributor-covenant.org/) regarding contributions.

## Credits

The base for this application was created from the [Getting Started with Rails](https://guides.rubyonrails.org/v6.1/getting_started.html) documentation.

The template used for this README file was created from the Coding Boot Camp [Professional README Guide](https://coding-boot-camp.github.io/full-stack/github/professional-readme-guide)

The template used for the CHANGELOG file was created from the [Keep a Changelog](https://keepachangelog.com/en/1.0.0/) guide.

## License

This project uses the [MIT License](https://github.com/rails/rails/blob/main/MIT-LICENSE), Copyright (c) David Heinemeier Hansson

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
