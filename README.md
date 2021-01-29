# LanceW's Awesome Perl [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome Perl resources, including frameworks, libraries and software. Inspired by [awesome-perl](https://github.com/hachiojipm/awesome-perl).

### Another module list

This is my list of Perl tools I like to use or think are good for use even if I am not actively using it. This is not going to have a huge list of modules; think of it as my own personal currated slice of CPAN.

I allso recommend checking out these lists.

* [Task::Kensho](https://github.com/EnlightenedPerlOrganisation/task-kensho "Task::Kensho")
* [awesome-perl](https://github.com/hachiojipm/awesome-perl)


### Contents


## Args

*Libraries for argument manifestation and validation.*


* [Params::Validate](https://metacpan.org/pod/Params::Validate) - Validate method/function parameters.


## Benchmarks

*Libraries for benchmarking*

* [Benchmark](https://metacpan.org/pod/Benchmark)


## Class Builder

*Libraries to support writing classes and meta programming*

* [Moo](https://metacpan.org/pod/Moo) - Great for light touch Moose.
* [Moose](https://metacpan.org/pod/Moose) - OOP defacto standard for when Moo is not enough.

## CLI

*Libraries for developing CLI applications*

* [Getopt::Long](https://metacpan.org/pod/Getopt::Long) - Extended processing of command line options.


## Container/IoC

*Libraries for containers/Inversion of Control

* [Bread::Board](https://metacpan.org/pod/Bread::Board)


## Database

*Libraries for dealing with relational databases*

* [DBI](https://metacpan.org/pod/DBI)

* [DBD::mysql](https://metacpan.org/pod/DBD::mysql)
* [DBD::Pg](https://metacpan.org/pod/DBD::Pg) - PostgreSQL driver for DBI.
* [DBD::SQLite](https://metacpan.org/pod/DBD::SQLite)


## Date & Time

*Libraries for working with dates and times*

* [DateTime](https://metacpan.org/pod/DateTime)
* [Time::Piece](https://metacpan.org/pod/Time::Piece)


## DevOps Tools

*Libraries that help when you want to deploy software across networks on several hosts/are working across computer networks*

* [Rex](https://metacpan.org/pod/Rex) - Remote Execution


* --

## Exception Handling

*Libraries that assist with and/or provide alternatives to eval{ die() }*

* [autodie](https://metacpan.org/pod/autodie) - Replace functions with ones that succeed or die with lexical scope
* [Try::Tiny](https://metacpan.org/pod/Try::Tiny) - minimal try/catch with proper preservation of $@


## Form Frameworks

*Libraries that take the boredom & repetition out of (web and UI) forms*

* [HTML::FormHandler](https://metacpan.org/pod/HTML::FormHandler) - HTML forms using Moose.


## List Manipulation

*Libraries for manipulation lists (arrays)*

* [List::MoreUtils](https://metacpan.org/pod/List::MoreUtils) - Provide the stuff missing in List::Util
* [List::Util](https://metacpan.org/pod/List::Util) - A selection of general-utility list subroutines


## Module Development

*Libraries that simplify and improve Perl module development*

* [Dist::Zilla](https://metacpan.org/pod/Dist::Zilla) - <http://dzil.org/>


## ORM

*Libraries that implement Object-Relational Mapping or datamapping techniques*

* [DBIx::Class](https://metacpan.org/pod/DBIx::Class)


## Package Management

*Libraries for package and dependency management*

* [App::cpanminus](https://metacpan.org/pod/App::cpanminus)
* [Carton](https://metacpan.org/pod/Carton)


## Profiling

*Libraries for examining run-time activity of your program*

* [Devel::NYTProf](https://metacpan.org/pod/Devel::NYTProf) - Code profiler.

## Protocol

*Protocol clients and libraries*


* [HTTP::Tiny](https://metacpan.org/pod/HTTP::Tiny) - Minimal and fast client. Included in the standard packages.
* [LWP::UserAgent](https://metacpan.org/pod/LWP::UserAgent) - Popular HTTP(S) Client



## REST Frameworks

*Libraries for developing REST applications*

* [Dancer2::Plugin::REST](https://metacpan.org/pod/Dancer2::Plugin::REST) - A plugin for writing RESTful apps with Dancer2


## Template Engines

*Libraries and tools for templating*

* [Template::Alloy](https://metacpan.org/pod/Template::Alloy) - TT2/3, HT, HTE, Tmpl, and Velocity Engine
* [Template::Toolkit](https://metacpan.org/pod/Template::Toolkit) - Very Popular Template Processing System

## Testing


* [Test2::V0](https://metacpan.org/pod/Test2::V0) - My default testing lib, modern


### Coverage

* [Devel::Cover](https://metacpan.org/pod/Devel::Cover)
* [Devel::Cover::Report::Coveralls](https://metacpan.org/pod/Devel::Cover::Report::Coveralls) Report to Coveralls

## Tools

*Some useful tools*

* [Data::Printer](https://metacpan.org/pod/Data::Printer) - Colored pretty-print of Perl data structures and objects.
* [Smart::Comments](https://metacpan.org/pod/Smart::Comments) - Comments that do more than just sit there.

*Libraries for handling configuration files*

* [Config::Tiny](https://metacpan.org/pod/Config::Tiny) - Read/Write .ini style files with as little code as possible


## Type checking

* [Type::Tiny](https://metacpan.org/pod/Type::Tiny) - Tiny, yet comprehensive type library


## Web Frameworks

*Libraries for developing Web applications*

* [Dancer2](https://metacpan.org/pod/Dancer2) - My defacto framework
* [Catalyst](https://metacpan.org/pod/Catalyst) - Overflowing with features. Very popular.
* [Mojolicious](https://metacpan.org/pod/Mojolicious) - An all in one framework.

### Middlewares


* [Plack](https://metacpan.org/pod/Plack) - PSGI server implementation and utilities for Web applications.
* [Starman](https://metacpan.org/pod/Starman) - High-performance preforking PSGI/Plack web server



## Web Scraping

*Libraries for extracting some information from websites*

* [WWW::Mechanize](https://metacpan.org/pod/WWW::Mechanize)


## Metadata Forensics

*General Metadata files parser, usefull during forensics investigations*

* [Image::ExifTool](https://metacpan.org/pod/distribution/Image-ExifTool/exiftool) - General metadata parser and viewer framework


