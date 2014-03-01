# Splitting Atoms

a community-built guide to hacking on the [Atom](https://atom.io) editor

> A hackable text editor for the 21st Century

> At GitHub, we're building the text editor we've always wanted. A tool you
> can customize to do anything, but also use productively on the first day
> without ever touching a config file. Atom is modern, approachable, and
> hackable to the core. We can't wait to see what you build with it.

To find out more about Atom from the team itself, read
[Introducing Atom](http://blog.atom.io/2014/02/26/introducing-atom.html) and
[The Nucleus of Atom](http://blog.atom.io/2014/02/26/the-nucleus-of-atom.html).

## Contributing to Splitting Atoms

There are a number of ways to contribute to this project:

- What are the sections, topics, and guides that are missing? There should
still be lots of them, so open up some issues and send pull requests!

- If you are excited about Atom and have already started digging into it and
hacking on it, then you are just the person we need to contribute to this
community-built, community-driven guide. Write about your experience tinkering
with part of Atom and help refine and clarify what is already written here.
Send pull requests and open issues.

- If something about Atom completely perplexes you or you find parts of the
official Atom documentation that are completely lacking, open an issue so that
we can look into it and address it in the guide.

- Create a badass Splitting Atom logo that can eventually be displayed in our
README, on our website, and in an eBook.

## Getting Started

You can start by going through
[the official Atom documentation](https://atom.io/docs) which contains a
handful of helpful guides for creating packages and themes as well as
advanced topics such as configuring your environment.

Check out the [Atom API](http://atom.io/docs/api) for more detailed
documentation on the APIs that are available to those developing packages or
hacking on existing ones.

## Packages

### Installing Packages

There are two main approaches to installing packages. You can easily do it
from inside Atom from the Package management tab in settings. For those still
inclined to using the command-line, the Atom Package Manager binary, `apm`, can
also be used to install packages as well.

#### Installing from Atom



#### Installing with apm


### Searching for Packages


### Managing Packages

Atom gives you insight into the load-time that each package is adding to the
overall performance of the editor. Based on this information, you can browse
your packages enabling and disabling them as you see fit.

#### Where are packages stored?

All the Atom configuration files, styles, packages, etc. are stored in an
Atom dot directory, namely `~/.atom`. Inside that directory, you can find
another directory named `packages` which contains all of your packages. For
those that have used NPM or Bower, it is similar to your `node_components` or
`bower_components` directories.

### Uninstalling Packages


## Splitting Atoms' Goals

- Develop supplementary guides, documentation, and tutorials for Atom
- Organize the guides, documentation, and tutorials into an Atom developers
  guide
- Publish the Atom developers guide as a website
- Publish the Atom developers guide as a PDF/eBook

## License

Everything here is licensed under the MIT license.
