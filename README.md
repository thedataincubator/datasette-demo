# Learning SQL with Datasette

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/thedataincubator/datasette-demo?quickstart=1)

[Datasette](https://datasette.io/) is a web-based tool for exploring and analyzing tabular data.  It runs on top of the [SQLite](https://sqlite.org/index.html) database engine, and it exposes the SQL queries that it runs.  As such, Datasette can be a useful tool to learn SQL by practicing analysis on your own data.

This repository is set up to run Datasette in [GitHub Codespaces](https://github.com/features/codespaces).  When you [open this repository in Codespaces](https://codespaces.new/thedataincubator/datasette-demo?quickstart=1), a cloud server will be started for you and Datasette is installed.  Access to the server is provided by a VSCode-based interface.

On first start, Datasette should automatically run (although it may take a minute to do so).  A button in the lower right should allow you to connect to the Datasette interface.  If it does not start automatically, you can start it by entering into the terminal
```bash
datasette data.db
```
Again, a button should appear, redirecting you to the Datasette interface.

## Data sets for Datasette

This environment is set up with [datasette-upload-csvs](https://datasette.io/plugins/datasette-upload-csvs), a Datasette plugin which allows you to upload any CSV file into the Datasette database.  For the demonstration, we will be using an [astronaut data set from Kaggle](https://www.kaggle.com/datasets/jessemostipak/astronaut-database).

## About the Data Incubator

The [Data Incubator](https://www.thedataincubator.com) is a leader in data science and data engineering training.
