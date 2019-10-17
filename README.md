# zeek-scripting-style-guide
Style guide for Zeek scripts, as used by ESnet.

## Code Lay-out

### Indentation

Use 1 hard tab per indentation level.

### Tabs or Spaces?

Both. Tabs are for indenting code blocks, spaces are for aligning code. e.g.

```
policy/protocols/conn/known-services.zeek:<TAB>Log::create_stream(Known::SERVICES_LOG, [$columns=ServicesInfo,
policy/protocols/conn/known-services.zeek:<TAB><SPACE>...<SPACE>...<SPACE><SPACE><SPACE>$ev=log_known_services,
policy/protocols/conn/known-services.zeek:<TAB><SPACE>...<SPACE>...<SPACE><SPACE><SPACE>$path="known_services"]);
```
