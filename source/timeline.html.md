---
layout: page
title: Weekly Timeline
---

Week 1: Introduction to Ruby and Programming

    Starting and using IRb/Pry
    Ruby basic datatypes, including arrays and hashes
    Explanation of symbols
    Variable assignment
    Input and output with puts and gets
    Using your editor and running Ruby scripts
    Object-oriented design
        I use a simplified version of SOLID, called RISE:
            Single Responsibility Principle
            Isolate side effects
            Replicate existing interfaces
            Easily testable
    Creating and organizing classes
    attr_accessor, attr_reader, and attr_writer
    String interpolation
    Control flow and logic
    Blocks
    Ruby project layout
    Debugging with byebug
    Testing with MiniTest

Week 2
Advanced OO & Ruby

    Variable arguments for methods
    Method visibility
    Inheritance
    Modules/mixins
    Class methods
    Bundler

Introduction to the Web

    HTML elements
    Basic CSS
    Middleman or other static site generator
        Layouts & partials

Week 3
Static sites, continued

    Sass
    A CSS framework -- Zurb Foundation, Twitter Bootstrap, or Bourbon and friends are recommended
    Middleman or other static site generator
        Dynamic pages from data
        Helpers
        Plugins
            middleman-blog
            middleman-deploy

Rails

    History of Rails
    MVC architecture explained
    Rake
    Scaffolding
    ActiveRecord models
        Built-in validations
        Custom validations
        Migrations
        belongs_to and has_many associations
        Simple queries
    Controllers and routes
        Custom controllers
        Resource routes
        Simple routes
        Strong parameters
    Views
        Custom views -- not scaffolds
        Form helpers

Week 4: Rails in Detail

    ActiveRecord in detail
        has_one associations
        has_and_belongs_to_many and has_many :through associations
        Association methods
        STI and polymorphic associations
        Migrations and existing data
        Queries using SQL fragments
        .includes
        Using PostgreSQL (I use SQLite until this week.)
        Testing models
    Controllers and routes in detail
        REST
        Before, around, and after filters
        Sessions and the flash session
        Private methods in controllers
        Testing controllers
    Views in detail
        Forms
        Helpers
        Alternative template languages
    Deployment to Heroku
    Other testing tools
        Factories
        Fake data
        BDD

Week 5: Introduction to JavaScript

    Intro to JavaScript
    Using JavaScript in Rails
        UJS
        Remote actions
    Server-generated JavaScript responses
        escape_javascript
        dom_id
    jQuery
        DOM manipulation
        Ajax
        Animations
    Asset pipeline
        CoffeeScript or Opal (optional)
        External assets (vendor/assets, Bower, rails-assets.org)

Week 6 and 7: Rails Patterns

    Integration testing with Capybara or other library
    Authentication
        DIY
        Using a gem
    File uploads
    Pagination
    Building RESTful APIs
        Generating JSON and XML
    Some of the following:
        Tagging
        Favorites
        Sorting
        Search
        Asynchronous processing
        Drag-and-drop
        Consuming external APIs
        More advanced patterns
            Resize/Crop Image
            Expression Builder
            Live Preview
            Forgiving Format
            Edit In-Place
            Filter Information On-Page
        Advanced forms
            Add Another
            Select Existing Option or Add New Option
            Select Options Based on Previous Options
            Captcha
            Auto-Complete

Week 8: Flex Week

I don't have a clear plan for this week. I suggest doing one or more of the following:

    Cover a JavaScript framework like Backbone, Angular, or React
    Go in-depth on testing
    Add in more patterns
    Deployment to non-Heroku platforms

Week 9: Review and Prep for Final Project

    Review of the past 8 weeks
    Agile development
    Estimation
    Pitching

Week 10-12: Final Project

Students work on their final projects.
