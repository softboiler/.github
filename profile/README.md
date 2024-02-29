I am gradually working towards migrating my dissertation projects, which facilitate the study of nucleate pool boiling, into this organization.

- [`boilercv`](https://github.com/blakeNaccarato/boilercv): Computer vision routines suitable for nucleate pool boiling bubble analysis.
- [`boilerdata`](https://github.com/blakeNaccarato/boilerdata): Data processing pipeline for a nucleate pool boiling apparatus.
- [`boilerdaq`](https://github.com/blakeNaccarato/boilerdaq): Data acquisition for a nucleate pool boiling experiment.
- [`boilercore`](https://github.com/blakeNaccarato/boilercore): Code shared among the above libraries. Things migrated here are candidates for splitting out into their own utility libraries, which may be generally useful for other researchers. For instance, `captivate` facilitates video and image viewing.
- [`boilercine`](https://github.com/blakeNaccarato/boilercine): A stopgap library for reading CINE files into the [`boilercv`](https://github.com/blakeNaccarato/boilercv) pipeline. Will probably migrate to `pims`, time permitting.
- [`copier-python`](https://github.com/blakeNaccarato/copier-python): A general-purpose Python project template. I intend to clone this template into `softboiler`, de-coupling my research-specific template features from the more general-purpose features.
- [`copier-python-workflow-setup`](https://github.com/blakeNaccarato/copier-python-workflow-setup): GitHub Actions workflows for projects generated from the above template. I will clone this as well and specialize around the projects in `softboiler`.

Another goal of this organization's website is to aggregate and highlight other thermal science research software in the field, with a focus on open-source and projects that follow the FAIR Guiding Principles. Such projects focus on improving the **F**indability, **A**ccessibility, **I**nteroperability, and **R**euse of their data, methods, and research.
