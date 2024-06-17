# Drupal DDEV Project

## Introduction

This project sets up a local development environment for a Drupal site using DDEV. DDEV is an open-source tool that makes it simple to get local PHP development environments up and running within minutes. It works with Docker to create consistent environments for development.

## Requirements

Before you begin, ensure you have the following installed on your local machine:

- [Docker](https://www.docker.com/get-started)
- [DDEV](https://ddev.readthedocs.io/en/stable/#installation)

## Project Setup

Follow these steps to set up the project:

### 1. Start DDEV
Initialize and start the DDEV environment run:
`ddev start`

### 2. Import the Database
If you have a database dump, you can import it using DDEV: `ddev import-db --src=./dbs/db.sql.gz
`

### 3. Install Drupal
Run: `ddev composer install`