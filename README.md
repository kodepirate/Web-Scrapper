# Web Scraper
A web scraper is a tool that is used to extract data from websites. This project is a simple web scraper built using Python and the Beautiful Soup library.

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites
You will need to have Python installed on your machine. This project was built using Python 3.8, but should work with any version of Python 3.

You will also need to install the Beautiful Soup library. This can be done by running the following command:

```
pip install beautifulsoup4
```

### Installing

To get the project up and running on your local machine, follow these steps:

**1.** Clone the repository to your local machine:
```
git clone https://github.com/kodepirate/Web-Scrapper.git
```
**2.** Navigate to the project directory:
```
cd Web-Scrapper
```
**3.** Run the script:
```
python scraper.py
```

## Usage
The web scraper is used by providing a URL and a CSS selector for the elements that you want to extract data from. The scraper will then extract the data and print it to the console.
```
python scraper.py <url> <css_selector>
```
For example, to scrape the titles of all the articles on the front page of the New York Times website, you could use the following command:
```
python scraper.py https://www.nytimes.com ".css-1ez5fsm"
```

## Built With

![Python](https://www.python.org/) - The programming language used

## Contributing
If you want to contribute to this project, please follow these steps:

Fork the repository
**1.** Create a new branch for your feature (git checkout -b my-new-feature)
**2.** Commit your changes (git commit -am 'Add some feature')
**3.** Push the branch (git push origin my-new-feature)
**4.** Create a new pull request

## License
This project is licensed under the MIT License
