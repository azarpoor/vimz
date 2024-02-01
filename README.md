# __VIMz__: Verifiable Image manipulation based on Zero-Knowledge Proofs
<p align="center">
  <img width="100%" src="cover.png" alt="Generated by AI (Freepik.com)">
  <em>Cover designed by <a href="https://www.freepik.com"> FreePik </a></em>
</p>



VIMz is currently (Dec. 2023) the fastest and most efficient program to proof authenticity of transformed/editted images w.r.t. an original source. It is built on top of [NOVA](https://github.com/microsoft/Nova) recursive zkSNARKs with the front-end of [Nova-Scotia](https://github.com/nalinbhardwaj/Nova-Scotia) (using [Circom](https://github.com/iden3/circom) language for defining internal circuits).
The protocol supports image resolutions of up to 4K (3840 x 2160) and higher.

## Acknowledgement
1. We thank [@iden3](https://github.com/iden3) for building the awesome [Circom](https://github.com/iden3/circom) language and proving the [CircomLib](https://github.com/iden3/circomlib).
2. This work currently heavily relies on [Nova-Scotia](https://github.com/nalinbhardwaj/Nova-Scotia)'s compiler for transforming Circom circuits to the ones comptible with [Nova](https://github.com/microsoft/Nova).
3. The very early version of the project (solely based on Circom without NOVA) got inspired by image transformation proofs from [@TrishaDatta](https://github.com/TrishaDatta)'s Circom circuits [repository](https://github.com/TrishaDatta/circom-circuits),<br>
which were related to the [medium post](https://medium.com/@boneh/using-zk-proofs-to-fight-disinformation-17e7d57fe52f) By Trisha Datta and Dan Boneh.

## License
<p xmlns:cc="http://creativecommons.org/ns#" >This work is licensed under <a href="http://creativecommons.org/licenses/by-nc/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Attribution-NonCommercial 4.0 International 
 <img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1"></a></p>
