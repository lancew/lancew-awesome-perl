# LanceW's Awesome Perl [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome Perl resources, including frameworks, libraries and software. Inspired by [awesome-perl](https://github.com/hachiojipm/awesome-perl).

### Another module list

This is my list of Perl tools I like to use or think are good for use even if I am not actively using it. This is not going to have a huge list of modules; think of it as my own personal currated slice of CPAN.

I allso recommend checking out these lists.

* [Task::Kensho](https://github.com/EnlightenedPerlOrganisation/task-kensho "Task::Kensho")
* [awesome-perl](https://github.com/hachiojipm/awesome-perl)


### Contents

- [Awesome Perl](#awesome-perl)
    - [Args](#args)
    - [Audio](#audio)
        - [Digital Signal Processing](#DSP)
    - [Benchmarks](#benchmarks)
    - [Caches](#caches)
    - [Class Builder](#class-builder)
    - [CLI](#cli)
    - [Cloud](#cloud)
    - [Cryptography](#cryptography)
    - [Commercial WebServices](#commercial-webservices)
    - [Container](#container)
    - [Data Format](#data-format)
    - [Database](#database)
    - [Database Drivers](#database-drivers)
        - [Relational Databases](#relational-databases)
        - [NoSQL Databases](#nosql-databases)
    - [Date & Time](#date--time)
    - [Devices](#devices)
    - [DevOps](#devops-tools)
    - [Email](#email)
    - [Event Loops](#event-loops)
    - [Exception Handling](#exception-handling)
    - [DOM Manipulation](#dom-manipulation)
    - [File Manipulation](#file-manipulation)
    - [Form Frameworks](#form-frameworks)
    - [Images](#images)
    - [List Manipulation](#list-manipulation)
    - [Logging](#logging)
    - [Module Development](#module-development)
    - [Network](#network)
    - [ORM](#orm)
    - [Package Management](#package-management)
    - [Processes and Threads](#processes-and-threads)
    - [Profiling](#profiling)
    - [Protocol](#protocol)
    - [Queueing](#queueing)
    - [REST Frameworks](#rest-frameworks)
    - [Science/Numerics](#sciencenumerics)
    - [Stream Manipulation](#stream-manipulation)
    - [Template Engines](#template-engines)
    - [Testing](#testing)
        - [Testing Frameworks](#testing-frameworks)
        - [Test Double](#test-double)
        - [Coverage](#coverage)
    - [Tools](#tools)
    - [Type Checking](#type-checking)
    - [Video](#video)
    - [Web Frameworks](#web-frameworks)
        - [Middlewares](#middlewares)
    - [Web Frameworks-Like](#web-frameworks-like)
    - [Web Scraping](#web-scraping)
    - [Network Security](#Network-Security)
    - [Digital Forensics](#Metadata-Forensics)
    - [Reverse Engineering](#Reverse-Engineering)

## Args

*Libraries for argument manifestation and validation.*


* [Params::Validate](https://metacpan.org/pod/Params::Validate) - Validate method/function parameters.


## Audio

* no experiences here

## Benchmarks

*Libraries for benchmarking*

* [Benchmark](https://metacpan.org/pod/Benchmark)
* [Dumbbench](https://metacpan.org/pod/Dumbbench)
* [Parallel::Benchmark](https://metacpan.org/pod/Parallel::Benchmark) - Benchmark in multiprocesses

## Caches

*Libraries to talk to Cache Softwares*

* todo

## Class Builder

*Libraries to support writing classes and meta programming*

* [Moo](https://metacpan.org/pod/Moo) - Great for light touch Moose.
* [Moose](https://metacpan.org/pod/Moose) - OOP defacto standard for when Moo is not enough.

## CLI

*Libraries for developing CLI applications*

* [Getopt::Long](https://metacpan.org/pod/Getopt::Long) - Extended processing of command line options.

## Cloud

* ??

## Cryptography

* ??

## Commercial WebServices

* ??

## Container/IoC

*Libraries for containers/Inversion of Control

* [Bread::Board](https://metacpan.org/pod/Bread::Board)

## Data Format

*Libraries for serializing, formatting and parsing*

* ---

## Database

*Libraries for dealing with relational databases*

* [DBI](https://metacpan.org/pod/DBI)
* 

## Database Drivers

*Libraries for using specific database products*

### Relational Databases

* [DBD::mysql](https://metacpan.org/pod/DBD::mysql)
* [DBD::Pg](https://metacpan.org/pod/DBD::Pg) - PostgreSQL driver for DBI.
* [DBD::SQLite](https://metacpan.org/pod/DBD::SQLite)

### NoSQL Databases

* --

## Date & Time

*Libraries for working with dates and times*

* [DateTime](https://metacpan.org/pod/DateTime)
* [Time::Piece](https://metacpan.org/pod/Time::Piece)

## Devices

*Libraries to talk to physical devices*

* ---

## DevOps Tools

*Libraries that help when you want to deploy software across networks on several hosts/are working across computer networks*

* [Rex](https://metacpan.org/pod/Rex) - Remote Execution

## Email

*Libraries that implement email creation and sending*

* ---

## Event Loops

*Libraries for various event loops. Asynchronous programming if you like*

* --

## Exception Handling

*Libraries that assist with and/or provide alternatives to eval{ die() }*

* [autodie](https://metacpan.org/pod/autodie) - Replace functions with ones that succeed or die with lexical scope
* [Try::Tiny](https://metacpan.org/pod/Try::Tiny) - minimal try/catch with proper preservation of $@

## DOM Manipulation

* --

## File Manipulation

* --

## Form Frameworks

*Libraries that take the boredom & repetition out of (web and UI) forms*

* [HTML::FormHandler](https://metacpan.org/pod/HTML::FormHandler) - HTML forms using Moose.


## Images

*Libraries for manipulating images*

* --

## List Manipulation

*Libraries for manipulation lists (arrays)*

* [List::MoreUtils](https://metacpan.org/pod/List::MoreUtils) - Provide the stuff missing in List::Util
* [List::Util](https://metacpan.org/pod/List::Util) - A selection of general-utility list subroutines


## Logging

*Libraries for generating and working with log files*

* --

## Module Development

*Libraries that simplify and improve Perl module development*

* [Dist::Zilla](https://metacpan.org/pod/Dist::Zilla) - <http://dzil.org/>

## Network

*Libraries that help when you are dealing with computer networks*

* --

## ORM

*Libraries that implement Object-Relational Mapping or datamapping techniques*

* [DBIx::Class](https://metacpan.org/pod/DBIx::Class)


## Package Management

*Libraries for package and dependency management*

* [App::cpanminus](https://metacpan.org/pod/App::cpanminus)
* [Carton](https://metacpan.org/pod/Carton)

## Processes and Threads

*Libraries for managing processes and threads*

* --

## Profiling

*Libraries for examining run-time activity of your program*

* [Devel::NYTProf](https://metacpan.org/pod/Devel::NYTProf) - Code profiler.

## Protocol

*Protocol clients and libraries*


* [HTTP::Tiny](https://metacpan.org/pod/HTTP::Tiny) - Minimal and fast client. Included in the standard packages.
* [LWP::UserAgent](https://metacpan.org/pod/LWP::UserAgent) - Popular HTTP(S) Client


## Queueing

*Message Queue, Job Queue System..*

* --

## Science/Numerics
*Hand-picked modules for research, science, numerics and hyper-computing*

* --

## Stream Manipulation

*Libraries for manipulating event streams*

* --

## REST Frameworks

*Libraries for developing REST applications*

* [Dancer2::Plugin::REST](https://metacpan.org/pod/Dancer2::Plugin::REST) - A plugin for writing RESTful apps with Dancer2


## Template Engines

*Libraries and tools for templating*

* [Template::Alloy](https://metacpan.org/pod/Template::Alloy) - TT2/3, HT, HTE, Tmpl, and Velocity Engine
* [Template::Toolkit](https://metacpan.org/pod/Template::Toolkit) - Very Popular Template Processing System
* [Text::Xslate](https://metacpan.org/pod/Text::Xslate) - Faster template engine with XS. Supports multiple syntaxes.

## Testing

*Libraries for testing codebases and generating test data.*

### Testing Frameworks

* [Test2::V0](https://metacpan.org/pod/Test2::V0) - My default testing lib, modern


### Coverage

* [Devel::Cover](https://metacpan.org/pod/Devel::Cover)
* [Devel::Cover::Report::Coveralls](https://metacpan.org/pod/Devel::Cover::Report::Coveralls) Report to Coveralls

## Tools

*Some useful tools*

* [Data::Printer](https://metacpan.org/pod/Data::Printer) - Colored pretty-print of Perl data structures and objects.
* [Smart::Comments](https://metacpan.org/pod/Smart::Comments) - Comments that do more than just sit there.

*Libraries for developping command line applications*

* --

*Libraries for handling configuration files*

* [Config::Tiny](https://metacpan.org/pod/Config::Tiny) - Read/Write .ini style files with as little code as possible


## Type checking

* [Type::Tiny](https://metacpan.org/pod/Type::Tiny) - Tiny, yet comprehensive type library

## Video

* --

## Web Frameworks

*Libraries for developing Web applications*

* [Dancer2](https://metacpan.org/pod/Dancer2) - My defacto framework
* [Catalyst](https://metacpan.org/pod/Catalyst) - Overflowing with features. Very popular.
* [Mojolicious](https://metacpan.org/pod/Mojolicious) - An all in one framework.

### Middlewares

*Libraries for creating HTTP middlewares*


* [Plack](https://metacpan.org/pod/Plack) - PSGI server implementation and utilities for Web applications.
* [Starman](https://metacpan.org/pod/Starman) - High-performance preforking PSGI/Plack web server


## Web Frameworks-Like

*Somewhere between templates and full on frameworks*

* --

## Web Scraping

*Libraries for extracting some information from websites*

* [WWW::Mechanize](https://metacpan.org/pod/WWW::Mechanize)


## Network Security

*Some great libraries for starting the world of Network security with Perl*


* --

## Metadata Forensics

*General Metadata files parser, usefull during forensics investigations*

* [Image::ExifTool](https://metacpan.org/pod/distribution/Image-ExifTool/exiftool) - General metadata parser and viewer framework

## Reverse Engineering

*Libraries used for disassembly assembly operations, ELF files and bytecode*

* --


# Other Awesome Lists

Other amazingly awesome lists can be found in:

* --

# How to contribute?

Please read [CONTRIBUTING.md](CONTRIBUTING.md)
