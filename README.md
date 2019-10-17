# zeek-scripting-style-guide
Style guide for Zeek scripts, as used by ESnet.

## Code Lay-out

### Indentation

Use 1 hard tab per indentation level.

Justification: Scripts that ship with Zeek use hard tabs, by a count of 33,771 to 182.

### Tabs or Spaces?

Both. Tabs are for indenting code blocks, spaces are for aligning code. e.g.

Justification: Scripts that ship with Zeek use both, in this way. Additionally, when using hard tabs,
the alignment is off if spaces aren't used for alignment.

```
known-services.zeek:<TAB>Log::create_stream(Known::SERVICES_LOG, [$columns=ServicesInfo,
known-services.zeek:<TAB><SPACE>...<SPACE>...<SPACE><SPACE><SPACE>$ev=log_known_services,
known-services.zeek:<TAB><SPACE>...<SPACE>...<SPACE><SPACE><SPACE>$path="known_services"]);
```
