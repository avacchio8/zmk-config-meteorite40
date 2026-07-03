# Changelog

## [4.3.1](https://github.com/iwk7273/zmk-config-meteorite40/compare/v4.3.0...v4.3.1) (2026-07-03)


### 修正

* Meteorite Studio へ Bluetooth 経由で接続するための操作を、キー割り当てやコンボから選べるよう修正しました。 ([9659531](https://github.com/iwk7273/zmk-config-meteorite40/commit/96595318fbd86ba13b9f2bb970e9d9a5fd5f5bcf))

## 4.3.0 (2026-07-03)


### Features

* add Studio BLE discovery combo (Q+A+Z) and behavior include ([e064349](https://github.com/iwk7273/zmk-config-meteorite40/commit/e0643490f9a2cf4dd6695e783e29122e2aa8765a))
* **config:** add mixed encoder behaviors ([e2c86c3](https://github.com/iwk7273/zmk-config-meteorite40/commit/e2c86c3148237268aabcb3deaa3cf0cc2a2c3bf0))
* **config:** enable combo settings ([56dc629](https://github.com/iwk7273/zmk-config-meteorite40/commit/56dc6291d3ed3e45897c849abda00af466ac36c5))
* **config:** point meteorite firmware to rpc branches ([f8ad2c0](https://github.com/iwk7273/zmk-config-meteorite40/commit/f8ad2c0acf297ac798852221598292034f6cb0e0))
* **encoder:** expose encoder bindings as keymap slots ([baf3eff](https://github.com/iwk7273/zmk-config-meteorite40/commit/baf3eff3b0e4a9705ee2742843a509af25632916))
* **release:** report build version over RPC; automate releases ([b1b6bd0](https://github.com/iwk7273/zmk-config-meteorite40/commit/b1b6bd06bd9920f00443cb43cf2264c7855480cd))
* スクロール用 motion_scaler を追加 ([a3ca211](https://github.com/iwk7273/zmk-config-meteorite40/commit/a3ca211aada40f376806395f41a49feb590849f7))


### Bug Fixes

* **ball:** browser zoom via Ctrl/Cmd +=/- (consumer AC_ZOOM didn't work) ([1693884](https://github.com/iwk7273/zmk-config-meteorite40/commit/1693884082b63723a7090fd97b7c8903a2631a61))
* **ball:** default sensitivity macro to renumbered NORMAL (1-&gt;2) ([d5ce709](https://github.com/iwk7273/zmk-config-meteorite40/commit/d5ce7098b9c2d762e10668671b3e0180af6bea9e))
* **ball:** fill Mac no-op bindings for DESKTOP/WINDOW profiles ([b84bea4](https://github.com/iwk7273/zmk-config-meteorite40/commit/b84bea4b2d1805ece209428bd2e5483c0c174450))
* **ball:** restore DESKTOP DOWN to show-desktop toggle (LG(D)/F11) ([41edbc8](https://github.com/iwk7273/zmk-config-meteorite40/commit/41edbc89ce94673dcfe83764b84263fbbe66fbf5))
* **config:** add mixed low encoder behaviors ([22830ab](https://github.com/iwk7273/zmk-config-meteorite40/commit/22830ab70ffd056be2322d63a97b35b86d6ba090))
* **config:** enlarge Studio RPC buffers for combos ([973fcbb](https://github.com/iwk7273/zmk-config-meteorite40/commit/973fcbb31ba77ad2bef014a313b501c9935388b7))
* **config:** simplify encoder defaults ([dd1cfc9](https://github.com/iwk7273/zmk-config-meteorite40/commit/dd1cfc9529691b420721f77346bfca8b98d88a1a))
* **dt:** move ball_profile_defaults/custom_config_defaults out of #if CONFIG_ ([94d8d01](https://github.com/iwk7273/zmk-config-meteorite40/commit/94d8d018f8a6094e5a87bc8e728e85d804669540))
* increase Studio RPC TX buffer size for BLE transport ([6847cb4](https://github.com/iwk7273/zmk-config-meteorite40/commit/6847cb419f892cc97c3e1377f96f531ac3853fa8))
* increase Studio RPC TX buffer to 4096 for full layout response ([f646260](https://github.com/iwk7273/zmk-config-meteorite40/commit/f646260d08c7d468de5fcdcd28d52e366922764d))
* **studio:** set RPC TX buf to 512 alongside BLE streaming flush ([99a7907](https://github.com/iwk7273/zmk-config-meteorite40/commit/99a7907f540c545e6ad53516064149088e1433b5))


### Performance Improvements

* enable BLE DLE and larger MTU for Studio throughput ([c4df151](https://github.com/iwk7273/zmk-config-meteorite40/commit/c4df151a40080cc06483ebb771c4c98c908b9d39))


### Reverts

* **debug:** restore BLE profile test settings ([99ae7bf](https://github.com/iwk7273/zmk-config-meteorite40/commit/99ae7bfd81b78de04d977d702c1234e4f2dc829c))
