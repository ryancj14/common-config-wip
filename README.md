# common-config

This is a preparatory repository for the creation of Symbiflow's common-config repo.

---

Symbiflow aims to produce a completely open source FPGA design toolchain.  They have a large presence on github where they have many repositories (73 to be exact), where each repository roughly corresponds to one project.  One of the challenges is with such a large effort is imposing some order and uniformity on the various repositories so that they all use the same code formatting, copyright licensing, documentation style, etc.  One of the open issues they have relates to creating a single common configuration github repository which is then included into every other repository to provide the desired uniformity.  This project focuses on creating such a common configuration repository and modifying all other repositories to use it.

To learn more, see [Issue 51](https://github.com/SymbiFlow/ideas/issues/51) on the Symbiflow Ideas repository.

---

This repository will hold the following items:

* [ ] Stuff around style formatting including;
  * [ ] `.editorconfig` file 
    * [ ] Fully implemented
  * [x] Copyright / license
    * [ ] Fully implemented
  * [ ]  Auto-formatting tools - `clang-format`, `yapf`, `verible`, `mjson`
    * [ ] Fully implemented
* [ ] Documentation around policies
  * [x] Code of conduct
    * [ ] Fully implemented
  * [x] Contribution guide
    * [ ] Fully implemented
  * [ ] Issue Templates
    * [ ] Fully implemented
  * [ ] Pull Request Templates
    * [ ] Fully implemented
  * [ ] Common replies to things like missing DCO and stuff
    * [ ] Fully Implemented
  * [ ] etc
* [ ] Documentation building and publishing scripts
  * [ ] The Sphinx documentation generation
    * [ ] Fully Implemented
  * [ ] ReadTheDocs publishing
    * [ ] Fully Implemented
* [ ] Useful infrastructure / CI scripts
  * [ ] Tools for handling the complexity of git submodules
    * [ ] Fully Implemented
  * [x] Tools for getting and setting up environments using conda (handled by make-env)
  * [ ] etc

Full implementation includes setting up github actions to check them and bots to merge them into projects where this is a submodule.
