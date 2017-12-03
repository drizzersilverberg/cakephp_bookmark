# CakePHP 3 The Basic

## What You Should Know

    * Familiar with using the terminal
    * Comfortable with object-oriented PHP
    * Comfortable with relational databases

## Overview of CakePHP

### CakePHP

    * Modern PHP object-oriented framework
    * Rapidly build web applications
    * Convention over configuration
    * MIT licensed framework
    * Official site: http://cakephp.org
    * Official documentation: http://book.cakephp.org

### Framework

    `A common set of tools and patterns for approaching groups of problems`

    `CakePHP is best at building web applications using relational databases; for example, MySQL.`

### PHP Requirements

    * PHP 5.4.16 for CakePHP 3.0 through 3.1
    * PHP 5.5.9 for CakePHP 3.2+

    `CakePHP approaches problems using the Model-View-Controller pattern.`

## CakePHP as an MVC Framework

### MVC

    `Model-View-Controller`

    `MVC is a pattern for separating concerns regarding the data of a system and the user interface for that same system`

    `Model is the database layer`
    `View is the presentation layer`
    `Controller joins model and view`

`User -> Dispatcher -> Controller -> Model -> Controller -> View -> HTML -> User`

## Convention over Configuration

    `Conventions are guidelines, not absolutes.`

    `Conventions = Speed`

    `Conventions = Less onboarding`

    `Conventions are replaceable`

## CakePHP Requirements

    * CakePHP 3.0 and 3.1 require PHP 5.4.16+
    * CakePHP 3.2 require PHP 5.5.9+
    * CakePHP supports PHP 7.0+

### PHP Extensions:

    * mbstring
    * intl

### Databases:

    * MySQL
    * PostgreSQL
    * SQlite
    * SQL Server

### Course Requirements:

    * SQlite
    * Command-line PHP 5.6+
    * Composer

## CakePHP Instalation

    via Composer:
    composer create-project --prefer-dist cakephp/app bookmarks

## CakePHP Folder Structure Conventions

    `CakePHP 3 follows PSR-4`

    `PSR-4 is an autoloading standard`

         * `bin` contains shell scripts to use cakephp from command line.
         * `config` contains configuration setup for application
         * `logs` is standard location in cakephp to read log files.
         * `plugins` contains installed cakephp plugins via composer
         * `src` core code of the application
            * `console` is cakephp codes that can used in command line
         * `tests` contains unit testing codes
         * `tmp` location to store any temporary cakephp files
         * `vendor`dependencies of the application
         * `webroot` css, js, images stored here

## CakePHP Naming Conventions

### CakePHP Controllers:

    * tagsController
    * familiesController

### CakePHP Controllers:

    * tagsTable
    * familiesTable

### CakePHP Entities:

    * tag
    * family

### CakePHP Database Tables

    * tags
    * families
        * id
        * name
        * tag_id

## CakePHP Shell

    * `bin/cake` -> view CakePHP app version, paths and available shells

    * `bin/cake server` -> run cakephp server (default: http://localhost:8785)
