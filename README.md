# FreemoVR - Virtual Reality for Freely Moving Animals

FreemoVR is a system for creating virtual reality for freely moving animals.

The principle of operation is that a realtime animal tracker provides
near-instantaneous 3D animal position data to a realtime rendering engine, which
draws perspective-correct visual stimuli for the animal on the walls using
calibrated computer displays.

"FreemoVR" itself refers to a system of several components. The [FreemoVR
engine](https://github.com/strawlab/freemovr_engine) draws the visual stimuli,
and can use different tracking systems to provide position input. The system was
originally developed to use [flydra](https://github.com/strawlab/flydra) as the
source of 3D position input.

This repository hold information relevant to the entire system rather than about
any specific part. Most of the source code will be in the individual code
repositories, but it makes sense to have a top-level repository for
documentation and issues related to the combined system.

## Discussion

For questions or discussion, please use [the "freemovr" Google
Group](https://groups.google.com/forum/#!forum/freemovr).

## Publication

FreemoVR is described in the following paper:

Stowers JR*, Hofbauer M*, Bastien R, Griessner J⁑, Higgins P⁑, Farooqui S⁑,
Fischer RM, Nowikovsky K, Haubensak W, Couzin ID, Tessmar-Raible K✎, Straw AD✎.
Virtual Reality for Freely Moving Animals. Nature Methods (2017)
[doi:10.1038/nmeth.4399](https://dx.doi.org/10.1038/nmeth.4399).

Please cite this if you use FreemoVR.

## License

The software, documentation and other resouces are licensed under either of

* Apache License, Version 2.0,
  (./LICENSE-APACHE or http://www.apache.org/licenses/LICENSE-2.0)
* MIT license (./LICENSE-MIT or http://opensource.org/licenses/MIT)
  at your option.

## Contribution

Unless you explicitly state otherwise, any contribution intentionally
submitted for inclusion in the work by you, as defined in the Apache-2.0
license, shall be dual licensed as above, without any additional terms or
conditions.

## Code of conduct

Anyone who interacts with bui-backend in any space including but not
limited to this GitHub repository is expected to follow our [code of
conduct](https://github.com/strawlab/flydra/blob/master/code_of_conduct.md).
