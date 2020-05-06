# What is this?

This is an experimental subset of Go that supports only webassembly.

Why a subset? Because as it stands, webassembly.  

Here are the planned features:

1. Remove GC and replace with reference counting
2. Remove shared global state (package vars)
3. Remove channels except where the item is value type
4. Each goroutine has a separate heap as well as stack

NB: this is just an experiment! Don't use it for anything serious.

Also note: I changed the license to AGPL to discourage use. If you
have a problem with this, open an issue and we can talk.
