DIN test options and results specification
==========================================

This repository contains specifications that are common to various implementations of the digit-in-noise test.
Implementations, whichever their programming language is, should implement the test parameters specified in 'options.txt',
and provide results in a format specified in 'results.txt'.

While a storing format has been chosen for results (JSON), the options can be stored in any native format that is adequate for
the language of the implementation. However, since the options are stored in the results structure, it needs to be converted
to JSON at that point.

To comment on the specifications, use the [Issues](https://github.com/dbSPLab/din-specification/issues) feature.

Contributors
------------

Etienne Gaudrain <etienne.gaudrain@cnrs.fr>

Thomas Koelewijn <t.koelewijn@rug.nl>

Soner Türüdü     <s.turudu@rug.nl>

Gloria Araiza-Illan <g.a.araiza.illan@rug.nl>

License
-------

DIN-SPECIFICATION (c) by CONTRIBUTORS

The work is this repository, DIN-SPECIFICATION is licensed under a
Creative Commons Attribution 4.0 International License.

You should have received a copy of the license along with this
work. If not, see <http://creativecommons.org/licenses/by/4.0/>.
