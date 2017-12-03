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

