# Thursday Night Football

This is a repo for my shared project with [@RobinKiplangat](https://github.com/robinkiplangat) to build a custom webapp for our Social Football Team. The app keeps stats on our team matches every thursday

## Description

Welcome to **TN_football**, a web application built for managing our social football team. This application provides several features to manage matches, scores, player updates, and so much more!

## Key Features

1. Scheduled matches every Thursday, with a countdown to the next match.
2. Random selection of teams based on player presence.
3. An updated score table after every match.
4. Weekly updates feature, providing details about who played, scored, and made payments for the match location.

## Technologies

* Frontend: React, TypeScript
* Backend: Python
* Database: DynamoDB  

## Project Structure

```bash
|- TN_football 
    ├── frontend/         # Front-end code (React)
        ├── src            # Source files
           └── components  # Reusable UI Components
    └── backend           # Back-end Code
        ├── app
        ├── __init__.py
    ├── requirements.txt
    ├── README.md          # This file!
```
The `frontend` directory contains all front end related source codes and assets such as images or stylesheets. The `backend/` folder is where we will write server side python scripts that handle API requests from clients like mobile apps etc., while `__init__.py`, `requirements.txt` are project level configuration files used by pipenv package manager when setting up virtual environment.

Finally, there's also an optional `.gitignore` file which specifies what should be ignored in version control when committing changes locally.

## Contributing

Any contributions you make are greatly appreciated. Please read the [CONTRIBUTING.md](CONTRIBUTING.md) for details on the process for submitting pull requests to us.

## Acknowledgements

Include any resources that played a significant role in helping this project be successful.

## License

This project is licensed under the MIT License - see [LICENSE.md](LICENSE.md) for details.

