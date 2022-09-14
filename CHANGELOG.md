#### 4.3.49 (2022-09-14)

#### 4.3.48 (2022-09-14)

#### 4.3.47 (2022-09-14)

#### 4.3.46 (2022-09-14)

#### 4.3.45 (2022-09-14)

##### Breaking Changes

- rename `onDoubleRowClick` to `onRowDoubleClick` ([32a7f3ac](https://github.com/material-table-core/core/commit/32a7f3ac5f371d3e349e1d2790f325efaa3b3a48))

##### Chores

- use @hello-pangea/dnd ([#608](https://github.com/material-table-core/core/pull/608)) ([e89f4bb8](https://github.com/material-table-core/core/commit/e89f4bb89e62c22cb72c1f20d4593ebede2d4662))
- update package.lock ([d724c7ef](https://github.com/material-table-core/core/commit/d724c7ef6f5daffa8bdbe94749a9215f1b4902b9))
- install babel module resolver ([092f8206](https://github.com/material-table-core/core/commit/092f82068e217744d4af881b243e77d9674f8ec4))
- add babel import aliases ([6105afd6](https://github.com/material-table-core/core/commit/6105afd6b4ffd20247003bb3b916633c049e2e2b))
- create MTableScrollbar ([07434b40](https://github.com/material-table-core/core/commit/07434b407f8b6dbe102746c9bb8a6e1869f6396c))
- remove chalk package ([fb817a42](https://github.com/material-table-core/core/commit/fb817a421c4852b55c123b14821669e5fd8ec6b1))
- fix formatting/spacing ([9a7eb079](https://github.com/material-table-core/core/commit/9a7eb07991ce933b06df21c6067dfcb6db66a88e))
- fix typo ([cb798b72](https://github.com/material-table-core/core/commit/cb798b721fb5ea22e4dbb88563045a607a23cdc5))
- move MTableBodyRow to own directory ([4c5354f8](https://github.com/material-table-core/core/commit/4c5354f846ef653f3ce07370400f262114944b13))
- clean up how persisting row click events are handled ([d735ef84](https://github.com/material-table-core/core/commit/d735ef8423110d720c74ce6ed771f588cd1e0883))
- change to force consumers to override ([48a08aa3](https://github.com/material-table-core/core/commit/48a08aa35afcdf7afd67f22efdf7ab9f0d94ed0b))
- update tests to start testing pre and post build ([e9d57280](https://github.com/material-table-core/core/commit/e9d5728003677704d177e714e457703dfe99a6fb))
- change transpiler ([2d11d942](https://github.com/material-table-core/core/commit/2d11d9422743cdf479180d161507244bf603d3a8))
- switch back to babel, still issues with esbuild ([b88892be](https://github.com/material-table-core/core/commit/b88892be20d7feb42013bcb3c474fe020e66d50d))
- use esbuild for transpiing instead of babel ([e8383429](https://github.com/material-table-core/core/commit/e8383429e0642f9a8081939cd2b09e8fb03d3c9b))
- add url ([1f3c56a3](https://github.com/material-table-core/core/commit/1f3c56a3fca0e31dc9c1f87c8355ec6f517b40c6))
- removla of wrong spreaded values of tablecell ([b4b04c6d](https://github.com/material-table-core/core/commit/b4b04c6dd53e14ff431b9cb3b840cb2013991e81))
- mrge edit cell validate fixes ([09e6487d](https://github.com/material-table-core/core/commit/09e6487d20d9e940ffd6bea6f1dc53842d2269a8))
- make @material-ui/core a peer dependency ([88179197](https://github.com/material-table-core/core/commit/8817919740116233c63b1073bd4033e129898bfb))
- **demo:** add demo and update linter ([e835e0ea](https://github.com/material-table-core/core/commit/e835e0ea786449d9220e71e635beba4547b1d8a5))

##### Documentation Changes

- add error for pagination with old mui version ([0617b8e3](https://github.com/material-table-core/core/commit/0617b8e30bebb8ec9491b209a1c347c4cfeb669f))
- create branch of current version ([85df956a](https://github.com/material-table-core/core/commit/85df956a485829e56cef7f9aaa6d0881b6717ba9))
- Update readme ([3718162e](https://github.com/material-table-core/core/commit/3718162e8f504605e84df59c7e62fb51685329d1))
- add changelog ([4b9af575](https://github.com/material-table-core/core/commit/4b9af5752e6fbdd22e3c14ba7abb3eacf0eaa04f))
- update readme ([5c601934](https://github.com/material-table-core/core/commit/5c601934b4f65aaaa4e3447e05acb9261dfa6f65))

##### New Features

- be able to adjust pagination position using flex ([c262a95f](https://github.com/material-table-core/core/commit/c262a95f7bc5607038e85a1765d6c22cf028419a))
- move to @react-forked/dnd ([0d4b020f](https://github.com/material-table-core/core/commit/0d4b020fdc23727f380ce811ab99e6273af833aa))
- add index to tableData ([8187c0fd](https://github.com/material-table-core/core/commit/8187c0fd36c3aa2dd451ce36e23b84cff2988009))
- add sortDirection to customSort ([23b02f1f](https://github.com/material-table-core/core/commit/23b02f1f7ab8bc47e56f50bb450799a485150422))
- keep detail panel open on rerender ([a881c1b8](https://github.com/material-table-core/core/commit/a881c1b8d9a3729d86e00643e3d513dc419ab47a))
- Rows cannot be clicked while editing ([96afa7d2](https://github.com/material-table-core/core/commit/96afa7d2236fd00768b9037ad850f0d6a2f8ec44))
- A key to override the default `id` tag to persist state between rerenders ([5a7d2b35](https://github.com/material-table-core/core/commit/5a7d2b3516c5347dcec1d389734a9ae33db47dca))
- export additional data for export func ([abf09a4e](https://github.com/material-table-core/core/commit/abf09a4eaf50269230b3db7ae800908a430d2155))
- export filtred data for exportFunc ([052b7871](https://github.com/material-table-core/core/commit/052b78716addffa4c4fc9cc3caf5dae761008c04))
- Update prop types for table cell ref ([105a2dbd](https://github.com/material-table-core/core/commit/105a2dbd97e280995bf17677a8d2fd2363b75a10))
- Improve renderSummaryRow ([756d225f](https://github.com/material-table-core/core/commit/756d225f45bc763e3d2faee46ffb3ed8779f29cc))
- Add group selection. ([#343](https://github.com/material-table-core/core/pull/343)) ([479798c2](https://github.com/material-table-core/core/commit/479798c28f63fe9c46b5f07b711362aff8c8d30a))
- add type module to package.json and fix esbuild issues ([e44ce4f3](https://github.com/material-table-core/core/commit/e44ce4f3d37daa4373faf31962235673a5802b52))
- detail npanel animation ([94a3a66e](https://github.com/material-table-core/core/commit/94a3a66ee8372dadd0b495e0a94bcf7e64de3014))
- add row id and provide telling warning for common errors ([39d5d35b](https://github.com/material-table-core/core/commit/39d5d35b77c22823a2da690d3de4ea9c6ac16031))
- Add on row double click ([6158df3e](https://github.com/material-table-core/core/commit/6158df3e9d743ad01d9782826333660696cf05cf))
- nRowsSelected method to toolbar localization ([c7c2d9a5](https://github.com/material-table-core/core/commit/c7c2d9a5d6f7899763b77bec812db31ea5b6627c))
- foreign handling of pagination counters ([58d32150](https://github.com/material-table-core/core/commit/58d321506450cf15a34af728f1de9a98c83ff839))
- add level param to functional rowStyle ([1d806fdf](https://github.com/material-table-core/core/commit/1d806fdfde7bdc63a310b55fe1fd71360fab686a))
- expose onSearchChange ([50271a5d](https://github.com/material-table-core/core/commit/50271a5d9b475e4031173b1af5ec43fc7b2ada6d))
- export unstyled MaterialTable as MTable ([ca999b65](https://github.com/material-table-core/core/commit/ca999b65e7251d39cc76577f3682c5e06e116079))
- able to align the detail panel icon column to right ([32fc6b94](https://github.com/material-table-core/core/commit/32fc6b94e428da631ba2ea3c723b5e7ae451e9d7))
- handle click on row ([56c21f0e](https://github.com/material-table-core/core/commit/56c21f0e37bba81bd09e98654d8879d0a1217707))
- **MaterialTable:** aggregate gropuings in localStoarge under material-table-groupings refactor(MTableGroupbar): map groupings feat(MTableGroupbar): clean up local storage when groupings are deleted ([0dd33f20](https://github.com/material-table-core/core/commit/0dd33f20fb515a895d743d01e1dcbde1fe6fad8b))
- **typescript:** update column.type definition ([6720dfd2](https://github.com/material-table-core/core/commit/6720dfd2ed4241d63456ce2e717fde76087a449b))
- **checkbox:** add init checked rows ([9970c035](https://github.com/material-table-core/core/commit/9970c035dde1f4a0ac9e19e770d1c1fcc2d95a71))
- **check:** possibility to load already checked rows ([b2926e03](https://github.com/material-table-core/core/commit/b2926e03fbeef3bff01873dca9dc5bfa46e351e9))
- **filter:** add checked checkbox filter ([97ec6d5f](https://github.com/material-table-core/core/commit/97ec6d5f39896d44fff327f763a3595012a2cc93))

##### Bug Fixes

- adjust current page to display detailpanel for remote data ([bcbb53ba](https://github.com/material-table-core/core/commit/bcbb53ba3db386b6ec3c8182b27fa33f44df1686))
- hidden columns resizing now works for correct col ([080ce82d](https://github.com/material-table-core/core/commit/080ce82d00332da7bec55db35c13af9afaa992fa))
- correct index for hidden column drag ([febedb34](https://github.com/material-table-core/core/commit/febedb347a84a43873d588ba5d68344ccc731f0f))
- background shadow breaks for fixed columns ([#503](https://github.com/material-table-core/core/pull/503)) ([02543a52](https://github.com/material-table-core/core/commit/02543a521863c0f4f6305fe882fae5ac09078e53))
- edit mode with fixed columns breaks table layout ([#498](https://github.com/material-table-core/core/pull/498)) ([58cdfa45](https://github.com/material-table-core/core/commit/58cdfa45638b386b18aca8b4cffc8775900640d2))
- show dragging header text on drag ([479b7532](https://github.com/material-table-core/core/commit/479b7532d263a2b9f2069dc7d449316e00970c86))
- column sort works for hidden ([b32d3bd3](https://github.com/material-table-core/core/commit/b32d3bd37c9179df2390454fd5add358bc7010ed))
- dispaly header for sorting false and grouping true ([80cbd95b](https://github.com/material-table-core/core/commit/80cbd95bbbb9f56f84376c462dd0e97a64414d24))
- RenderSortButton renders content correctly ([5faa47cb](https://github.com/material-table-core/core/commit/5faa47cb3562208e5cbf4d52a7ec3cbbebe876c6))
- Check for null summary row value ([3e93e915](https://github.com/material-table-core/core/commit/3e93e9156fdd335da5ddd955c7ac459c42503341))
- [#455](https://github.com/material-table-core/core/pull/455) Use proper detailPanel callback signature when detailPanel is an array of callbacks ([#468](https://github.com/material-table-core/core/pull/468)) ([b6ae7bc2](https://github.com/material-table-core/core/commit/b6ae7bc2ef0997c966c17119679f3024461779bc))
- Add sorting icon for draggable false ([c7918619](https://github.com/material-table-core/core/commit/c791861932ac09fbcd8bb269019645c2cb5601cc))
- extract the correct value for select edit cell ([3f681ba3](https://github.com/material-table-core/core/commit/3f681ba36d8daa36fbeaa5386a387787aff8afae))
- autofocus of edit rows ([77107104](https://github.com/material-table-core/core/commit/771071044bd4ff38fa1a9e5b2b93f27dc33b9bd3))
- [#441](https://github.com/material-table-core/core/pull/441) ([#443](https://github.com/material-table-core/core/pull/443)) ([ca3e4ee0](https://github.com/material-table-core/core/commit/ca3e4ee056e5b3d33254759426f5ada143710c1f))
- [#437](https://github.com/material-table-core/core/pull/437) ([#440](https://github.com/material-table-core/core/pull/440)) ([a9e65aac](https://github.com/material-table-core/core/commit/a9e65aaca4d47533482267cf0f948716ab48d65e))
- prevent enter to save for invalid row ([905d5252](https://github.com/material-table-core/core/commit/905d525278a520755ee0367a13425f7dc8132e29))
- regression of optional detail panel function ([6d55e366](https://github.com/material-table-core/core/commit/6d55e3660aa869df555197f1cf8bbfdf33b15d7f))
- typos in comments and components ([cc2b40e3](https://github.com/material-table-core/core/commit/cc2b40e374bc424fe4cdc3f466f9dff9e340d277))
- transpiler issues, move back to babel ([20e9a1e7](https://github.com/material-table-core/core/commit/20e9a1e7b01a74ca128ba615b8d1af0328ec1ab9))
- issue with jest and modules ([64842a9b](https://github.com/material-table-core/core/commit/64842a9b2d47bdbb63fb1513bdcfd390e12aab3a))
- delay in onRowClick ([6301b34d](https://github.com/material-table-core/core/commit/6301b34dc71d3994dcc22673fef1ff480f81bb8a))
- persist row click events, single and double click ([6337c3bf](https://github.com/material-table-core/core/commit/6337c3bfefaee356228426af74f7ac02da55567a))
- issue when programmatically hiding a shown detail panel [#282](https://github.com/material-table-core/core/pull/282) ([4696507d](https://github.com/material-table-core/core/commit/4696507d7bf71d9dcaa0b0bfc733c5b973b39bf2))
- Move duble click to syntheic events ([fcf963da](https://github.com/material-table-core/core/commit/fcf963da436f5520f518530e3632ad76b47155b2))
- Proptype fix for tabelcell ([101d2900](https://github.com/material-table-core/core/commit/101d2900b5ed280920d751248f51225d1380f1da))
- only apply drag style if dragging ([04b538f0](https://github.com/material-table-core/core/commit/04b538f0de5aed16017ad8c8fc5b1bf5bb654163))
- Update m-table-body-row on 'NaN' margin-left error. ([2d4a85c5](https://github.com/material-table-core/core/commit/2d4a85c5e605a18484965c2364630b74b906855c))
- Hook edit cell up to validate ([88bb78f0](https://github.com/material-table-core/core/commit/88bb78f01da564d57f6432414644088aa56292da))
- Fallback for change of columns ([d4302655](https://github.com/material-table-core/core/commit/d4302655e5af87cb07e15f2b581772628d238b80))
- PRevent column width to be set in stone it not resizing ([6c430c53](https://github.com/material-table-core/core/commit/6c430c53729d72fb0c4e214bb4f036570fecf4a2))
- Set width of columns without mutations ([4e08c89a](https://github.com/material-table-core/core/commit/4e08c89ac4ee7452a62db9aa2dd8cc4519a7fba5))
- Fixed EditComponentProps ([04282538](https://github.com/material-table-core/core/commit/042825383b2a9d16845dc3b1e757695393839ff5))
- remove equality check on data prop function when remote data is true, no sense to check for that ([cfd8f2d4](https://github.com/material-table-core/core/commit/cfd8f2d47ea069af4497febbf5b6e67401f306fc))
- remove tableData property from column in check phase ([56565225](https://github.com/material-table-core/core/commit/565652251df3a2ea7c73382e391eec0c35a36700))
- add page, totalCount to props ([0a0f07a2](https://github.com/material-table-core/core/commit/0a0f07a21312f3ebb765a1c92db0ed703dd11c0f))
- export data with lookup values ([47eba169](https://github.com/material-table-core/core/commit/47eba16971b053f202255b368af3d5c6cc1a68c1))
- **actions-header:** Do not force textAlign ([#375](https://github.com/material-table-core/core/pull/375)) ([356a0555](https://github.com/material-table-core/core/commit/356a0555681fecfaff4d83c7f4a0a3b3b6c0f1a7))
- **MTableRow:** dont override enter on button elements ([5387af47](https://github.com/material-table-core/core/commit/5387af47f90e52854247de2c7b1851da5c378d8f))
- **DataManager:** set new groupsIndex in sortData() ([9a51e314](https://github.com/material-table-core/core/commit/9a51e31476fb381295286b74311cd095fd5b3d05))
- **typings:**
  - added missing totalCount type on Query interface ([c11febb0](https://github.com/material-table-core/core/commit/c11febb04a173a378af65e41147b2b41725562c4))
  - added missing 'width' type on Column interface ([63d0ae60](https://github.com/material-table-core/core/commit/63d0ae606122ca13cb3d55c10f3c046abd7de730))
- **editComponent:** add missing onRowDataChange type declaration ([605b95a7](https://github.com/material-table-core/core/commit/605b95a78c565685998cec8456f873f528498e07))
- **types:** change void to any for promises return on editable callbacks ([3457e5b6](https://github.com/material-table-core/core/commit/3457e5b68efcd02ca5e0477c52db1c7e2f1d2749))
- **table filter:** add key to TableCell for action column ([49593494](https://github.com/material-table-core/core/commit/4959349452968e00800abda2006f5d273887931c))

##### Other Changes

- check for localStorage for SSR ([ce738354](https://github.com/material-table-core/core/commit/ce738354563e3bbf9b5ba63c5adf60f28cf9801c))
- //github.com/material-table-core/core ([b8023ead](https://github.com/material-table-core/core/commit/b8023ead8f63d8887bee31474a4845d7a2afd2c0))
- do not fail on hidden columns dragging ([5966ee37](https://github.com/material-table-core/core/commit/5966ee373e88836e7f47f266af6da314f9ad88ad))
- //github.com/material-table-core/core ([c13b88a4](https://github.com/material-table-core/core/commit/c13b88a45aa7d6a33d275da2c869a76074aae8a0))
- add missing idSynonym ([027becc8](https://github.com/material-table-core/core/commit/027becc8a56628697ca033ecee71269226adde16))
- //github.com/material-table-core/core ([2d1da8d0](https://github.com/material-table-core/core/commit/2d1da8d01a86e6dbbc4fb5be100464097492f960))
- improve exports to only export correct data ([a8644bc3](https://github.com/material-table-core/core/commit/a8644bc31acf3ff26af59d357bea1cddaa839ec8))
- //github.com/material-table-core/core ([33fffdf3](https://github.com/material-table-core/core/commit/33fffdf38e0e755f1ac59db63913a3c1dac40508))
- //github.com/material-table-core/core ([f017eeca](https://github.com/material-table-core/core/commit/f017eeca328f228454a90e81345d8ec00a20494d))
- //github.com/material-table-core/core ([1f5638f5](https://github.com/material-table-core/core/commit/1f5638f58f6f79234ead098ffb4313117c32b3d6))
- //github.com/material-table-core/core ([9245d2ff](https://github.com/material-table-core/core/commit/9245d2ff602e4444ac4c4b842dcee525254c9ec4))
- //github.com/material-table-core/core ([51682e8d](https://github.com/material-table-core/core/commit/51682e8d07ba07f5823b99efeacfbfbdfef9fecb))
- //github.com/material-table-core/core ([b316bf31](https://github.com/material-table-core/core/commit/b316bf319dc8c6aa26c06062cf5e723d404c0ad0))
- rename handler ([d97e81e9](https://github.com/material-table-core/core/commit/d97e81e9d48a9ac454da193483e1a7e4dcba717f))
- build clean up comments ([0bb41291](https://github.com/material-table-core/core/commit/0bb41291f83a737b884fca1c9de5dcced7ea0c22))
- //github.com/material-table-core/core ([c2566924](https://github.com/material-table-core/core/commit/c25669242a9d0f160f9782a4787796520c205a45))
- build fix esbuild issues ([d37ff606](https://github.com/material-table-core/core/commit/d37ff606dcdd3a79ab66e0306b1fa235dde61154))
- //github.com/material-table-core/core ([72fbd53d](https://github.com/material-table-core/core/commit/72fbd53d6d9cdc9249d199279384c234b0f9ca7a))
- //github.com/material-table-core/core ([3f31e92e](https://github.com/material-table-core/core/commit/3f31e92ed35b7812aa8f7e5cc8c0a8810e4b1066))
- build add demo ([0f2a7e3a](https://github.com/material-table-core/core/commit/0f2a7e3ac9c30200c79aad7e2fd33c8357d886d9))
- build remove exporters from files ([6ec1a476](https://github.com/material-table-core/core/commit/6ec1a4767a6e9a000f2e4a140d383f082ab0c3e9))
- //github.com/material-table-core/core ([eef03a06](https://github.com/material-table-core/core/commit/eef03a063b0fd446433943bfcb774bc6cce2dae4))
- //github.com/material-table-core/core ([7dbd7a4b](https://github.com/material-table-core/core/commit/7dbd7a4b75b38ea180bdce8e8d973eae888c0e94))
- keep tabledata from previous columns ([e0fa5ee0](https://github.com/material-table-core/core/commit/e0fa5ee0dd480610022a14b02ff65a8c55b38ddd))
- build testing ([d8174194](https://github.com/material-table-core/core/commit/d817419456f40a54d1e8e72a62f724feddc2816e))
- build testing ([0a8cf7b0](https://github.com/material-table-core/core/commit/0a8cf7b0558acaa57b07a4137d8fb4781b6ea580))
- build update build.yml ([7b9d3cf3](https://github.com/material-table-core/core/commit/7b9d3cf3eeaf85ec6d52519609d8d88dc78b2681))
- build testing ([797344ab](https://github.com/material-table-core/core/commit/797344abc647d73837d9f95213f6a32330718cb1))
- build update build yml; test if skip build still works ([422d09bf](https://github.com/material-table-core/core/commit/422d09bf98ce9a04ffd6e5a008d96f8c93245b7d))
- build update build yml ([12367e66](https://github.com/material-table-core/core/commit/12367e660f068ccdad72a8368b62a7115459506a))
- build update build.yml ([af77c277](https://github.com/material-table-core/core/commit/af77c277e0e6718be417a0ec0fd86829902455d1))
- build update readme ([1fb439b6](https://github.com/material-table-core/core/commit/1fb439b698e887bfaa39099e4ab8299fa470d163))
- build update readme ([dfc74a89](https://github.com/material-table-core/core/commit/dfc74a8994701b91459df3ac6e42ba72c8a633b2))
- build ([8b5925fc](https://github.com/material-table-core/core/commit/8b5925fc60b90e1edf7afba147e4e11c55a40a37))
- Align title with columns ([db85a061](https://github.com/material-table-core/core/commit/db85a061487a5cfd4af61570a02f5a34eef7cd65))
- //github.com/material-table-core/core ([2dcf3f8a](https://github.com/material-table-core/core/commit/2dcf3f8a661f7359140ff87607551aa12168aedb))
- //github.com/material-table-core/core ([5e9ec31b](https://github.com/material-table-core/core/commit/5e9ec31ba826ef167602b2e2a3503ec8afddab85))
- missing colSpan prop for MTableCell ([d80830eb](https://github.com/material-table-core/core/commit/d80830eb15bca1d5edc4d0c5d8841b09b2461d75))
- //github.com/MrWittman612/core into MrWittman612-Refactor-MTableActions-class-to-functional-component ([0c4961f9](https://github.com/material-table-core/core/commit/0c4961f9655bceeb91fdf9e5bdcf9f01f66874c1))
- //github.com/material-table-core/refactor-material-table ([771674d6](https://github.com/material-table-core/core/commit/771674d6c7478fbf26c40b47c22f5595192fa5ba))
- //github.com/mbrn/material-table into feature-column-resizing ([ace4adec](https://github.com/material-table-core/core/commit/ace4adecc0e272e884772c81fdef6e172bd002b8))
- //github.com/floAr/material-table" ([a79fa7ee](https://github.com/material-table-core/core/commit/a79fa7ee80b9558c9005e46cfd6b186cded7cc2a))
- //github.com/floAr/material-table ([e499fd2a](https://github.com/material-table-core/core/commit/e499fd2a990331e4bad383fe5e0332f25ec616a8))
- //github.com/floAr/material-table ([572885b4](https://github.com/material-table-core/core/commit/572885b45d5da69d15669b0662da1477cf9a439e))
- Cannot find name 'RowData' ([9f1e3cf1](https://github.com/material-table-core/core/commit/9f1e3cf1113d8c5d8c7b074e63e764183a87a5f8))
- //github.com/floAr/material-table ([d51e1406](https://github.com/material-table-core/core/commit/d51e14062cd4a99e3e4e9930d4ebcba81b367c7f))
- //github.com/mbrn/material-table ([700b6111](https://github.com/material-table-core/core/commit/700b611186c4fa2ac3d478fa43630887c0317112))
- //github.com/Domino987/material-table into prettier ([1726cfe6](https://github.com/material-table-core/core/commit/1726cfe6b7c2a3ef656fc8ce445bbff04dcc47fd))
- onRowAddCancelled and onRowUpdateCancelled has been added ([1ecf3c07](https://github.com/material-table-core/core/commit/1ecf3c0774427be93f70ed1320224ba6dc283048))
- broken isEditable and isDeletable options ([d6e9e7b5](https://github.com/material-table-core/core/commit/d6e9e7b56df42e72cef9391f541a034b69f5c92b))
- marginTop in TableFilterRow ([57aa5d32](https://github.com/material-table-core/core/commit/57aa5d327992ef857089fc9333757420ba37d76e))
- //github.com/mbrn/material-table ([44b60bb7](https://github.com/material-table-core/core/commit/44b60bb71513b40073a531e265127883091424d3))
- action icon can be a string, function or Component ([fe283a5e](https://github.com/material-table-core/core/commit/fe283a5eefd60a3f7e6b08c47f83f92fba9ba24f))
- //github.com/ryanintulsa/material-table into ryanintulsa-dragAndDropWithHiddenColsFix ([a7b683f6](https://github.com/material-table-core/core/commit/a7b683f6db6d41a31ac13197b431d91ee572899c))
- prevent actions icons re-render ([5e133cf6](https://github.com/material-table-core/core/commit/5e133cf6bf8045745316b5f073200b76c3938c3c))
- //github.com/mbrn/material-table/pull/1205#issuecomment-544285507 ([b4b62ebc](https://github.com/material-table-core/core/commit/b4b62ebc80698dc0a6ecc3a98e8544f8d8b5668d))
- //github.com/martin-pepgit/material-table into martin-pepgit-issue_968 ([961df05e](https://github.com/material-table-core/core/commit/961df05e3b5ebf34ba57ae1e4cd9981a20783b3c))
- //github.com/mbrn/material-table/issues/932 ([a09d1696](https://github.com/material-table-core/core/commit/a09d1696c4480a3c6fff41ba98d429d823ba2cea))
- true ([a9a50f72](https://github.com/material-table-core/core/commit/a9a50f72b278f433fd549195e851b270add38f08))
- reuse defaultExpanded option ([29ad4298](https://github.com/material-table-core/core/commit/29ad4298e9dcfe31c562319009d9ba9a6ea86b78))
- //github.com/martin-pepgit/material-table into martin-pepgit-issue_945 ([9496ff75](https://github.com/material-table-core/core/commit/9496ff75dcb5454ea4b31901d04494970124a187))
- //github.com/emrekara37/material-table into emrekara37-tooltip-position ([c9b05535](https://github.com/material-table-core/core/commit/c9b055358ce38bb1a78f76d10befd2255ea83cc2))
- Header checkbox is not working properly when grouping is enabled ([59f28e43](https://github.com/material-table-core/core/commit/59f28e4319a0a810c2d8725b114df9d49a6e1ea7))
- //github.com/KATT/material-table into KATT-fix-row-onclick-typedefs ([cfaba4f8](https://github.com/material-table-core/core/commit/cfaba4f83b98ed48ae9c4ae8b27effc848169355))
- //github.com/emrekara37/material-table into emrekara37-override-sortarrow-icon ([9d2b7467](https://github.com/material-table-core/core/commit/9d2b74670740647064f7acd56f55c47a0932b982))
- //github.com/theodore-koch/material-table into theodore-koch-feat/add-level-to-functional-rowStyle ([6a32389a](https://github.com/material-table-core/core/commit/6a32389ad572d44aa28d9d4861351f54e32dd0b8))
- //github.com/Paktusin/material-table into Paktusin-master ([02712ce1](https://github.com/material-table-core/core/commit/02712ce1ba4040cd99e50688785ae40b41466c65))
- use callback after state is set ([f9a6e83a](https://github.com/material-table-core/core/commit/f9a6e83a825717eeaf895ce799ca5baaae0a7311))
- use callback after state is set ([12c1bd00](https://github.com/material-table-core/core/commit/12c1bd00dc0d735018b00afee3b0ead2372501b8))
- //github.com/mbrn/material-table ([d37bf4c5](https://github.com/material-table-core/core/commit/d37bf4c585f7c0cc559b78601ef9d0576cb587e0))
- //github.com/MaxLeiter/material-table into MaxLeiter-patch-1 ([543bb407](https://github.com/material-table-core/core/commit/543bb407cfc27ec65f073bb9bec97b912014499c))
- //github.com/yzhbankov/material-table into yzhbankov-filter-placeholder-fix ([ec2fad86](https://github.com/material-table-core/core/commit/ec2fad86f64829e6c94063462e848f0b78603376))
- Warnings when options.paginationType == 'stepped' ([f4e7c696](https://github.com/material-table-core/core/commit/f4e7c6962c42e874a0b136bed105918fbcfe0022))
- //github.com/gianlucamateo/material-table into gianlucamateo-bug/treeSearch ([cbf87104](https://github.com/material-table-core/core/commit/cbf87104da323681f008323facf4641be1834033))
- //github.com/AndySeymour2904/material-table into AndySeymour2904-iss708 ([ea30f04a](https://github.com/material-table-core/core/commit/ea30f04a4409ec14ddc98ee325236b624ed84366))
- //github.com/AugustoCalaca/material-table into AugustoCalaca-feature/placeholder-filtering ([768576fa](https://github.com/material-table-core/core/commit/768576fa523835940e0f7430bf863fc4e64c0fa0))
- //github.com/gianlucamateo/material-table into gianlucamateo-feature/customRowPadding ([3c60e815](https://github.com/material-table-core/core/commit/3c60e81584094e83f8b9eee76318dc4edc1daf7a))
- //github.com/mbrn/material-table ([eccb1e85](https://github.com/material-table-core/core/commit/eccb1e857bcbbda3317d4079f08fa487428a1901))
- Returning the row Data was checked and it is available in onSelectionChange ([fcba9f95](https://github.com/material-table-core/core/commit/fcba9f9510cf3f9dea6e87171acc9a6aa5e8d2c5))
- //github.com/mbrn/material-table ([50d9325a](https://github.com/material-table-core/core/commit/50d9325a566295684615181b1320d884f2544a1b))
- //github.com/truongtv22/material-table into bug/display-2-searchbox ([23ece5a1](https://github.com/material-table-core/core/commit/23ece5a12c7b9c1cde46aa62120642cb13254749))
- //github.com/truongtv22/material-table into bug/edit-child-rows ([15a7cb98](https://github.com/material-table-core/core/commit/15a7cb98fabf3b30ea2c867ba3a3bbca571efe78))
- //github.com/rssluca/material-table into rssluca-master ([b2bca2a8](https://github.com/material-table-core/core/commit/b2bca2a87cd37c93f066eaf54d7a6646a693a5f9))
- //github.com/truongtv22/material-table into truongtv22-feature-option-expand-all-rows ([ca63e47f](https://github.com/material-table-core/core/commit/ca63e47fb7572ee06786525dc816245f968c39c0))
- //github.com/rssluca/material-table into rssluca-master ([3081523b](https://github.com/material-table-core/core/commit/3081523b8298e8482c0e8a96f33863c40f13a8ed))
- //github.com/mbrn/material-table ([f8920251](https://github.com/material-table-core/core/commit/f89202513638534e0560a04e97ed4363fcb0154d))
- Cannot read property isExpanded of undefined ([77c1c1e8](https://github.com/material-table-core/core/commit/77c1c1e89f464fc98a9fbd118ed8977a42e90cae))
- find by path was not working after paging ([1422f1ad](https://github.com/material-table-core/core/commit/1422f1ad6ceffdb624f05a90afc6f686834562e0))
- //github.com/mbrn/material-table ([2cd32c82](https://github.com/material-table-core/core/commit/2cd32c82bf75114d4fd7e08330156da1dbe8cc7e))
- //github.com/mbrn/material-table ([4019e127](https://github.com/material-table-core/core/commit/4019e1277bd4fae55c2bb1d3150cbc2df337b9f7))
- //github.com/mbrn/material-table into mbrn-master ([434d196b](https://github.com/material-table-core/core/commit/434d196be65762977ab622665059f388c7642cf0))
- //github.com/mbrn/material-table ([140b9cd9](https://github.com/material-table-core/core/commit/140b9cd952133277ac843a82e2cc972a8dbc6800))
- This closes [#38](https://github.com/material-table-core/core/pull/38), actions columns rendering problem was solved ([e337135e](https://github.com/material-table-core/core/commit/e337135e9881780d3057372d9a4fc8d0376361ee))
- free actions was not rendering when columns buttons disabled ([42eec9b4](https://github.com/material-table-core/core/commit/42eec9b40aaf319ac9f18cd9fa3fa63ca0d44cd5))
- Free actions added ([450ff197](https://github.com/material-table-core/core/commit/450ff197b122f758ab16b82dc17c1440ecebcb48))
- Horizontal scroll set to only table content, except header and footer ([db92b353](https://github.com/material-table-core/core/commit/db92b3536a3c247d13228bc75c3687328866fa8b))
- action disabled property added ([10ac40af](https://github.com/material-table-core/core/commit/10ac40afcbe413d730ace2bbd3485c12455159c7))
- This closes [#33](https://github.com/material-table-core/core/pull/33) ([e99ee76e](https://github.com/material-table-core/core/commit/e99ee76e7cd9c6cdad8ea3838889f4a25732cc63))
- This closes [#31](https://github.com/material-table-core/core/pull/31), action buttons new line problem solved ([c982d0b4](https://github.com/material-table-core/core/commit/c982d0b498e1e634c9732395be6121e724faeae0))
- //github.com/mbrn/material-table ([cda25533](https://github.com/material-table-core/core/commit/cda25533802f858545d0dbda036a2cf345428225))
- **check:** possibility to load already checked rows" ([c1c7c117](https://github.com/material-table-core/core/commit/c1c7c11743001eb04db3823afe4c5af713a0249d))

##### Refactors

- omit one `Omit` ([#463](https://github.com/material-table-core/core/pull/463)) ([d99d551d](https://github.com/material-table-core/core/commit/d99d551dee04ceb0ebdc165c0b4aaad42b49e28c))
- create MTableCustomIcon component ([b1f8e617](https://github.com/material-table-core/core/commit/b1f8e617da0aab725dc8638189950a7d5c506ee3))
- support for mui 4.12 ([ef81cb73](https://github.com/material-table-core/core/commit/ef81cb736e6224a4a9190ceb176d7398ce7171cd))
- cleanup unused imports ([e3cc8fba](https://github.com/material-table-core/core/commit/e3cc8fbae6eb4a979b72e8392f6f0a8b7336e8d2))
- persist an array instead of object ([5bf5e92a](https://github.com/material-table-core/core/commit/5bf5e92ad9a90fb8c951f5ba6780dc1a777b6078))
- MTableBodyRow component added ([73ed3771](https://github.com/material-table-core/core/commit/73ed3771ba085425798b4fd89108cb7c13ce57d1))
- m-table-body component created and used by main component ([5adfc68a](https://github.com/material-table-core/core/commit/5adfc68aed6c98cf0e87ed7292295b455dd46235))

#### 4.3.45 (2022-09-14)

##### Breaking Changes

- rename `onDoubleRowClick` to `onRowDoubleClick` ([32a7f3ac](https://github.com/material-table-core/core/commit/32a7f3ac5f371d3e349e1d2790f325efaa3b3a48))

##### Chores

- use @hello-pangea/dnd ([#608](https://github.com/material-table-core/core/pull/608)) ([e89f4bb8](https://github.com/material-table-core/core/commit/e89f4bb89e62c22cb72c1f20d4593ebede2d4662))
- update package.lock ([d724c7ef](https://github.com/material-table-core/core/commit/d724c7ef6f5daffa8bdbe94749a9215f1b4902b9))
- install babel module resolver ([092f8206](https://github.com/material-table-core/core/commit/092f82068e217744d4af881b243e77d9674f8ec4))
- add babel import aliases ([6105afd6](https://github.com/material-table-core/core/commit/6105afd6b4ffd20247003bb3b916633c049e2e2b))
- create MTableScrollbar ([07434b40](https://github.com/material-table-core/core/commit/07434b407f8b6dbe102746c9bb8a6e1869f6396c))
- remove chalk package ([fb817a42](https://github.com/material-table-core/core/commit/fb817a421c4852b55c123b14821669e5fd8ec6b1))
- fix formatting/spacing ([9a7eb079](https://github.com/material-table-core/core/commit/9a7eb07991ce933b06df21c6067dfcb6db66a88e))
- fix typo ([cb798b72](https://github.com/material-table-core/core/commit/cb798b721fb5ea22e4dbb88563045a607a23cdc5))
- move MTableBodyRow to own directory ([4c5354f8](https://github.com/material-table-core/core/commit/4c5354f846ef653f3ce07370400f262114944b13))
- clean up how persisting row click events are handled ([d735ef84](https://github.com/material-table-core/core/commit/d735ef8423110d720c74ce6ed771f588cd1e0883))
- change to force consumers to override ([48a08aa3](https://github.com/material-table-core/core/commit/48a08aa35afcdf7afd67f22efdf7ab9f0d94ed0b))
- update tests to start testing pre and post build ([e9d57280](https://github.com/material-table-core/core/commit/e9d5728003677704d177e714e457703dfe99a6fb))
- change transpiler ([2d11d942](https://github.com/material-table-core/core/commit/2d11d9422743cdf479180d161507244bf603d3a8))
- switch back to babel, still issues with esbuild ([b88892be](https://github.com/material-table-core/core/commit/b88892be20d7feb42013bcb3c474fe020e66d50d))
- use esbuild for transpiing instead of babel ([e8383429](https://github.com/material-table-core/core/commit/e8383429e0642f9a8081939cd2b09e8fb03d3c9b))
- add url ([1f3c56a3](https://github.com/material-table-core/core/commit/1f3c56a3fca0e31dc9c1f87c8355ec6f517b40c6))
- removla of wrong spreaded values of tablecell ([b4b04c6d](https://github.com/material-table-core/core/commit/b4b04c6dd53e14ff431b9cb3b840cb2013991e81))
- mrge edit cell validate fixes ([09e6487d](https://github.com/material-table-core/core/commit/09e6487d20d9e940ffd6bea6f1dc53842d2269a8))
- make @material-ui/core a peer dependency ([88179197](https://github.com/material-table-core/core/commit/8817919740116233c63b1073bd4033e129898bfb))
- **demo:** add demo and update linter ([e835e0ea](https://github.com/material-table-core/core/commit/e835e0ea786449d9220e71e635beba4547b1d8a5))

##### Documentation Changes

- add error for pagination with old mui version ([0617b8e3](https://github.com/material-table-core/core/commit/0617b8e30bebb8ec9491b209a1c347c4cfeb669f))
- create branch of current version ([85df956a](https://github.com/material-table-core/core/commit/85df956a485829e56cef7f9aaa6d0881b6717ba9))
- Update readme ([3718162e](https://github.com/material-table-core/core/commit/3718162e8f504605e84df59c7e62fb51685329d1))
- add changelog ([4b9af575](https://github.com/material-table-core/core/commit/4b9af5752e6fbdd22e3c14ba7abb3eacf0eaa04f))
- update readme ([5c601934](https://github.com/material-table-core/core/commit/5c601934b4f65aaaa4e3447e05acb9261dfa6f65))

##### New Features

- be able to adjust pagination position using flex ([c262a95f](https://github.com/material-table-core/core/commit/c262a95f7bc5607038e85a1765d6c22cf028419a))
- move to @react-forked/dnd ([0d4b020f](https://github.com/material-table-core/core/commit/0d4b020fdc23727f380ce811ab99e6273af833aa))
- add index to tableData ([8187c0fd](https://github.com/material-table-core/core/commit/8187c0fd36c3aa2dd451ce36e23b84cff2988009))
- add sortDirection to customSort ([23b02f1f](https://github.com/material-table-core/core/commit/23b02f1f7ab8bc47e56f50bb450799a485150422))
- keep detail panel open on rerender ([a881c1b8](https://github.com/material-table-core/core/commit/a881c1b8d9a3729d86e00643e3d513dc419ab47a))
- Rows cannot be clicked while editing ([96afa7d2](https://github.com/material-table-core/core/commit/96afa7d2236fd00768b9037ad850f0d6a2f8ec44))
- A key to override the default `id` tag to persist state between rerenders ([5a7d2b35](https://github.com/material-table-core/core/commit/5a7d2b3516c5347dcec1d389734a9ae33db47dca))
- export additional data for export func ([abf09a4e](https://github.com/material-table-core/core/commit/abf09a4eaf50269230b3db7ae800908a430d2155))
- export filtred data for exportFunc ([052b7871](https://github.com/material-table-core/core/commit/052b78716addffa4c4fc9cc3caf5dae761008c04))
- Update prop types for table cell ref ([105a2dbd](https://github.com/material-table-core/core/commit/105a2dbd97e280995bf17677a8d2fd2363b75a10))
- Improve renderSummaryRow ([756d225f](https://github.com/material-table-core/core/commit/756d225f45bc763e3d2faee46ffb3ed8779f29cc))
- Add group selection. ([#343](https://github.com/material-table-core/core/pull/343)) ([479798c2](https://github.com/material-table-core/core/commit/479798c28f63fe9c46b5f07b711362aff8c8d30a))
- add type module to package.json and fix esbuild issues ([e44ce4f3](https://github.com/material-table-core/core/commit/e44ce4f3d37daa4373faf31962235673a5802b52))
- detail npanel animation ([94a3a66e](https://github.com/material-table-core/core/commit/94a3a66ee8372dadd0b495e0a94bcf7e64de3014))
- add row id and provide telling warning for common errors ([39d5d35b](https://github.com/material-table-core/core/commit/39d5d35b77c22823a2da690d3de4ea9c6ac16031))
- Add on row double click ([6158df3e](https://github.com/material-table-core/core/commit/6158df3e9d743ad01d9782826333660696cf05cf))
- nRowsSelected method to toolbar localization ([c7c2d9a5](https://github.com/material-table-core/core/commit/c7c2d9a5d6f7899763b77bec812db31ea5b6627c))
- foreign handling of pagination counters ([58d32150](https://github.com/material-table-core/core/commit/58d321506450cf15a34af728f1de9a98c83ff839))
- add level param to functional rowStyle ([1d806fdf](https://github.com/material-table-core/core/commit/1d806fdfde7bdc63a310b55fe1fd71360fab686a))
- expose onSearchChange ([50271a5d](https://github.com/material-table-core/core/commit/50271a5d9b475e4031173b1af5ec43fc7b2ada6d))
- export unstyled MaterialTable as MTable ([ca999b65](https://github.com/material-table-core/core/commit/ca999b65e7251d39cc76577f3682c5e06e116079))
- able to align the detail panel icon column to right ([32fc6b94](https://github.com/material-table-core/core/commit/32fc6b94e428da631ba2ea3c723b5e7ae451e9d7))
- handle click on row ([56c21f0e](https://github.com/material-table-core/core/commit/56c21f0e37bba81bd09e98654d8879d0a1217707))
- **MaterialTable:** aggregate gropuings in localStoarge under material-table-groupings refactor(MTableGroupbar): map groupings feat(MTableGroupbar): clean up local storage when groupings are deleted ([0dd33f20](https://github.com/material-table-core/core/commit/0dd33f20fb515a895d743d01e1dcbde1fe6fad8b))
- **typescript:** update column.type definition ([6720dfd2](https://github.com/material-table-core/core/commit/6720dfd2ed4241d63456ce2e717fde76087a449b))
- **checkbox:** add init checked rows ([9970c035](https://github.com/material-table-core/core/commit/9970c035dde1f4a0ac9e19e770d1c1fcc2d95a71))
- **check:** possibility to load already checked rows ([b2926e03](https://github.com/material-table-core/core/commit/b2926e03fbeef3bff01873dca9dc5bfa46e351e9))
- **filter:** add checked checkbox filter ([97ec6d5f](https://github.com/material-table-core/core/commit/97ec6d5f39896d44fff327f763a3595012a2cc93))

##### Bug Fixes

- adjust current page to display detailpanel for remote data ([bcbb53ba](https://github.com/material-table-core/core/commit/bcbb53ba3db386b6ec3c8182b27fa33f44df1686))
- hidden columns resizing now works for correct col ([080ce82d](https://github.com/material-table-core/core/commit/080ce82d00332da7bec55db35c13af9afaa992fa))
- correct index for hidden column drag ([febedb34](https://github.com/material-table-core/core/commit/febedb347a84a43873d588ba5d68344ccc731f0f))
- background shadow breaks for fixed columns ([#503](https://github.com/material-table-core/core/pull/503)) ([02543a52](https://github.com/material-table-core/core/commit/02543a521863c0f4f6305fe882fae5ac09078e53))
- edit mode with fixed columns breaks table layout ([#498](https://github.com/material-table-core/core/pull/498)) ([58cdfa45](https://github.com/material-table-core/core/commit/58cdfa45638b386b18aca8b4cffc8775900640d2))
- show dragging header text on drag ([479b7532](https://github.com/material-table-core/core/commit/479b7532d263a2b9f2069dc7d449316e00970c86))
- column sort works for hidden ([b32d3bd3](https://github.com/material-table-core/core/commit/b32d3bd37c9179df2390454fd5add358bc7010ed))
- dispaly header for sorting false and grouping true ([80cbd95b](https://github.com/material-table-core/core/commit/80cbd95bbbb9f56f84376c462dd0e97a64414d24))
- RenderSortButton renders content correctly ([5faa47cb](https://github.com/material-table-core/core/commit/5faa47cb3562208e5cbf4d52a7ec3cbbebe876c6))
- Check for null summary row value ([3e93e915](https://github.com/material-table-core/core/commit/3e93e9156fdd335da5ddd955c7ac459c42503341))
- [#455](https://github.com/material-table-core/core/pull/455) Use proper detailPanel callback signature when detailPanel is an array of callbacks ([#468](https://github.com/material-table-core/core/pull/468)) ([b6ae7bc2](https://github.com/material-table-core/core/commit/b6ae7bc2ef0997c966c17119679f3024461779bc))
- Add sorting icon for draggable false ([c7918619](https://github.com/material-table-core/core/commit/c791861932ac09fbcd8bb269019645c2cb5601cc))
- extract the correct value for select edit cell ([3f681ba3](https://github.com/material-table-core/core/commit/3f681ba36d8daa36fbeaa5386a387787aff8afae))
- autofocus of edit rows ([77107104](https://github.com/material-table-core/core/commit/771071044bd4ff38fa1a9e5b2b93f27dc33b9bd3))
- [#441](https://github.com/material-table-core/core/pull/441) ([#443](https://github.com/material-table-core/core/pull/443)) ([ca3e4ee0](https://github.com/material-table-core/core/commit/ca3e4ee056e5b3d33254759426f5ada143710c1f))
- [#437](https://github.com/material-table-core/core/pull/437) ([#440](https://github.com/material-table-core/core/pull/440)) ([a9e65aac](https://github.com/material-table-core/core/commit/a9e65aaca4d47533482267cf0f948716ab48d65e))
- prevent enter to save for invalid row ([905d5252](https://github.com/material-table-core/core/commit/905d525278a520755ee0367a13425f7dc8132e29))
- regression of optional detail panel function ([6d55e366](https://github.com/material-table-core/core/commit/6d55e3660aa869df555197f1cf8bbfdf33b15d7f))
- typos in comments and components ([cc2b40e3](https://github.com/material-table-core/core/commit/cc2b40e374bc424fe4cdc3f466f9dff9e340d277))
- transpiler issues, move back to babel ([20e9a1e7](https://github.com/material-table-core/core/commit/20e9a1e7b01a74ca128ba615b8d1af0328ec1ab9))
- issue with jest and modules ([64842a9b](https://github.com/material-table-core/core/commit/64842a9b2d47bdbb63fb1513bdcfd390e12aab3a))
- delay in onRowClick ([6301b34d](https://github.com/material-table-core/core/commit/6301b34dc71d3994dcc22673fef1ff480f81bb8a))
- persist row click events, single and double click ([6337c3bf](https://github.com/material-table-core/core/commit/6337c3bfefaee356228426af74f7ac02da55567a))
- issue when programmatically hiding a shown detail panel [#282](https://github.com/material-table-core/core/pull/282) ([4696507d](https://github.com/material-table-core/core/commit/4696507d7bf71d9dcaa0b0bfc733c5b973b39bf2))
- Move duble click to syntheic events ([fcf963da](https://github.com/material-table-core/core/commit/fcf963da436f5520f518530e3632ad76b47155b2))
- Proptype fix for tabelcell ([101d2900](https://github.com/material-table-core/core/commit/101d2900b5ed280920d751248f51225d1380f1da))
- only apply drag style if dragging ([04b538f0](https://github.com/material-table-core/core/commit/04b538f0de5aed16017ad8c8fc5b1bf5bb654163))
- Update m-table-body-row on 'NaN' margin-left error. ([2d4a85c5](https://github.com/material-table-core/core/commit/2d4a85c5e605a18484965c2364630b74b906855c))
- Hook edit cell up to validate ([88bb78f0](https://github.com/material-table-core/core/commit/88bb78f01da564d57f6432414644088aa56292da))
- Fallback for change of columns ([d4302655](https://github.com/material-table-core/core/commit/d4302655e5af87cb07e15f2b581772628d238b80))
- PRevent column width to be set in stone it not resizing ([6c430c53](https://github.com/material-table-core/core/commit/6c430c53729d72fb0c4e214bb4f036570fecf4a2))
- Set width of columns without mutations ([4e08c89a](https://github.com/material-table-core/core/commit/4e08c89ac4ee7452a62db9aa2dd8cc4519a7fba5))
- Fixed EditComponentProps ([04282538](https://github.com/material-table-core/core/commit/042825383b2a9d16845dc3b1e757695393839ff5))
- remove equality check on data prop function when remote data is true, no sense to check for that ([cfd8f2d4](https://github.com/material-table-core/core/commit/cfd8f2d47ea069af4497febbf5b6e67401f306fc))
- remove tableData property from column in check phase ([56565225](https://github.com/material-table-core/core/commit/565652251df3a2ea7c73382e391eec0c35a36700))
- add page, totalCount to props ([0a0f07a2](https://github.com/material-table-core/core/commit/0a0f07a21312f3ebb765a1c92db0ed703dd11c0f))
- export data with lookup values ([47eba169](https://github.com/material-table-core/core/commit/47eba16971b053f202255b368af3d5c6cc1a68c1))
- **actions-header:** Do not force textAlign ([#375](https://github.com/material-table-core/core/pull/375)) ([356a0555](https://github.com/material-table-core/core/commit/356a0555681fecfaff4d83c7f4a0a3b3b6c0f1a7))
- **MTableRow:** dont override enter on button elements ([5387af47](https://github.com/material-table-core/core/commit/5387af47f90e52854247de2c7b1851da5c378d8f))
- **DataManager:** set new groupsIndex in sortData() ([9a51e314](https://github.com/material-table-core/core/commit/9a51e31476fb381295286b74311cd095fd5b3d05))
- **typings:**
  - added missing totalCount type on Query interface ([c11febb0](https://github.com/material-table-core/core/commit/c11febb04a173a378af65e41147b2b41725562c4))
  - added missing 'width' type on Column interface ([63d0ae60](https://github.com/material-table-core/core/commit/63d0ae606122ca13cb3d55c10f3c046abd7de730))
- **editComponent:** add missing onRowDataChange type declaration ([605b95a7](https://github.com/material-table-core/core/commit/605b95a78c565685998cec8456f873f528498e07))
- **types:** change void to any for promises return on editable callbacks ([3457e5b6](https://github.com/material-table-core/core/commit/3457e5b68efcd02ca5e0477c52db1c7e2f1d2749))
- **table filter:** add key to TableCell for action column ([49593494](https://github.com/material-table-core/core/commit/4959349452968e00800abda2006f5d273887931c))

##### Other Changes

- check for localStorage for SSR ([ce738354](https://github.com/material-table-core/core/commit/ce738354563e3bbf9b5ba63c5adf60f28cf9801c))
- //github.com/material-table-core/core ([b8023ead](https://github.com/material-table-core/core/commit/b8023ead8f63d8887bee31474a4845d7a2afd2c0))
- do not fail on hidden columns dragging ([5966ee37](https://github.com/material-table-core/core/commit/5966ee373e88836e7f47f266af6da314f9ad88ad))
- //github.com/material-table-core/core ([c13b88a4](https://github.com/material-table-core/core/commit/c13b88a45aa7d6a33d275da2c869a76074aae8a0))
- add missing idSynonym ([027becc8](https://github.com/material-table-core/core/commit/027becc8a56628697ca033ecee71269226adde16))
- //github.com/material-table-core/core ([2d1da8d0](https://github.com/material-table-core/core/commit/2d1da8d01a86e6dbbc4fb5be100464097492f960))
- improve exports to only export correct data ([a8644bc3](https://github.com/material-table-core/core/commit/a8644bc31acf3ff26af59d357bea1cddaa839ec8))
- //github.com/material-table-core/core ([33fffdf3](https://github.com/material-table-core/core/commit/33fffdf38e0e755f1ac59db63913a3c1dac40508))
- //github.com/material-table-core/core ([f017eeca](https://github.com/material-table-core/core/commit/f017eeca328f228454a90e81345d8ec00a20494d))
- //github.com/material-table-core/core ([1f5638f5](https://github.com/material-table-core/core/commit/1f5638f58f6f79234ead098ffb4313117c32b3d6))
- //github.com/material-table-core/core ([9245d2ff](https://github.com/material-table-core/core/commit/9245d2ff602e4444ac4c4b842dcee525254c9ec4))
- //github.com/material-table-core/core ([51682e8d](https://github.com/material-table-core/core/commit/51682e8d07ba07f5823b99efeacfbfbdfef9fecb))
- //github.com/material-table-core/core ([b316bf31](https://github.com/material-table-core/core/commit/b316bf319dc8c6aa26c06062cf5e723d404c0ad0))
- rename handler ([d97e81e9](https://github.com/material-table-core/core/commit/d97e81e9d48a9ac454da193483e1a7e4dcba717f))
- build clean up comments ([0bb41291](https://github.com/material-table-core/core/commit/0bb41291f83a737b884fca1c9de5dcced7ea0c22))
- //github.com/material-table-core/core ([c2566924](https://github.com/material-table-core/core/commit/c25669242a9d0f160f9782a4787796520c205a45))
- build fix esbuild issues ([d37ff606](https://github.com/material-table-core/core/commit/d37ff606dcdd3a79ab66e0306b1fa235dde61154))
- //github.com/material-table-core/core ([72fbd53d](https://github.com/material-table-core/core/commit/72fbd53d6d9cdc9249d199279384c234b0f9ca7a))
- //github.com/material-table-core/core ([3f31e92e](https://github.com/material-table-core/core/commit/3f31e92ed35b7812aa8f7e5cc8c0a8810e4b1066))
- build add demo ([0f2a7e3a](https://github.com/material-table-core/core/commit/0f2a7e3ac9c30200c79aad7e2fd33c8357d886d9))
- build remove exporters from files ([6ec1a476](https://github.com/material-table-core/core/commit/6ec1a4767a6e9a000f2e4a140d383f082ab0c3e9))
- //github.com/material-table-core/core ([eef03a06](https://github.com/material-table-core/core/commit/eef03a063b0fd446433943bfcb774bc6cce2dae4))
- //github.com/material-table-core/core ([7dbd7a4b](https://github.com/material-table-core/core/commit/7dbd7a4b75b38ea180bdce8e8d973eae888c0e94))
- keep tabledata from previous columns ([e0fa5ee0](https://github.com/material-table-core/core/commit/e0fa5ee0dd480610022a14b02ff65a8c55b38ddd))
- build testing ([d8174194](https://github.com/material-table-core/core/commit/d817419456f40a54d1e8e72a62f724feddc2816e))
- build testing ([0a8cf7b0](https://github.com/material-table-core/core/commit/0a8cf7b0558acaa57b07a4137d8fb4781b6ea580))
- build update build.yml ([7b9d3cf3](https://github.com/material-table-core/core/commit/7b9d3cf3eeaf85ec6d52519609d8d88dc78b2681))
- build testing ([797344ab](https://github.com/material-table-core/core/commit/797344abc647d73837d9f95213f6a32330718cb1))
- build update build yml; test if skip build still works ([422d09bf](https://github.com/material-table-core/core/commit/422d09bf98ce9a04ffd6e5a008d96f8c93245b7d))
- build update build yml ([12367e66](https://github.com/material-table-core/core/commit/12367e660f068ccdad72a8368b62a7115459506a))
- build update build.yml ([af77c277](https://github.com/material-table-core/core/commit/af77c277e0e6718be417a0ec0fd86829902455d1))
- build update readme ([1fb439b6](https://github.com/material-table-core/core/commit/1fb439b698e887bfaa39099e4ab8299fa470d163))
- build update readme ([dfc74a89](https://github.com/material-table-core/core/commit/dfc74a8994701b91459df3ac6e42ba72c8a633b2))
- build ([8b5925fc](https://github.com/material-table-core/core/commit/8b5925fc60b90e1edf7afba147e4e11c55a40a37))
- Align title with columns ([db85a061](https://github.com/material-table-core/core/commit/db85a061487a5cfd4af61570a02f5a34eef7cd65))
- //github.com/material-table-core/core ([2dcf3f8a](https://github.com/material-table-core/core/commit/2dcf3f8a661f7359140ff87607551aa12168aedb))
- //github.com/material-table-core/core ([5e9ec31b](https://github.com/material-table-core/core/commit/5e9ec31ba826ef167602b2e2a3503ec8afddab85))
- missing colSpan prop for MTableCell ([d80830eb](https://github.com/material-table-core/core/commit/d80830eb15bca1d5edc4d0c5d8841b09b2461d75))
- //github.com/MrWittman612/core into MrWittman612-Refactor-MTableActions-class-to-functional-component ([0c4961f9](https://github.com/material-table-core/core/commit/0c4961f9655bceeb91fdf9e5bdcf9f01f66874c1))
- //github.com/material-table-core/refactor-material-table ([771674d6](https://github.com/material-table-core/core/commit/771674d6c7478fbf26c40b47c22f5595192fa5ba))
- //github.com/mbrn/material-table into feature-column-resizing ([ace4adec](https://github.com/material-table-core/core/commit/ace4adecc0e272e884772c81fdef6e172bd002b8))
- //github.com/floAr/material-table" ([a79fa7ee](https://github.com/material-table-core/core/commit/a79fa7ee80b9558c9005e46cfd6b186cded7cc2a))
- //github.com/floAr/material-table ([e499fd2a](https://github.com/material-table-core/core/commit/e499fd2a990331e4bad383fe5e0332f25ec616a8))
- //github.com/floAr/material-table ([572885b4](https://github.com/material-table-core/core/commit/572885b45d5da69d15669b0662da1477cf9a439e))
- Cannot find name 'RowData' ([9f1e3cf1](https://github.com/material-table-core/core/commit/9f1e3cf1113d8c5d8c7b074e63e764183a87a5f8))
- //github.com/floAr/material-table ([d51e1406](https://github.com/material-table-core/core/commit/d51e14062cd4a99e3e4e9930d4ebcba81b367c7f))
- //github.com/mbrn/material-table ([700b6111](https://github.com/material-table-core/core/commit/700b611186c4fa2ac3d478fa43630887c0317112))
- //github.com/Domino987/material-table into prettier ([1726cfe6](https://github.com/material-table-core/core/commit/1726cfe6b7c2a3ef656fc8ce445bbff04dcc47fd))
- onRowAddCancelled and onRowUpdateCancelled has been added ([1ecf3c07](https://github.com/material-table-core/core/commit/1ecf3c0774427be93f70ed1320224ba6dc283048))
- broken isEditable and isDeletable options ([d6e9e7b5](https://github.com/material-table-core/core/commit/d6e9e7b56df42e72cef9391f541a034b69f5c92b))
- marginTop in TableFilterRow ([57aa5d32](https://github.com/material-table-core/core/commit/57aa5d327992ef857089fc9333757420ba37d76e))
- //github.com/mbrn/material-table ([44b60bb7](https://github.com/material-table-core/core/commit/44b60bb71513b40073a531e265127883091424d3))
- action icon can be a string, function or Component ([fe283a5e](https://github.com/material-table-core/core/commit/fe283a5eefd60a3f7e6b08c47f83f92fba9ba24f))
- //github.com/ryanintulsa/material-table into ryanintulsa-dragAndDropWithHiddenColsFix ([a7b683f6](https://github.com/material-table-core/core/commit/a7b683f6db6d41a31ac13197b431d91ee572899c))
- prevent actions icons re-render ([5e133cf6](https://github.com/material-table-core/core/commit/5e133cf6bf8045745316b5f073200b76c3938c3c))
- //github.com/mbrn/material-table/pull/1205#issuecomment-544285507 ([b4b62ebc](https://github.com/material-table-core/core/commit/b4b62ebc80698dc0a6ecc3a98e8544f8d8b5668d))
- //github.com/martin-pepgit/material-table into martin-pepgit-issue_968 ([961df05e](https://github.com/material-table-core/core/commit/961df05e3b5ebf34ba57ae1e4cd9981a20783b3c))
- //github.com/mbrn/material-table/issues/932 ([a09d1696](https://github.com/material-table-core/core/commit/a09d1696c4480a3c6fff41ba98d429d823ba2cea))
- true ([a9a50f72](https://github.com/material-table-core/core/commit/a9a50f72b278f433fd549195e851b270add38f08))
- reuse defaultExpanded option ([29ad4298](https://github.com/material-table-core/core/commit/29ad4298e9dcfe31c562319009d9ba9a6ea86b78))
- //github.com/martin-pepgit/material-table into martin-pepgit-issue_945 ([9496ff75](https://github.com/material-table-core/core/commit/9496ff75dcb5454ea4b31901d04494970124a187))
- //github.com/emrekara37/material-table into emrekara37-tooltip-position ([c9b05535](https://github.com/material-table-core/core/commit/c9b055358ce38bb1a78f76d10befd2255ea83cc2))
- Header checkbox is not working properly when grouping is enabled ([59f28e43](https://github.com/material-table-core/core/commit/59f28e4319a0a810c2d8725b114df9d49a6e1ea7))
- //github.com/KATT/material-table into KATT-fix-row-onclick-typedefs ([cfaba4f8](https://github.com/material-table-core/core/commit/cfaba4f83b98ed48ae9c4ae8b27effc848169355))
- //github.com/emrekara37/material-table into emrekara37-override-sortarrow-icon ([9d2b7467](https://github.com/material-table-core/core/commit/9d2b74670740647064f7acd56f55c47a0932b982))
- //github.com/theodore-koch/material-table into theodore-koch-feat/add-level-to-functional-rowStyle ([6a32389a](https://github.com/material-table-core/core/commit/6a32389ad572d44aa28d9d4861351f54e32dd0b8))
- //github.com/Paktusin/material-table into Paktusin-master ([02712ce1](https://github.com/material-table-core/core/commit/02712ce1ba4040cd99e50688785ae40b41466c65))
- use callback after state is set ([f9a6e83a](https://github.com/material-table-core/core/commit/f9a6e83a825717eeaf895ce799ca5baaae0a7311))
- use callback after state is set ([12c1bd00](https://github.com/material-table-core/core/commit/12c1bd00dc0d735018b00afee3b0ead2372501b8))
- //github.com/mbrn/material-table ([d37bf4c5](https://github.com/material-table-core/core/commit/d37bf4c585f7c0cc559b78601ef9d0576cb587e0))
- //github.com/MaxLeiter/material-table into MaxLeiter-patch-1 ([543bb407](https://github.com/material-table-core/core/commit/543bb407cfc27ec65f073bb9bec97b912014499c))
- //github.com/yzhbankov/material-table into yzhbankov-filter-placeholder-fix ([ec2fad86](https://github.com/material-table-core/core/commit/ec2fad86f64829e6c94063462e848f0b78603376))
- Warnings when options.paginationType == 'stepped' ([f4e7c696](https://github.com/material-table-core/core/commit/f4e7c6962c42e874a0b136bed105918fbcfe0022))
- //github.com/gianlucamateo/material-table into gianlucamateo-bug/treeSearch ([cbf87104](https://github.com/material-table-core/core/commit/cbf87104da323681f008323facf4641be1834033))
- //github.com/AndySeymour2904/material-table into AndySeymour2904-iss708 ([ea30f04a](https://github.com/material-table-core/core/commit/ea30f04a4409ec14ddc98ee325236b624ed84366))
- //github.com/AugustoCalaca/material-table into AugustoCalaca-feature/placeholder-filtering ([768576fa](https://github.com/material-table-core/core/commit/768576fa523835940e0f7430bf863fc4e64c0fa0))
- //github.com/gianlucamateo/material-table into gianlucamateo-feature/customRowPadding ([3c60e815](https://github.com/material-table-core/core/commit/3c60e81584094e83f8b9eee76318dc4edc1daf7a))
- //github.com/mbrn/material-table ([eccb1e85](https://github.com/material-table-core/core/commit/eccb1e857bcbbda3317d4079f08fa487428a1901))
- Returning the row Data was checked and it is available in onSelectionChange ([fcba9f95](https://github.com/material-table-core/core/commit/fcba9f9510cf3f9dea6e87171acc9a6aa5e8d2c5))
- //github.com/mbrn/material-table ([50d9325a](https://github.com/material-table-core/core/commit/50d9325a566295684615181b1320d884f2544a1b))
- //github.com/truongtv22/material-table into bug/display-2-searchbox ([23ece5a1](https://github.com/material-table-core/core/commit/23ece5a12c7b9c1cde46aa62120642cb13254749))
- //github.com/truongtv22/material-table into bug/edit-child-rows ([15a7cb98](https://github.com/material-table-core/core/commit/15a7cb98fabf3b30ea2c867ba3a3bbca571efe78))
- //github.com/rssluca/material-table into rssluca-master ([b2bca2a8](https://github.com/material-table-core/core/commit/b2bca2a87cd37c93f066eaf54d7a6646a693a5f9))
- //github.com/truongtv22/material-table into truongtv22-feature-option-expand-all-rows ([ca63e47f](https://github.com/material-table-core/core/commit/ca63e47fb7572ee06786525dc816245f968c39c0))
- //github.com/rssluca/material-table into rssluca-master ([3081523b](https://github.com/material-table-core/core/commit/3081523b8298e8482c0e8a96f33863c40f13a8ed))
- //github.com/mbrn/material-table ([f8920251](https://github.com/material-table-core/core/commit/f89202513638534e0560a04e97ed4363fcb0154d))
- Cannot read property isExpanded of undefined ([77c1c1e8](https://github.com/material-table-core/core/commit/77c1c1e89f464fc98a9fbd118ed8977a42e90cae))
- find by path was not working after paging ([1422f1ad](https://github.com/material-table-core/core/commit/1422f1ad6ceffdb624f05a90afc6f686834562e0))
- //github.com/mbrn/material-table ([2cd32c82](https://github.com/material-table-core/core/commit/2cd32c82bf75114d4fd7e08330156da1dbe8cc7e))
- //github.com/mbrn/material-table ([4019e127](https://github.com/material-table-core/core/commit/4019e1277bd4fae55c2bb1d3150cbc2df337b9f7))
- //github.com/mbrn/material-table into mbrn-master ([434d196b](https://github.com/material-table-core/core/commit/434d196be65762977ab622665059f388c7642cf0))
- //github.com/mbrn/material-table ([140b9cd9](https://github.com/material-table-core/core/commit/140b9cd952133277ac843a82e2cc972a8dbc6800))
- This closes [#38](https://github.com/material-table-core/core/pull/38), actions columns rendering problem was solved ([e337135e](https://github.com/material-table-core/core/commit/e337135e9881780d3057372d9a4fc8d0376361ee))
- free actions was not rendering when columns buttons disabled ([42eec9b4](https://github.com/material-table-core/core/commit/42eec9b40aaf319ac9f18cd9fa3fa63ca0d44cd5))
- Free actions added ([450ff197](https://github.com/material-table-core/core/commit/450ff197b122f758ab16b82dc17c1440ecebcb48))
- Horizontal scroll set to only table content, except header and footer ([db92b353](https://github.com/material-table-core/core/commit/db92b3536a3c247d13228bc75c3687328866fa8b))
- action disabled property added ([10ac40af](https://github.com/material-table-core/core/commit/10ac40afcbe413d730ace2bbd3485c12455159c7))
- This closes [#33](https://github.com/material-table-core/core/pull/33) ([e99ee76e](https://github.com/material-table-core/core/commit/e99ee76e7cd9c6cdad8ea3838889f4a25732cc63))
- This closes [#31](https://github.com/material-table-core/core/pull/31), action buttons new line problem solved ([c982d0b4](https://github.com/material-table-core/core/commit/c982d0b498e1e634c9732395be6121e724faeae0))
- //github.com/mbrn/material-table ([cda25533](https://github.com/material-table-core/core/commit/cda25533802f858545d0dbda036a2cf345428225))
- **check:** possibility to load already checked rows" ([c1c7c117](https://github.com/material-table-core/core/commit/c1c7c11743001eb04db3823afe4c5af713a0249d))

##### Refactors

- omit one `Omit` ([#463](https://github.com/material-table-core/core/pull/463)) ([d99d551d](https://github.com/material-table-core/core/commit/d99d551dee04ceb0ebdc165c0b4aaad42b49e28c))
- create MTableCustomIcon component ([b1f8e617](https://github.com/material-table-core/core/commit/b1f8e617da0aab725dc8638189950a7d5c506ee3))
- support for mui 4.12 ([ef81cb73](https://github.com/material-table-core/core/commit/ef81cb736e6224a4a9190ceb176d7398ce7171cd))
- cleanup unused imports ([e3cc8fba](https://github.com/material-table-core/core/commit/e3cc8fbae6eb4a979b72e8392f6f0a8b7336e8d2))
- persist an array instead of object ([5bf5e92a](https://github.com/material-table-core/core/commit/5bf5e92ad9a90fb8c951f5ba6780dc1a777b6078))
- MTableBodyRow component added ([73ed3771](https://github.com/material-table-core/core/commit/73ed3771ba085425798b4fd89108cb7c13ce57d1))
- m-table-body component created and used by main component ([5adfc68a](https://github.com/material-table-core/core/commit/5adfc68aed6c98cf0e87ed7292295b455dd46235))

#### 4.3.44 (2022-05-19)

##### New Features

- be able to adjust pagination position using flex ([c262a95f](https://github.com/material-table-core/core/commit/c262a95f7bc5607038e85a1765d6c22cf028419a))
- move to @react-forked/dnd ([0d4b020f](https://github.com/material-table-core/core/commit/0d4b020fdc23727f380ce811ab99e6273af833aa))

##### Other Changes

- check for localStorage for SSR ([ce738354](https://github.com/material-table-core/core/commit/ce738354563e3bbf9b5ba63c5adf60f28cf9801c))
- //github.com/material-table-core/core ([b8023ead](https://github.com/material-table-core/core/commit/b8023ead8f63d8887bee31474a4845d7a2afd2c0))

#### 4.3.43 (2022-04-25)

##### Other Changes

- do not fail on hidden columns dragging ([5966ee37](https://github.com/material-table-core/core/commit/5966ee373e88836e7f47f266af6da314f9ad88ad))

#### 4.3.42 (2022-04-21)

##### Bug Fixes

- adjust current page to display detailpanel for remote data ([bcbb53ba](https://github.com/material-table-core/core/commit/bcbb53ba3db386b6ec3c8182b27fa33f44df1686))

#### 4.3.41 (2022-04-18)

#### 4.3.40 (2022-04-18)

##### Bug Fixes

- hidden columns resizing now works for correct col ([080ce82d](https://github.com/material-table-core/core/commit/080ce82d00332da7bec55db35c13af9afaa992fa))
- correct index for hidden column drag ([febedb34](https://github.com/material-table-core/core/commit/febedb347a84a43873d588ba5d68344ccc731f0f))

#### 4.3.39 (2022-04-01)

- fix pagination for small screens #524 ([746740e](https://github.com/material-table-core/core/commit/746740e4656021f3f2a55937f367eb7f9a1520fc))

#### 4.3.38 (2022-03-19)

##### New Features

- add index to tableData ([8187c0fd](https://github.com/material-table-core/core/commit/8187c0fd36c3aa2dd451ce36e23b84cff2988009))

#### 4.3.37 (2022-03-19)

##### New Features

- add sortDirection to customSort ([23b02f1f](https://github.com/material-table-core/core/commit/23b02f1f7ab8bc47e56f50bb450799a485150422))

#### 4.3.36 (2022-03-08)

##### Bug Fixes

- background shadow breaks for fixed columns ([#503](https://github.com/material-table-core/core/pull/503)) ([02543a52](https://github.com/material-table-core/core/commit/02543a521863c0f4f6305fe882fae5ac09078e53))

#### 4.3.35 (2022-03-06)

#### 4.3.34 (2022-03-06)

##### New Features

- keep detail panel open on rerender ([a881c1b8](https://github.com/material-table-core/core/commit/a881c1b8d9a3729d86e00643e3d513dc419ab47a))

#### 4.3.33 (2022-03-06)

##### Bug Fixes

- edit mode with fixed columns breaks table layout ([#498](https://github.com/material-table-core/core/pull/498)) ([58cdfa45](https://github.com/material-table-core/core/commit/58cdfa45638b386b18aca8b4cffc8775900640d2))

#### 4.3.32 (2022-02-26)

##### New Features

- Rows cannot be clicked while editing ([96afa7d2](https://github.com/material-table-core/core/commit/96afa7d2236fd00768b9037ad850f0d6a2f8ec44))

##### Bug Fixes

- show dragging header text on drag ([479b7532](https://github.com/material-table-core/core/commit/479b7532d263a2b9f2069dc7d449316e00970c86))

##### Other Changes

- //github.com/material-table-core/core ([c13b88a4](https://github.com/material-table-core/core/commit/c13b88a45aa7d6a33d275da2c869a76074aae8a0))

#### 4.3.31 (2022-02-14)

##### Other Changes

- add missing idSynonym ([027becc8](https://github.com/material-table-core/core/commit/027becc8a56628697ca033ecee71269226adde16))

#### 4.3.30 (2022-02-13)

##### New Features

- A key to override the default `id` tag to persist state between rerenders ([5a7d2b35](https://github.com/material-table-core/core/commit/5a7d2b3516c5347dcec1d389734a9ae33db47dca))

#### 4.3.29 (2022-02-10)

#### 4.3.28 (2022-02-10)

##### Bug Fixes

- column sort works for hidden ([b32d3bd3](https://github.com/material-table-core/core/commit/b32d3bd37c9179df2390454fd5add358bc7010ed))

##### Other Changes

- //github.com/material-table-core/core ([2d1da8d0](https://github.com/material-table-core/core/commit/2d1da8d01a86e6dbbc4fb5be100464097492f960))
- improve exports to only export correct data ([a8644bc3](https://github.com/material-table-core/core/commit/a8644bc31acf3ff26af59d357bea1cddaa839ec8))

#### 4.3.27 (2022-01-31)

##### New Features

- export additional data for export func ([abf09a4e](https://github.com/material-table-core/core/commit/abf09a4eaf50269230b3db7ae800908a430d2155))

#### 4.3.26 (2022-01-30)

##### New Features

- export filtred data for exportFunc ([052b7871](https://github.com/material-table-core/core/commit/052b78716addffa4c4fc9cc3caf5dae761008c04))

##### Bug Fixes

- dispaly header for sorting false and grouping true ([80cbd95b](https://github.com/material-table-core/core/commit/80cbd95bbbb9f56f84376c462dd0e97a64414d24))

#### 4.3.25 (2022-01-29)

##### New Features

- Update prop types for table cell ref ([105a2dbd](https://github.com/material-table-core/core/commit/105a2dbd97e280995bf17677a8d2fd2363b75a10))

##### Bug Fixes

- RenderSortButton renders content correctly ([5faa47cb](https://github.com/material-table-core/core/commit/5faa47cb3562208e5cbf4d52a7ec3cbbebe876c6))
- Check for null summary row value ([3e93e915](https://github.com/material-table-core/core/commit/3e93e9156fdd335da5ddd955c7ac459c42503341))
- [#455](https://github.com/material-table-core/core/pull/455) Use proper detailPanel callback signature when detailPanel is an array of callbacks ([#468](https://github.com/material-table-core/core/pull/468)) ([b6ae7bc2](https://github.com/material-table-core/core/commit/b6ae7bc2ef0997c966c17119679f3024461779bc))

##### Other Changes

- //github.com/material-table-core/core ([33fffdf3](https://github.com/material-table-core/core/commit/33fffdf38e0e755f1ac59db63913a3c1dac40508))

#### 4.3.24 (2022-01-27)

##### New Features

- Improve renderSummaryRow ([756d225f](https://github.com/material-table-core/core/commit/756d225f45bc763e3d2faee46ffb3ed8779f29cc))

##### Other Changes

- //github.com/material-table-core/core ([f017eeca](https://github.com/material-table-core/core/commit/f017eeca328f228454a90e81345d8ec00a20494d))

#### 4.3.23 (2022-01-25)

##### Bug Fixes

- Add sorting icon for draggable false ([c7918619](https://github.com/material-table-core/core/commit/c791861932ac09fbcd8bb269019645c2cb5601cc))

#### 4.3.22 (2022-01-22)

##### Bug Fixes

- extract the correct value for select edit cell ([3f681ba3](https://github.com/material-table-core/core/commit/3f681ba36d8daa36fbeaa5386a387787aff8afae))

#### 4.3.21 (2022-01-22)

##### Other Changes

- //github.com/material-table-core/core ([1f5638f5](https://github.com/material-table-core/core/commit/1f5638f58f6f79234ead098ffb4313117c32b3d6))

#### 4.3.20 (2022-01-22)

##### Bug Fixes

- autofocus of edit rows ([77107104](https://github.com/material-table-core/core/commit/771071044bd4ff38fa1a9e5b2b93f27dc33b9bd3))

##### Refactors

- omit one `Omit` ([#463](https://github.com/material-table-core/core/pull/463)) ([d99d551d](https://github.com/material-table-core/core/commit/d99d551dee04ceb0ebdc165c0b4aaad42b49e28c))

#### 4.3.19 (2022-01-21)

#### 4.3.18 (2022-01-09)

#### 4.3.17 (2022-01-09)

#### 4.3.16 (2021-12-31)

#### 4.3.15 (2021-12-21)

##### Bug Fixes

- [#441](https://github.com/material-table-core/core/pull/441) ([#443](https://github.com/material-table-core/core/pull/443)) ([ca3e4ee0](https://github.com/material-table-core/core/commit/ca3e4ee056e5b3d33254759426f5ada143710c1f))

#### 4.3.14 (2021-12-21)

##### Bug Fixes

- [#437](https://github.com/material-table-core/core/pull/437) ([#440](https://github.com/material-table-core/core/pull/440)) ([a9e65aac](https://github.com/material-table-core/core/commit/a9e65aaca4d47533482267cf0f948716ab48d65e))

#### 4.3.13 (2021-12-21)

##### Bug Fixes

- [#437](https://github.com/material-table-core/core/pull/437) ([#440](https://github.com/material-table-core/core/pull/440)) ([a9e65aac](https://github.com/material-table-core/core/commit/a9e65aaca4d47533482267cf0f948716ab48d65e))

#### 4.3.13 (2021-12-21)

##### Bug Fixes

- [#437](https://github.com/material-table-core/core/pull/437) ([#440](https://github.com/material-table-core/core/pull/440)) ([a9e65aac](https://github.com/material-table-core/core/commit/a9e65aaca4d47533482267cf0f948716ab48d65e))

#### 4.3.12 (2021-12-19)

- Improve resiliance of UUID lookup ([8932e17267d830ce15ea4344c67bba316202b04b](https://github.com/material-table-core/core/commit/8932e17267d830ce15ea4344c67bba316202b04b) and [089917160b200179d9b2ace6e65c3402f74ad08a](https://github.com/material-table-core/core/commit/089917160b200179d9b2ace6e65c3402f74ad08a))
- Re-use column definitions in reorder logic ((1cae2379e7b6830b1a2af83e73751af76b1cf4c3)[https://github.com/material-table-core/core/commit/1cae2379e7b6830b1a2af83e73751af76b1cf4c3])
- Separate state for controlled vs. uncontrolled input warnings per [React FAQ](https://reactjs.org/docs/hooks-faq.html#should-i-use-one-or-many-state-variables) ([8ea10b5901f1da4b081775377798231692d49e5b](https://github.com/material-table-core/core/commit/8ea10b5901f1da4b081775377798231692d49e5b)).
- Improve detection of row hover events ([62117c548e1a4d29fa9863830a5a8839ba4727e8](https://github.com/material-table-core/core/commit/62117c548e1a4d29fa9863830a5a8839ba4727e8))

#### 4.3.11 (2021-11-20)

##### Chores

- update package.lock ([d724c7ef](https://github.com/material-table-core/core/commit/d724c7ef6f5daffa8bdbe94749a9215f1b4902b9))

##### Other Changes

- //github.com/material-table-core/core ([9245d2ff](https://github.com/material-table-core/core/commit/9245d2ff602e4444ac4c4b842dcee525254c9ec4))

#### 4.3.11 (2021-11-16)

#### 4.3.10 (2021-11-13)

#### 4.3.10 (2021-11-13)

#### 4.3.10 (2021-11-13)

#### 4.3.10 (2021-11-13)

#### 4.3.10 (2021-11-13)

### 4.4.0 (2021-11-13)

#### 4.3.9 (2021-11-03)

#### 4.3.8 (2021-11-01)

##### Bug Fixes

- prevent enter to save for invalid row ([905d5252](https://github.com/material-table-core/core/commit/905d525278a520755ee0367a13425f7dc8132e29))

#### 4.3.7 (2021-10-19)

##### Documentation Changes

- add error for pagination with old mui version ([0617b8e3](https://github.com/material-table-core/core/commit/0617b8e30bebb8ec9491b209a1c347c4cfeb669f))

##### Other Changes

- //github.com/material-table-core/core ([51682e8d](https://github.com/material-table-core/core/commit/51682e8d07ba07f5823b99efeacfbfbdfef9fecb))

#### 4.3.6 (2021-10-15)

##### Bug Fixes

- **actions-header:** Do not force textAlign ([#375](https://github.com/material-table-core/core/pull/375)) ([356a0555](https://github.com/material-table-core/core/commit/356a0555681fecfaff4d83c7f4a0a3b3b6c0f1a7))

##### Other Changes

- //github.com/material-table-core/core ([b316bf31](https://github.com/material-table-core/core/commit/b316bf319dc8c6aa26c06062cf5e723d404c0ad0))

#### 4.3.5 (2021-10-07)

#### 4.3.5 (2021-10-07)

#### 4.3.4 (2021-10-03)

#### 4.3.3 (2021-09-22)

#### 4.3.2 (2021-09-22)

##### New Features

- Add group selection. ([#343](https://github.com/material-table-core/core/pull/343)) ([479798c2](https://github.com/material-table-core/core/commit/479798c28f63fe9c46b5f07b711362aff8c8d30a))

##### Bug Fixes

- regression of optional detail panel function ([6d55e366](https://github.com/material-table-core/core/commit/6d55e3660aa869df555197f1cf8bbfdf33b15d7f))

#### 4.3.1 (2021-08-31)

##### Chores

- install babel module resolver ([092f8206](https://github.com/material-table-core/core/commit/092f82068e217744d4af881b243e77d9674f8ec4))
- add babel import aliases ([6105afd6](https://github.com/material-table-core/core/commit/6105afd6b4ffd20247003bb3b916633c049e2e2b))
- create MTableScrollbar ([07434b40](https://github.com/material-table-core/core/commit/07434b407f8b6dbe102746c9bb8a6e1869f6396c))

##### New Features

- **MaterialTable:** aggregate gropuings in localStoarge under material-table-groupings refactor(MTableGroupbar): map groupings feat(MTableGroupbar): clean up local storage when groupings are deleted ([0dd33f20](https://github.com/material-table-core/core/commit/0dd33f20fb515a895d743d01e1dcbde1fe6fad8b))

##### Bug Fixes

- typos in comments and components ([cc2b40e3](https://github.com/material-table-core/core/commit/cc2b40e374bc424fe4cdc3f466f9dff9e340d277))

##### Refactors

- cleanup unused imports ([e3cc8fba](https://github.com/material-table-core/core/commit/e3cc8fbae6eb4a979b72e8392f6f0a8b7336e8d2))
- persist an array instead of object ([5bf5e92a](https://github.com/material-table-core/core/commit/5bf5e92ad9a90fb8c951f5ba6780dc1a777b6078))

### 4.3.0 (2021-08-07)

##### Bug Fixes

- transpiler issues, move back to babel ([20e9a1e7](https://github.com/material-table-core/core/commit/20e9a1e7b01a74ca128ba615b8d1af0328ec1ab9))

#### 4.2.3 (2021-08-06)

##### Chores

- remove chalk package ([fb817a42](https://github.com/material-table-core/core/commit/fb817a421c4852b55c123b14821669e5fd8ec6b1))

#### 4.2.2 (2021-08-06)

##### Chores

- fix formatting/spacing ([9a7eb079](https://github.com/material-table-core/core/commit/9a7eb07991ce933b06df21c6067dfcb6db66a88e))

##### New Features

- add type module to package.json and fix esbuild issues ([e44ce4f3](https://github.com/material-table-core/core/commit/e44ce4f3d37daa4373faf31962235673a5802b52))

##### Bug Fixes

- issue with jest and modules ([64842a9b](https://github.com/material-table-core/core/commit/64842a9b2d47bdbb63fb1513bdcfd390e12aab3a))

#### 4.2.1 (2021-08-05)

##### Bug Fixes

- delay in onRowClick ([6301b34d](https://github.com/material-table-core/core/commit/6301b34dc71d3994dcc22673fef1ff480f81bb8a))

### 4.2.0 (2021-08-05)

##### Breaking Changes

- rename `onDoubleRowClick` to `onRowDoubleClick` ([32a7f3ac](https://github.com/material-table-core/core/commit/32a7f3ac5f371d3e349e1d2790f325efaa3b3a48))

##### Chores

- fix typo ([cb798b72](https://github.com/material-table-core/core/commit/cb798b721fb5ea22e4dbb88563045a607a23cdc5))
- move MTableBodyRow to own directory ([4c5354f8](https://github.com/material-table-core/core/commit/4c5354f846ef653f3ce07370400f262114944b13))

##### Refactors

- create MTableCustomIcon component ([b1f8e617](https://github.com/material-table-core/core/commit/b1f8e617da0aab725dc8638189950a7d5c506ee3))

### 4.1.0 (2021-08-01)

##### Chores

- clean up how persisting row click events are handled ([d735ef84](https://github.com/material-table-core/core/commit/d735ef8423110d720c74ce6ed771f588cd1e0883))
- change to force consumers to override ([48a08aa3](https://github.com/material-table-core/core/commit/48a08aa35afcdf7afd67f22efdf7ab9f0d94ed0b))

##### Bug Fixes

- persist row click events, single and double click ([6337c3bf](https://github.com/material-table-core/core/commit/6337c3bfefaee356228426af74f7ac02da55567a))

##### Other Changes

- rename handler ([d97e81e9](https://github.com/material-table-core/core/commit/d97e81e9d48a9ac454da193483e1a7e4dcba717f))
- build clean up comments ([0bb41291](https://github.com/material-table-core/core/commit/0bb41291f83a737b884fca1c9de5dcced7ea0c22))

## 4.0.0 (2021-07-31)

##### Chores

- update tests to start testing pre and post build ([e9d57280](https://github.com/material-table-core/core/commit/e9d5728003677704d177e714e457703dfe99a6fb))
- change transpiler ([2d11d942](https://github.com/material-table-core/core/commit/2d11d9422743cdf479180d161507244bf603d3a8))

#### 3.2.5 (2021-07-29)

##### Bug Fixes

- issue when programmatically hiding a shown detail panel [#282](https://github.com/material-table-core/core/pull/282) ([4696507d](https://github.com/material-table-core/core/commit/4696507d7bf71d9dcaa0b0bfc733c5b973b39bf2))

#### 3.2.4 (2021-07-27)

#### 3.2.3 (2021-07-27)

#### 3.2.2 (2021-07-27)

##### Chores

- switch back to babel, still issues with esbuild ([b88892be](https://github.com/material-table-core/core/commit/b88892be20d7feb42013bcb3c474fe020e66d50d))

#### 3.2.1 (2021-07-27)

##### Chores

- use esbuild for transpiing instead of babel ([e8383429](https://github.com/material-table-core/core/commit/e8383429e0642f9a8081939cd2b09e8fb03d3c9b))

##### Other Changes

- //github.com/material-table-core/core ([c2566924](https://github.com/material-table-core/core/commit/c25669242a9d0f160f9782a4787796520c205a45))

### 3.2.0 (2021-07-27)

Fix issues with pagination/when we receive new data with the same ID. Our solution was to add an internal UUID prop for each row upon receiving new external data. Issue #272 has all you need to know

##### Other Changes

- build fix esbuild issues ([d37ff606](https://github.com/material-table-core/core/commit/d37ff606dcdd3a79ab66e0306b1fa235dde61154))

#### 3.1.2 (2021-07-26)

#### 3.1.1 (2021-07-26)

##### Other Changes

- //github.com/material-table-core/core ([72fbd53d](https://github.com/material-table-core/core/commit/72fbd53d6d9cdc9249d199279384c234b0f9ca7a))

### 3.1.0 (2021-07-19)

##### New Features

- detail npanel animation ([94a3a66e](https://github.com/material-table-core/core/commit/94a3a66ee8372dadd0b495e0a94bcf7e64de3014))
- add row id and provide telling warning for common errors ([39d5d35b](https://github.com/material-table-core/core/commit/39d5d35b77c22823a2da690d3de4ea9c6ac16031))

##### Other Changes

- //github.com/material-table-core/core ([3f31e92e](https://github.com/material-table-core/core/commit/3f31e92ed35b7812aa8f7e5cc8c0a8810e4b1066))

### 3.1.0 (2021-07-19)

##### New Features

- detail npanel animation ([94a3a66e](https://github.com/material-table-core/core/commit/94a3a66ee8372dadd0b495e0a94bcf7e64de3014))
- add row id and provide telling warning for common errors ([39d5d35b](https://github.com/material-table-core/core/commit/39d5d35b77c22823a2da690d3de4ea9c6ac16031))

##### Other Changes

- //github.com/material-table-core/core ([3f31e92e](https://github.com/material-table-core/core/commit/3f31e92ed35b7812aa8f7e5cc8c0a8810e4b1066))

### 3.1.0 (2021-07-19)

##### New Features

- detail npanel animation ([94a3a66e](https://github.com/material-table-core/core/commit/94a3a66ee8372dadd0b495e0a94bcf7e64de3014))
- add row id and provide telling warning for common errors ([39d5d35b](https://github.com/material-table-core/core/commit/39d5d35b77c22823a2da690d3de4ea9c6ac16031))

##### Other Changes

- //github.com/material-table-core/core ([3f31e92e](https://github.com/material-table-core/core/commit/3f31e92ed35b7812aa8f7e5cc8c0a8810e4b1066))

#### 3.0.18 (2021-07-19)

#### 3.0.17 (2021-07-14)

##### Other Changes

- build add demo ([0f2a7e3a](https://github.com/material-table-core/core/commit/0f2a7e3ac9c30200c79aad7e2fd33c8357d886d9))
- build remove exporters from files ([6ec1a476](https://github.com/material-table-core/core/commit/6ec1a4767a6e9a000f2e4a140d383f082ab0c3e9))

#### 3.0.16 (2021-07-08)

##### Chores

- add url ([1f3c56a3](https://github.com/material-table-core/core/commit/1f3c56a3fca0e31dc9c1f87c8355ec6f517b40c6))

##### Documentation Changes

- create branch of current version ([85df956a](https://github.com/material-table-core/core/commit/85df956a485829e56cef7f9aaa6d0881b6717ba9))

##### Refactors

- support for mui 4.12 ([ef81cb73](https://github.com/material-table-core/core/commit/ef81cb736e6224a4a9190ceb176d7398ce7171cd))

#### 3.0.15 (2021-07-08)

##### Chores

- add url ([1f3c56a3](https://github.com/material-table-core/core/commit/1f3c56a3fca0e31dc9c1f87c8355ec6f517b40c6))

##### Documentation Changes

- create branch of current version ([85df956a](https://github.com/material-table-core/core/commit/85df956a485829e56cef7f9aaa6d0881b6717ba9))

##### Refactors

- support for mui 4.12 ([ef81cb73](https://github.com/material-table-core/core/commit/ef81cb736e6224a4a9190ceb176d7398ce7171cd))

#### 3.0.14 (2021-07-07)

##### Bug Fixes

- Move duble click to syntheic events ([fcf963da](https://github.com/material-table-core/core/commit/fcf963da436f5520f518530e3632ad76b47155b2))
- Proptype fix for tabelcell ([101d2900](https://github.com/material-table-core/core/commit/101d2900b5ed280920d751248f51225d1380f1da))

#### 3.0.13 (2021-07-02)

##### Chores

- removla of wrong spreaded values of tablecell ([b4b04c6d](https://github.com/material-table-core/core/commit/b4b04c6dd53e14ff431b9cb3b840cb2013991e81))

##### New Features

- Add on row double click ([6158df3e](https://github.com/material-table-core/core/commit/6158df3e9d743ad01d9782826333660696cf05cf))

##### Bug Fixes

- only apply drag style if dragging ([04b538f0](https://github.com/material-table-core/core/commit/04b538f0de5aed16017ad8c8fc5b1bf5bb654163))
- Update m-table-body-row on 'NaN' margin-left error. ([2d4a85c5](https://github.com/material-table-core/core/commit/2d4a85c5e605a18484965c2364630b74b906855c))

##### Other Changes

- //github.com/material-table-core/core ([eef03a06](https://github.com/material-table-core/core/commit/eef03a063b0fd446433943bfcb774bc6cce2dae4))

#### 3.0.12 (2021-06-27)

##### Chores

- mrge edit cell validate fixes ([09e6487d](https://github.com/material-table-core/core/commit/09e6487d20d9e940ffd6bea6f1dc53842d2269a8))

#### 3.0.11 (2021-06-27)

##### Bug Fixes

- Hook edit cell up to validate ([88bb78f0](https://github.com/material-table-core/core/commit/88bb78f01da564d57f6432414644088aa56292da))

##### Other Changes

- //github.com/material-table-core/core ([7dbd7a4b](https://github.com/material-table-core/core/commit/7dbd7a4b75b38ea180bdce8e8d973eae888c0e94))
- keep tabledata from previous columns ([e0fa5ee0](https://github.com/material-table-core/core/commit/e0fa5ee0dd480610022a14b02ff65a8c55b38ddd))
- build testing ([d8174194](https://github.com/material-table-core/core/commit/d817419456f40a54d1e8e72a62f724feddc2816e))
- build testing ([0a8cf7b0](https://github.com/material-table-core/core/commit/0a8cf7b0558acaa57b07a4137d8fb4781b6ea580))
- build update build.yml ([7b9d3cf3](https://github.com/material-table-core/core/commit/7b9d3cf3eeaf85ec6d52519609d8d88dc78b2681))
- build testing ([797344ab](https://github.com/material-table-core/core/commit/797344abc647d73837d9f95213f6a32330718cb1))
- build update build yml; test if skip build still works ([422d09bf](https://github.com/material-table-core/core/commit/422d09bf98ce9a04ffd6e5a008d96f8c93245b7d))
- build update build yml ([12367e66](https://github.com/material-table-core/core/commit/12367e660f068ccdad72a8368b62a7115459506a))
- build update build.yml ([af77c277](https://github.com/material-table-core/core/commit/af77c277e0e6718be417a0ec0fd86829902455d1))

#### 3.0.10 (2021-06-26)

##### Other Changes

- build update readme ([1fb439b6](https://github.com/material-table-core/core/commit/1fb439b698e887bfaa39099e4ab8299fa470d163))

#### 3.0.9 (2021-06-26)

##### Other Changes

- build update readme ([dfc74a89](https://github.com/material-table-core/core/commit/dfc74a8994701b91459df3ac6e42ba72c8a633b2))
- build ([8b5925fc](https://github.com/material-table-core/core/commit/8b5925fc60b90e1edf7afba147e4e11c55a40a37))

#### 3.0.8 (2021-06-26)

#### 3.0.7 (2021-06-19)

##### Bug Fixes

- Fallback for change of columns ([d4302655](https://github.com/material-table-core/core/commit/d4302655e5af87cb07e15f2b581772628d238b80))

### 3.0.6 (2021-06-10)

##### Bug Fixes

- PRevent column width to be set in stone it not resizing ([6c430c53](https://github.com/material-table-core/core/commit/6c430c53729d72fb0c4e214bb4f036570fecf4a2))

##### Other Changes

- Align title with columns ([db85a061](https://github.com/material-table-core/core/commit/db85a061487a5cfd4af61570a02f5a34eef7cd65))

#### 3.0.5 (2021-06-08)

##### Other Changes

- //github.com/material-table-core/core ([2dcf3f8a](https://github.com/material-table-core/core/commit/2dcf3f8a661f7359140ff87607551aa12168aedb))

#### 3.0.4 (2021-06-08)

#### 3.0.3 (2021-06-08)

##### Documentation Changes

- Update readme ([3718162e](https://github.com/material-table-core/core/commit/3718162e8f504605e84df59c7e62fb51685329d1))

##### Other Changes

- //github.com/material-table-core/core ([5e9ec31b](https://github.com/material-table-core/core/commit/5e9ec31ba826ef167602b2e2a3503ec8afddab85))

#### 3.0.2 (2021-06-03)

#### 3.0.1 (2021-06-01)

##### Bug Fixes

- Set width of columns without mutations ([4e08c89a](https://github.com/material-table-core/core/commit/4e08c89ac4ee7452a62db9aa2dd8cc4519a7fba5))

## 3.0.0 (2021-05-29)

##### Breaking Changes

- **Prop Mutation:** The mutation of data and columns to add the tableData object was removed. This will remove the object reference for the callbacks as well, so that if you rely on object comparision to find your data, this will no longer work
  ([Breaking Changes](https://material-table-core.com/docs/breaking-changes)) ([Thread](https://github.com/mbrn/material-table/pull/1174)):

```
onRowClick={(event, clickedRow)=> {
    // Will now always return undefined because reference changed
    const existingRow = data.find(d => d === clickedRow)
}
```

Instead this works:

```
onRowClick={(event, clickedRow)=> {
    // Finding the object with an internal id/unique property
    const existingRow = data.find(d => d.id === clickedRow.id)
    // Accessing the index
    const existingRow = data[clickedRow.tableData.id]
}
```

##### Bug Fixes

- **MTableRow:** dont override enter on button elements ([5387af47](https://github.com/material-table-core/core/commit/5387af47f90e52854247de2c7b1851da5c378d8f))

#### 2.3.40 (2021-05-22)

#### 2.3.39 (2021-05-14)

- Resolve import typo https://github.com/material-table-core/core/commit/01999ef80d31dc575cab0aa91e1a395c9bc5a48a

#### 2.3.38 (2021-05-13)

#### 2.3.38 (2021-05-13)

#### 2.3.37 (2021-05-03)

##### Documentation Changes

- add changelog ([4b9af575](https://github.com/material-table-core/core/commit/4b9af5752e6fbdd22e3c14ba7abb3eacf0eaa04f))

#### 2.3.37 (2021-05-03)

##### Documentation Changes

- add changelog ([4b9af575](https://github.com/material-table-core/core/commit/4b9af5752e6fbdd22e3c14ba7abb3eacf0eaa04f))

#### 2.3.38 (2021-05-02)

##### Documentation Changes

- add changelog ([4b9af575](https://github.com/material-table-core/core/commit/4b9af5752e6fbdd22e3c14ba7abb3eacf0eaa04f))

#### 2.3.37 (2021-05-02)

##### Documentation Changes

- add changelog ([4b9af575](https://github.com/material-table-core/core/commit/4b9af5752e6fbdd22e3c14ba7abb3eacf0eaa04f))
