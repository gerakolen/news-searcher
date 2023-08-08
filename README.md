# Introduction

This is a go application for finding news via the News API.


# Prerequisites

- You need to have [Go](https://golang.org/dl/) installed on your computer. The version used in this project is **1.20**.

- Sign up for a [News API account](https://newsapi.org/register) and get your
free API key.

# Setup

1. Clone this repository

```bash
git clone https://github.com/gerstudent/news-searcher
```

2. Create `.env` file following the example file `.env.example` and enter your News API Key.

3. `cd` into it and run the following command: `go build && ./news-searcher` to start the server on port 3000.

4. Visit http://localhost:3000 in your browser.
