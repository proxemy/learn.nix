# learn.nix

A per-package collection of small question and solution about nix objects.  
It's primary goal is to archive my learning curve, later, it could become a
resource.

## Usage

TODO

`nix repl learn.nix`

### Preparation

* [Install nix](https://nixos.org/download.html).  
  You should be able to successfully run the following commands.  
  ```bash
  # both tools should report at least something
  nix --version
  nix-channel --list

  # a simple derivation should be build and executed
  nix shell nixpkgs#hello -c hello
  ```

* [Learn nix the language.](https://nixos.org/guides/nix-pills/basics-of-language.html)  
  To interact with the guides herein, it is important, that you have at least
  a vague feeling of nix. Language specifics are not the primary goal of these
  guides.  
  Learning the
  [language primitives](https://learnxinyminutes.com/docs/nix/)
  is up to you but it's not that much anyway.

## Contribution

TODO
