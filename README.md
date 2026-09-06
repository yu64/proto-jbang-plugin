# proto-jbang-plugin

A TOML plugin for managing JBang with proto.

JBang を管理する proto 用 TOML プラグインです。

## Usage / 使い方

Register the plugin, install JBang, and check its version:

プラグインを登録し、JBang をインストールしてバージョンを確認します。

```sh
proto plugin add jbang "https://raw.githubusercontent.com/yu64/proto-jbang-plugin/refs/heads/main/jbang.toml"
proto install jbang
jbang version
```
