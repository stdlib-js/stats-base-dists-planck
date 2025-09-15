# CHANGELOG

> Package changelog.

<section class="release" id="unreleased">

## Unreleased (2025-09-15)

<section class="features">

### Features

-   [`5e3f0ad`](https://github.com/stdlib-js/stdlib/commit/5e3f0ad64fdac2a68ee1b1fcf88081bdc274d1e7) - add `planck` distribution namespace
-   [`0486735`](https://github.com/stdlib-js/stdlib/commit/0486735a3bd3a0f69d5940e7ff590afa18dcecd8) - add C implementation for `stats/base/dists/planck/cdf`
-   [`3253591`](https://github.com/stdlib-js/stdlib/commit/32535910933dcb61a8b0cb47ac76cc789aeff6e0) - add C implementation for `stats/base/dists/planck/logpmf`
-   [`11de1b0`](https://github.com/stdlib-js/stdlib/commit/11de1b04a61be7bad540053589639855d319b88f) - add C implementation for `stats/base/dists/planck/pmf`
-   [`5cc4546`](https://github.com/stdlib-js/stdlib/commit/5cc454641d97c66cf6ff75eb02a99086a65b7848) - add C implementation for `stats/base/dists/planck/mode` [(#4911)](https://github.com/stdlib-js/stdlib/pull/4911)
-   [`2b0a046`](https://github.com/stdlib-js/stdlib/commit/2b0a046b6c94af24039a72419b9577117459a1c4) - add C implementation for `stats/base/dists/planck/kurtosis`
-   [`91ac343`](https://github.com/stdlib-js/stdlib/commit/91ac343103b2c6f65a7fe76e95df32d08e01ae02) - add C implementation for `stats/base/dists/planck/quantile`
-   [`8987e23`](https://github.com/stdlib-js/stdlib/commit/8987e23a05d1df2d7b062a2211394142dc3853b9) - add C implementation for `stats/base/dists/planck/skewness`
-   [`2e1fd00`](https://github.com/stdlib-js/stdlib/commit/2e1fd00ef18ea2d3306e2196856c5076003071a2) - add C implementation for `stats/base/dists/planck/variance`
-   [`340a147`](https://github.com/stdlib-js/stdlib/commit/340a147293f2fb18db097491154b83671c44bdd3) - add C implementation for `@stdlib/stats-base/dists/planck/logcdf` [(#4936)](https://github.com/stdlib-js/stdlib/pull/4936)
-   [`612a602`](https://github.com/stdlib-js/stdlib/commit/612a602ee7110d2d303282969975e99892004989) - add C implementation for `stats/base/dists/planck/mgf` [(#4945)](https://github.com/stdlib-js/stdlib/pull/4945)
-   [`8ba53a1`](https://github.com/stdlib-js/stdlib/commit/8ba53a198106852057d9444fb684818e8e7dfcc5) - add C implementation for `stats/base/dists/planck/mean` [(#4902)](https://github.com/stdlib-js/stdlib/pull/4902)
-   [`5470254`](https://github.com/stdlib-js/stdlib/commit/54702546fc9b57bfb6aa7a5bd1404e45e1d8ed5f) - add C implementation for `stats/base/dists/planck/entropy` [(#4898)](https://github.com/stdlib-js/stdlib/pull/4898)
-   [`fb90f93`](https://github.com/stdlib-js/stdlib/commit/fb90f93faa07ef30d622a721192453e9acdc1087) - add C implementation for `stats/base/dists/planck/median` [(#4938)](https://github.com/stdlib-js/stdlib/pull/4938)
-   [`120e678`](https://github.com/stdlib-js/stdlib/commit/120e678549e87a742a33ef2d3574c88ab0f95b26) - add C implementation for `stats/base/dists/planck/stdev` [(#4913)](https://github.com/stdlib-js/stdlib/pull/4913)
-   [`5444ad4`](https://github.com/stdlib-js/stdlib/commit/5444ad47eef627b88d14c4e260e14051ffe301fe) - add `stats/base/dists/planck/mgf` [(#4478)](https://github.com/stdlib-js/stdlib/pull/4478)
-   [`5524db1`](https://github.com/stdlib-js/stdlib/commit/5524db160ac2122196d06d9b3d3fbbfc841409c1) - add `stats/base/dists/planck/quantile` [(#4392)](https://github.com/stdlib-js/stdlib/pull/4392)
-   [`34b3c31`](https://github.com/stdlib-js/stdlib/commit/34b3c31428dfa3911fcf3ed5ba73b6ba6ddd83de) - add `stats/base/dists/planck/entropy` [(#4325)](https://github.com/stdlib-js/stdlib/pull/4325)
-   [`094bea4`](https://github.com/stdlib-js/stdlib/commit/094bea4813d0bcbe184fe8d2be95b97b1ff3b045) - add `stats/base/dists/planck/logpmf` [(#4182)](https://github.com/stdlib-js/stdlib/pull/4182)
-   [`7d285da`](https://github.com/stdlib-js/stdlib/commit/7d285da1e7214bbccf226cc56645c6c6520072cf) - add `stats/base/dists/planck/mode` [(#4350)](https://github.com/stdlib-js/stdlib/pull/4350)
-   [`b8b2e44`](https://github.com/stdlib-js/stdlib/commit/b8b2e44b61f388af7257000657111d693f8d32ee) - add `stats/base/dists/planck/kurtosis` [(#4355)](https://github.com/stdlib-js/stdlib/pull/4355)
-   [`c41e8a2`](https://github.com/stdlib-js/stdlib/commit/c41e8a215f55a1d01843e954f0b0de34909acf94) - add `stats/base/dists/planck/skewness` [(#4353)](https://github.com/stdlib-js/stdlib/pull/4353)
-   [`e982d25`](https://github.com/stdlib-js/stdlib/commit/e982d2541929447a454214fa81bd3d9556f36b8d) - add `stats/base/dists/planck/median` [(#4346)](https://github.com/stdlib-js/stdlib/pull/4346)
-   [`baf8692`](https://github.com/stdlib-js/stdlib/commit/baf8692a1cc1eb70acd0c17a9e45bf06c315c5d6) - add `stats/base/dists/planck/logcdf` [(#4227)](https://github.com/stdlib-js/stdlib/pull/4227)
-   [`4cf8ad7`](https://github.com/stdlib-js/stdlib/commit/4cf8ad7f9820ff00bb61360b83d75c295da8f656) - add `stats/base/dists/planck/cdf` [(#4130)](https://github.com/stdlib-js/stdlib/pull/4130)
-   [`d16409a`](https://github.com/stdlib-js/stdlib/commit/d16409aa8fc9dca64365d5a66b50b1e01dc32f5d) - add `stats/base/dists/planck/pmf` [(#3896)](https://github.com/stdlib-js/stdlib/pull/3896)
-   [`d43f119`](https://github.com/stdlib-js/stdlib/commit/d43f119c8619f0683bcb5baadca812cbc0cfd406) - add `stats/base/dists/planck/stdev` [(#4127)](https://github.com/stdlib-js/stdlib/pull/4127)
-   [`8aff8f8`](https://github.com/stdlib-js/stdlib/commit/8aff8f8ded98f6cf3ee869208f999af9fdb25b0d) - add `stats/base/dists/planck/variance` [(#4102)](https://github.com/stdlib-js/stdlib/pull/4102)
-   [`56801e8`](https://github.com/stdlib-js/stdlib/commit/56801e8c64bc227a69e9b9b811d74994f2ad88a1) - add `stats/base/dists/planck/mean` [(#3942)](https://github.com/stdlib-js/stdlib/pull/3942)

</section>

<!-- /.features -->

<section class="bug-fixes">

### Bug Fixes

-   [`2a0ea7f`](https://github.com/stdlib-js/stdlib/commit/2a0ea7feb22806685fef9eac8a32d7012dab7adc) - use correct package names in package.json

</section>

<!-- /.bug-fixes -->

<section class="issues">

### Closed Issues

A total of 17 issues were closed in this release:

[#4883](https://github.com/stdlib-js/stdlib/issues/4883), [#4897](https://github.com/stdlib-js/stdlib/issues/4897), [#4899](https://github.com/stdlib-js/stdlib/issues/4899), [#4901](https://github.com/stdlib-js/stdlib/issues/4901), [#4905](https://github.com/stdlib-js/stdlib/issues/4905), [#4907](https://github.com/stdlib-js/stdlib/issues/4907), [#4910](https://github.com/stdlib-js/stdlib/issues/4910), [#4912](https://github.com/stdlib-js/stdlib/issues/4912), [#4935](https://github.com/stdlib-js/stdlib/issues/4935), [#4937](https://github.com/stdlib-js/stdlib/issues/4937), [#4944](https://github.com/stdlib-js/stdlib/issues/4944), [#4996](https://github.com/stdlib-js/stdlib/issues/4996), [#5000](https://github.com/stdlib-js/stdlib/issues/5000), [#5228](https://github.com/stdlib-js/stdlib/issues/5228), [#5229](https://github.com/stdlib-js/stdlib/issues/5229), [#5711](https://github.com/stdlib-js/stdlib/issues/5711), [#7427](https://github.com/stdlib-js/stdlib/issues/7427)

</section>

<!-- /.issues -->

<section class="commits">

### Commits

<details>

-   [`e2efe32`](https://github.com/stdlib-js/stdlib/commit/e2efe32914d0d9dae5da34e6f7e7bf7655430710) - **chore:** rename exported variable in d.ts file to match name used in example code _(by Philipp Burckhardt)_
-   [`a7ee897`](https://github.com/stdlib-js/stdlib/commit/a7ee897ffbec2a6a758563fd68277591352f22a8) - **docs:** encode Markdown stdlib package URLs [(#7933)](https://github.com/stdlib-js/stdlib/pull/7933) _(by stdlib-bot)_
-   [`5e3f0ad`](https://github.com/stdlib-js/stdlib/commit/5e3f0ad64fdac2a68ee1b1fcf88081bdc274d1e7) - **feat:** add `planck` distribution namespace _(by Philipp Burckhardt)_
-   [`4589cee`](https://github.com/stdlib-js/stdlib/commit/4589cee4e69b2a4c4a433321f413824a69eebb6e) - **docs:** fix return annotation values _(by Philipp Burckhardt)_
-   [`7add020`](https://github.com/stdlib-js/stdlib/commit/7add0201c13e56a0381926ccfd4073c84eaf2ed4) - **test:** use standardized assertion messages and fix lint errors _(by Philipp Burckhardt)_
-   [`fc438e0`](https://github.com/stdlib-js/stdlib/commit/fc438e0edbad0689d6923d6f3edb959b96597662) - **test:** use standardized assertion messages and fix lint errors _(by Philipp Burckhardt)_
-   [`07f7c05`](https://github.com/stdlib-js/stdlib/commit/07f7c0522c73e6ad9505e1d45035ae439344200d) - **test:** use standardized assertion messages and fix lint errors _(by Philipp Burckhardt)_
-   [`9c21fd2`](https://github.com/stdlib-js/stdlib/commit/9c21fd20ef8b8a6a88abb96d80ea6d8e4c5434eb) - **test:** use .strictEqual() instead of .equal() _(by Philipp Burckhardt)_
-   [`2a0ea7f`](https://github.com/stdlib-js/stdlib/commit/2a0ea7feb22806685fef9eac8a32d7012dab7adc) - **fix:** use correct package names in package.json _(by Philipp Burckhardt)_
-   [`8ea46b6`](https://github.com/stdlib-js/stdlib/commit/8ea46b662dc6e27231d250d101e33a3cf770cd77) - **test:** update descriptions to match language used in JS tests _(by Philipp Burckhardt)_
-   [`bb5b8f3`](https://github.com/stdlib-js/stdlib/commit/bb5b8f37a23d60d6ed7ed8d4af77e8e80d4fcde7) - **docs:** update `stats/base/dists/planck` examples to use Greek symbols _(by Philipp Burckhardt)_
-   [`99d605d`](https://github.com/stdlib-js/stdlib/commit/99d605d037b740cc5565e8d7bb119b5ff4840619) - **bench:** clean-up _(by Athan Reines)_
-   [`7120de1`](https://github.com/stdlib-js/stdlib/commit/7120de1b6484dd69bc0fd1e3cdc2ffe5d2635a8e) - **docs:** use consistent types _(by Athan Reines)_
-   [`241e5de`](https://github.com/stdlib-js/stdlib/commit/241e5de5107bafc5a9bdd478ce1660bf4080d106) - **docs:** use consistent types _(by Athan Reines)_
-   [`cb4a038`](https://github.com/stdlib-js/stdlib/commit/cb4a0383c7148d36b9bce721d6a324a009638f99) - **chore:** use consistent decimals and types _(by Athan Reines)_
-   [`a477ce3`](https://github.com/stdlib-js/stdlib/commit/a477ce3c13373fb141f025c43b5001cb23f18258) - **chore:** ensure consistent use of decimals _(by Athan Reines)_
-   [`18a1bcc`](https://github.com/stdlib-js/stdlib/commit/18a1bcc97735d26b415f7fa0f477d9340492c2cd) - **chore:** remove excess trailing whitespace _(by Athan Reines)_
-   [`f32a0ed`](https://github.com/stdlib-js/stdlib/commit/f32a0ed051dddc4c29baa473fdc386e8654e33e6) - **chore:** clean-up _(by Athan Reines)_
-   [`d0030d8`](https://github.com/stdlib-js/stdlib/commit/d0030d8f59684cfaa23353ff661fd49b790af9bd) - **chore:** add decimals _(by Athan Reines)_
-   [`07a3861`](https://github.com/stdlib-js/stdlib/commit/07a3861a1d7b396fd95d93089cc135a323fb22fd) - **style:** remove blank line _(by Athan Reines)_
-   [`d877d7c`](https://github.com/stdlib-js/stdlib/commit/d877d7c18f238623b2ad310ee3dcb361059d3fe5) - **style:** remove blank lines _(by Athan Reines)_
-   [`0486735`](https://github.com/stdlib-js/stdlib/commit/0486735a3bd3a0f69d5940e7ff590afa18dcecd8) - **feat:** add C implementation for `stats/base/dists/planck/cdf` _(by Philipp Burckhardt)_
-   [`3253591`](https://github.com/stdlib-js/stdlib/commit/32535910933dcb61a8b0cb47ac76cc789aeff6e0) - **feat:** add C implementation for `stats/base/dists/planck/logpmf` _(by Philipp Burckhardt)_
-   [`11de1b0`](https://github.com/stdlib-js/stdlib/commit/11de1b04a61be7bad540053589639855d319b88f) - **feat:** add C implementation for `stats/base/dists/planck/pmf` _(by Philipp Burckhardt)_
-   [`5cc4546`](https://github.com/stdlib-js/stdlib/commit/5cc454641d97c66cf6ff75eb02a99086a65b7848) - **feat:** add C implementation for `stats/base/dists/planck/mode` [(#4911)](https://github.com/stdlib-js/stdlib/pull/4911) _(by Yuvi Mittal, Philipp Burckhardt, stdlib-bot)_
-   [`2b0a046`](https://github.com/stdlib-js/stdlib/commit/2b0a046b6c94af24039a72419b9577117459a1c4) - **feat:** add C implementation for `stats/base/dists/planck/kurtosis` _(by Philipp Burckhardt)_
-   [`91ac343`](https://github.com/stdlib-js/stdlib/commit/91ac343103b2c6f65a7fe76e95df32d08e01ae02) - **feat:** add C implementation for `stats/base/dists/planck/quantile` _(by Philipp Burckhardt)_
-   [`8987e23`](https://github.com/stdlib-js/stdlib/commit/8987e23a05d1df2d7b062a2211394142dc3853b9) - **feat:** add C implementation for `stats/base/dists/planck/skewness` _(by Philipp Burckhardt)_
-   [`2e1fd00`](https://github.com/stdlib-js/stdlib/commit/2e1fd00ef18ea2d3306e2196856c5076003071a2) - **feat:** add C implementation for `stats/base/dists/planck/variance` _(by Philipp Burckhardt)_
-   [`484bc07`](https://github.com/stdlib-js/stdlib/commit/484bc07d6974d904855666b30728d618b2261e03) - **chore:** address commit comments for commit `340a147` [(#7434)](https://github.com/stdlib-js/stdlib/pull/7434) _(by Lokesh Ranjan)_
-   [`e4d9557`](https://github.com/stdlib-js/stdlib/commit/e4d955774c09a9e1139396fd69e0913951755302) - **chore:** clean-up _(by Athan Reines)_
-   [`340a147`](https://github.com/stdlib-js/stdlib/commit/340a147293f2fb18db097491154b83671c44bdd3) - **feat:** add C implementation for `@stdlib/stats-base/dists/planck/logcdf` [(#4936)](https://github.com/stdlib-js/stdlib/pull/4936) _(by Yuvi Mittal, Philipp Burckhardt, stdlib-bot)_
-   [`9c8bff8`](https://github.com/stdlib-js/stdlib/commit/9c8bff8a85818c74169190784a3cbd43dd53be67) - **chore:** clean-up _(by Athan Reines)_
-   [`612a602`](https://github.com/stdlib-js/stdlib/commit/612a602ee7110d2d303282969975e99892004989) - **feat:** add C implementation for `stats/base/dists/planck/mgf` [(#4945)](https://github.com/stdlib-js/stdlib/pull/4945) _(by Yuvi Mittal, Philipp Burckhardt, stdlib-bot)_
-   [`197a69a`](https://github.com/stdlib-js/stdlib/commit/197a69a212649e53bece59d70ae840b9acb08bea) - **chore:** clean-up _(by Athan Reines)_
-   [`8ba53a1`](https://github.com/stdlib-js/stdlib/commit/8ba53a198106852057d9444fb684818e8e7dfcc5) - **feat:** add C implementation for `stats/base/dists/planck/mean` [(#4902)](https://github.com/stdlib-js/stdlib/pull/4902) _(by Yuvi Mittal, Philipp Burckhardt)_
-   [`a1e230f`](https://github.com/stdlib-js/stdlib/commit/a1e230f29297caa89880e9c194c615a0400fb7bc) - **chore:** clean up cppcheck-suppress comments _(by Karan Anand)_
-   [`78ab146`](https://github.com/stdlib-js/stdlib/commit/78ab146ecf23ca916bb4c171312c02448798351f) - **chore:** address commit comment [(#5728)](https://github.com/stdlib-js/stdlib/pull/5728) _(by Jalaj Kumar)_
-   [`5470254`](https://github.com/stdlib-js/stdlib/commit/54702546fc9b57bfb6aa7a5bd1404e45e1d8ed5f) - **feat:** add C implementation for `stats/base/dists/planck/entropy` [(#4898)](https://github.com/stdlib-js/stdlib/pull/4898) _(by Yuvi Mittal, Philipp Burckhardt)_
-   [`7e8f02d`](https://github.com/stdlib-js/stdlib/commit/7e8f02ddf2771907ff71fc79b56e165c62c69bd6) - **docs:** update related packages sections [(#5434)](https://github.com/stdlib-js/stdlib/pull/5434) _(by stdlib-bot)_
-   [`576bd4b`](https://github.com/stdlib-js/stdlib/commit/576bd4b6bb45c0580dbb386d6b347cbb45145806) - **bench:** revert uniform implementation and remove unnecessary loop [(#5314)](https://github.com/stdlib-js/stdlib/pull/5314) _(by Abhishek Jain, Philipp Burckhardt)_
-   [`eecbeee`](https://github.com/stdlib-js/stdlib/commit/eecbeeec6f265ce248fd131a29e89362eacc727d) - **chore:** address commit comments [(#5283)](https://github.com/stdlib-js/stdlib/pull/5283) _(by Rishav Tarway)_
-   [`fb90f93`](https://github.com/stdlib-js/stdlib/commit/fb90f93faa07ef30d622a721192453e9acdc1087) - **feat:** add C implementation for `stats/base/dists/planck/median` [(#4938)](https://github.com/stdlib-js/stdlib/pull/4938) _(by Yuvi Mittal, Philipp Burckhardt, stdlib-bot)_
-   [`120e678`](https://github.com/stdlib-js/stdlib/commit/120e678549e87a742a33ef2d3574c88ab0f95b26) - **feat:** add C implementation for `stats/base/dists/planck/stdev` [(#4913)](https://github.com/stdlib-js/stdlib/pull/4913) _(by Yuvi Mittal, Philipp Burckhardt)_
-   [`177f0a0`](https://github.com/stdlib-js/stdlib/commit/177f0a00909c097be05d47107a3e6ab05b865409) - **chore:** consistently use differential entropy for continuous distributions _(by Philipp Burckhardt)_
-   [`f75a0ce`](https://github.com/stdlib-js/stdlib/commit/f75a0cef6a3112b166dba04c13bada9763cec350) - **chore:** use excess kurtosis consistently _(by Philipp Burckhardt)_
-   [`5444ad4`](https://github.com/stdlib-js/stdlib/commit/5444ad47eef627b88d14c4e260e14051ffe301fe) - **feat:** add `stats/base/dists/planck/mgf` [(#4478)](https://github.com/stdlib-js/stdlib/pull/4478) _(by Jaysukh Makvana, Athan Reines)_
-   [`5524db1`](https://github.com/stdlib-js/stdlib/commit/5524db160ac2122196d06d9b3d3fbbfc841409c1) - **feat:** add `stats/base/dists/planck/quantile` [(#4392)](https://github.com/stdlib-js/stdlib/pull/4392) _(by Jaysukh Makvana, Athan Reines, stdlib-bot)_
-   [`34b3c31`](https://github.com/stdlib-js/stdlib/commit/34b3c31428dfa3911fcf3ed5ba73b6ba6ddd83de) - **feat:** add `stats/base/dists/planck/entropy` [(#4325)](https://github.com/stdlib-js/stdlib/pull/4325) _(by Jaysukh Makvana, Athan Reines, stdlib-bot)_
-   [`094bea4`](https://github.com/stdlib-js/stdlib/commit/094bea4813d0bcbe184fe8d2be95b97b1ff3b045) - **feat:** add `stats/base/dists/planck/logpmf` [(#4182)](https://github.com/stdlib-js/stdlib/pull/4182) _(by Jaysukh Makvana, Athan Reines, stdlib-bot)_
-   [`7d285da`](https://github.com/stdlib-js/stdlib/commit/7d285da1e7214bbccf226cc56645c6c6520072cf) - **feat:** add `stats/base/dists/planck/mode` [(#4350)](https://github.com/stdlib-js/stdlib/pull/4350) _(by Jaysukh Makvana, Athan Reines, stdlib-bot)_
-   [`b8b2e44`](https://github.com/stdlib-js/stdlib/commit/b8b2e44b61f388af7257000657111d693f8d32ee) - **feat:** add `stats/base/dists/planck/kurtosis` [(#4355)](https://github.com/stdlib-js/stdlib/pull/4355) _(by Jaysukh Makvana, Athan Reines, stdlib-bot)_
-   [`c41e8a2`](https://github.com/stdlib-js/stdlib/commit/c41e8a215f55a1d01843e954f0b0de34909acf94) - **feat:** add `stats/base/dists/planck/skewness` [(#4353)](https://github.com/stdlib-js/stdlib/pull/4353) _(by Jaysukh Makvana, Athan Reines, stdlib-bot)_
-   [`e982d25`](https://github.com/stdlib-js/stdlib/commit/e982d2541929447a454214fa81bd3d9556f36b8d) - **feat:** add `stats/base/dists/planck/median` [(#4346)](https://github.com/stdlib-js/stdlib/pull/4346) _(by Jaysukh Makvana, Athan Reines, stdlib-bot)_
-   [`054f4e5`](https://github.com/stdlib-js/stdlib/commit/054f4e520735bc1ad59e0f608bb588430463e913) - **docs:** fix descriptions _(by Athan Reines)_
-   [`baf8692`](https://github.com/stdlib-js/stdlib/commit/baf8692a1cc1eb70acd0c17a9e45bf06c315c5d6) - **feat:** add `stats/base/dists/planck/logcdf` [(#4227)](https://github.com/stdlib-js/stdlib/pull/4227) _(by Jaysukh Makvana, Athan Reines, stdlib-bot)_
-   [`4cf8ad7`](https://github.com/stdlib-js/stdlib/commit/4cf8ad7f9820ff00bb61360b83d75c295da8f656) - **feat:** add `stats/base/dists/planck/cdf` [(#4130)](https://github.com/stdlib-js/stdlib/pull/4130) _(by Jaysukh Makvana, Athan Reines)_
-   [`d16409a`](https://github.com/stdlib-js/stdlib/commit/d16409aa8fc9dca64365d5a66b50b1e01dc32f5d) - **feat:** add `stats/base/dists/planck/pmf` [(#3896)](https://github.com/stdlib-js/stdlib/pull/3896) _(by Jaysukh Makvana, Athan Reines, stdlib-bot)_
-   [`d43f119`](https://github.com/stdlib-js/stdlib/commit/d43f119c8619f0683bcb5baadca812cbc0cfd406) - **feat:** add `stats/base/dists/planck/stdev` [(#4127)](https://github.com/stdlib-js/stdlib/pull/4127) _(by Jaysukh Makvana, Athan Reines)_
-   [`8aff8f8`](https://github.com/stdlib-js/stdlib/commit/8aff8f8ded98f6cf3ee869208f999af9fdb25b0d) - **feat:** add `stats/base/dists/planck/variance` [(#4102)](https://github.com/stdlib-js/stdlib/pull/4102) _(by Jaysukh Makvana, Athan Reines)_
-   [`56801e8`](https://github.com/stdlib-js/stdlib/commit/56801e8c64bc227a69e9b9b811d74994f2ad88a1) - **feat:** add `stats/base/dists/planck/mean` [(#3942)](https://github.com/stdlib-js/stdlib/pull/3942) _(by Jaysukh Makvana, Athan Reines, stdlib-bot)_

</details>

</section>

<!-- /.commits -->

<section class="contributors">

### Contributors

A total of 9 people contributed to this release. Thank you to the following contributors:

-   Abhishek Jain
-   Athan Reines
-   Jalaj Kumar
-   Jaysukh Makvana
-   Karan Anand
-   Lokesh Ranjan
-   Philipp Burckhardt
-   Rishav Tarway
-   Yuvi Mittal

</section>

<!-- /.contributors -->

</section>

<!-- /.release -->

