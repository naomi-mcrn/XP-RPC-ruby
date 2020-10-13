XP-RPC-ruby
=====================

Usage
--------------------
```
 require './lib/xp'
 cli = XP::RPC::Client.new("user" => "rpcuser", "pass" => "rpcpassword")
 ret = cli.execrpc("getinfo")
```

本家Lex氏のnode版 (https://github.com/SOELexicon/node-ExperiencePoints) を強引にRuby移植。
とりあえず最小限動くだけ。煮るなり焼くなり好きにして。
