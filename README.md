# datetime

Calendar dates + times. Owns the `DateTime` struct and the surrounding helpers: constructors (`now`, `from_unix`, `from_iso`, `make`, …), arithmetic on the struct (`add_seconds`, `diff_seconds`, `is

This package is also bundled with the Quirk compiler at
`<QUIRK_HOME>/packages/datetime/`, so `use datetime` works out of the box on a
fresh install. This repo is the canonical home — when you want a version
newer than the one your compiler shipped with, install it explicitly:

```bash
quirk pkg install datetime             # latest tag from this repo
quirk pkg install datetime@1.0.0       # pinned
```

The compiler-shipped registry maps the bare name `datetime` to this repo
(since v1.4.0), so no `quirk pkg registry add` is needed.

## Origin

Split from `quirk-compiler/packages/datetime/` in compiler v1.5.0 as part of
the stdlib-in-independent-repos rollout. Source history before that lives
in [AlexVachon/quirk](https://github.com/AlexVachon/quirk).

## License

MIT (see [`LICENSE`](LICENSE)).
