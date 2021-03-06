
# Type: isotope


A specific subtype of an atom with a specified neutron number

URI: [chemont:Isotope](https://w3id.org/chemont/Isotope)


![img](http://yuml.me/diagram/nofunky;dir:TB/class/[Isotope]<decay%20product%200..1-%20[Isotope&#124;neutron_number:count%20%3F;half_life:number_of_years%20%3F;decay_mode:string%20%3F;decay_energy:string%20%3F;mode_of_formation:string%20%3F;atomic_number(i):count%20%3F;symbol(pk)(i):string;name(i):string%20%3F;id(i):string],[Isotope]<isotope%20of%200..1-%20[Isotope],[Atom]^-[Isotope],[Atom])

## Parents

 *  is_a: [Atom](Atom.md) - A material entity consisting of exactly one atomic nucleus and the electron(s) orbiting it.

## Referenced by class

 *  **[Isotope](Isotope.md)** *[decay product](decay_product.md)*  <sub>OPT</sub>  **[Isotope](Isotope.md)**
 *  **[Isotope](Isotope.md)** *[isotone of](isotone_of.md)*  <sub>OPT</sub>  **[Isotope](Isotope.md)**
 *  **[Isotope](Isotope.md)** *[isotope of](isotope_of.md)*  <sub>OPT</sub>  **[Isotope](Isotope.md)**
 *  **[Isotope](Isotope.md)** *[nuclear isomer of](nuclear_isomer_of.md)*  <sub>OPT</sub>  **[Isotope](Isotope.md)**

## Attributes


### Own

 * [decay energy](decay_energy.md)  <sub>OPT</sub>
    * range: [String](types/String.md)
 * [decay mode](decay_mode.md)  <sub>OPT</sub>
    * range: [String](types/String.md)
 * [decay product](decay_product.md)  <sub>OPT</sub>
    * range: [Isotope](Isotope.md)
 * [half life](half_life.md)  <sub>OPT</sub>
    * range: [NumberOfYears](types/NumberOfYears.md)
 * [isotope of](isotope_of.md)  <sub>OPT</sub>
    * Description: relationship that holds between two isotopes, always holds if the isotopes have the same atomic number and a different neutron number.
    * range: [Isotope](Isotope.md)
 * [mode of formation](mode_of_formation.md)  <sub>OPT</sub>
    * range: [String](types/String.md)
 * [neutron number](neutron_number.md)  <sub>OPT</sub>
    * Description: number of neutrons in an atom
    * range: [Count](types/Count.md)

### Inherited from atom:

 * [atomic number](atomic_number.md)  <sub>OPT</sub>
    * Description: number of protons in an atom
    * range: [Count](types/Count.md)
 * [id](id.md)  <sub>REQ</sub>
    * range: [String](types/String.md)
 * [name](name.md)  <sub>OPT</sub>
    * Description: name of chemical entity. E.g. nickel, carbon-16
    * range: [String](types/String.md)
 * [symbol](symbol.md)  <sub>REQ</sub>
    * Description: short symbol for chemical entity, e.g. K, C-16
    * range: [String](types/String.md)

## Other properties

|  |  |  |
| --- | --- | --- |
| **Examples:** | | Example(value='1H (protium)', description=None) |
|  | | Example(value='2H (deuterium)', description=None) |
|  | | Example(value='https://en.wikipedia.org/wiki/Carbon-12', description=None) |

