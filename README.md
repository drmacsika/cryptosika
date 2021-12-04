# CRYPTOSIKA: A Realtime cryptocurrency exhange rates and news app for trading crypto and visualizing the effect of news and sentiments on prices of various crytocurrencies.

Table of Contents:
- [Screenshots](#screenshots)
- [Tools](#tools)
- [Features](#features)
- [Installation and Usage](#installation)
- [Contributing](#contributing)
- [Credits](#credits)
- [Additional Info](#additional-info)

## Screenshots

![Blog Posts](https://github.com/drmacsika/am-backend/blob/master/templates/Screenshot%202021-10-23%20at%2020.48.16.png)

![Blog Category](https://github.com/drmacsika/am-backend/blob/master/templates/Screenshot%202021-10-23%20at%2020.48.28.png)

![Contact](https://github.com/drmacsika/am-backend/blob/master/templates/Screenshot%202021-10-23%20at%2020.48.39.png)

![User Accounts](https://github.com/drmacsika/am-backend/blob/master/templates/Screenshot%202021-10-23%20at%2020.48.48.png)

![User Auth](https://github.com/drmacsika/am-backend/blob/master/templates/Screenshot%202021-10-23%20at%2020.48.57.png)

## Tools

- React
- Redux ToolKit for state management
- Rapid API for getting live coin amounts
- Bing News API for gettings various realtime crypto news
- ANT Design
- ANT Design Icons
- Axios for interacting with the APIs
- Chart.Js for creating charts
- react-chartjs-2 for rendering the charts from charts.js
- Millify to convert extremely large numbers into readable strings
- html-react-parser  to parse html data
- moment to parse time and dates
- react-router-dom

## Features

- Asynchronous CRUD endpoints for blog posts and categories
- Asynchronous CRUD endpoints for contacts
- Asynchronous CRUD endpoints for user accounts
- Asynchronous endpoints for user authentication
- Production ready settings file using Pydantic
- Migrations using Alembic
- Secure password hashing by default.
- JWT token authentication.

## Installation and Usage

Use the package manager [pip](https://pip.pypa.io/en/stable/) for installation.

```bash
- python -m venv venv
- source venv/bin/activate
- pip install -r requirements.txt
- cd fastapi-async-blog
- alembic revision --autogenerate -m "Init"
- alembic upgrade head
- uvicorn main:app --reload
```

## Contributing

Pull requests and contributions are welcome. For major changes, please open an issue first to discuss what you would like to change.

Ensure to follow the [guidelines](https://github.com/drmacsika/fastapi-async-blog/blob/master/CONTRIBUTING.md) and update tests as appropriate.

## Credits

All thanks to Tiangolo, I found the [Project Generation - Template](https://github.com/tiangolo/full-stack-fastapi-postgresql) incredibly helpful.

## Additional Info

For an in-depth understanding of FastAPI or any of the tools used here including questions and collaborations, you can reach out to me.
