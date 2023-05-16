
# FastAPI and Postgres Dev Environment with Codespadces

This repo can be opened in a [Codespaces](https://docs.github.com/en/codespaces/overview) - a development environment hosted in the cloud. You can open this repo in a [browser](https://docs.github.com/en/codespaces/developing-in-codespaces/creating-a-codespace-for-a-repository) or IDE like [VS Code](https://code.visualstudio.com/docs/remote/codespaces) with the [GitHub Codespaces extension](https://marketplace.visualstudio.com/items?itemName=GitHub.codespaces).

## Running the sample

1. Copy *.env.devcontainer* to *.env*.

2. Start the web app:

  ```
  uvicorn main:app --reload
  ```

## Pydantic and SQLAlchemy

[Pydantic](https://docs.pydantic.dev/latest/) is for data validation and settings managment using Python type annotations. [SQLAlchemy]() is a SQL toolkit and Object Relational Mapper (ORM).
