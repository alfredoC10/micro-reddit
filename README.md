# Micro-reddit

## About
This is the second project from the Ruby on Rails module of the Microverse program. The objective only comprises the implementation of MVC's models to a database, so I was'nt required to perform any front-end development. Associations, migrations and validation helped build the models.

## good practices it looks for
- No spaces before semicolons
- Presence of a single space after a colon
- Presence of a single space after a comma
- Each selector must be in a new line when they are listed in the same rule

## Built with
- Ruby
- Ruby on Rails
- VS Code
- Rubocop linters

## Data model
- User table
- Posts table
- Comments table

## Getting started

### Prerequisites
- Browser (Google Chrome, Mozilla Firefox, Safari or any other browser)
- Text editor (strongly recommended VS Code)
- Empty directory where the repo is to be cloned

### To get a local copy of this repo
Run the following comands in the terminal in the next order:

- Step 1:  
$ cd "here comes the path of your selected directory (double quotes must not be here)"

- Step 2:
$ git clone https://github.com/alfredoC10/micro-reddit.git

### To start the app
- Step 1: cd to micro-reddit repository

- Step 2: To install all the required gems that are in the Gemfile, run:

  bundle install --without production 

- Step 3: To migrate the database, run:

  rails db:migrate

- Step 4: To open the rails console, run:

  rails console

-Step 5: For creating, posts, users and comments user_id must be defined in posts and comments and post_id in comments.

## Author

👤 **Alfredo Huemac**

- Github: [@Huemac-Alfredo](https://github.com/Huemac-Alfredo)
- Twitter: [@AlfredoHuemac](https://twitter.com/AlfredoHuemac)
- Linkedin: [Alfredo Huemac Córdova](https://www.linkedin.com/in/alfredo-huemac-c%C3%B3rdova-173b481b2/)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!

Feel free to check the [issues page](https://github.com/alfredoC10/micro-reddit/issues).

## Show your support

Give a ⭐️ if you like this project!

## Acknowledgments

- Microverse
- The Odin Project
- Anyone whose detailed code inspired the creation of this project, keep doing amazing stuff!