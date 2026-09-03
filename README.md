# sw-MLPL live demo (stable)

The **stable public build** of the sw-MLPL playground:

### https://mlpl.softwarewrighter.com/

sw-MLPL is a Rust-first array and tensor programming language for machine
learning, visualization, and experimentation, inspired by APL, APL2, J,
and BQN. The playground runs the interpreter entirely in your browser
(WebAssembly) -- pick a demo, edit it, and run it live.

## What this repository is

This repo holds ONLY the built, deployed site for the stable channel, so
the public URL stays put while development continues. It is published
deliberately from the source repository, not on every push:

- **Source code:** https://github.com/sw-ml-study/sw-mlpl
- **Rolling dev build:** https://sw-ml-study.github.io/sw-mlpl/ (moves on
  every push -- for development, not for sharing)
- **Stable build (here):** https://mlpl.softwarewrighter.com/ (moves only
  when a release is cut)

Each deploy is produced by `scripts/release-stable.sh` in the source
repository. `build-info.json` records the source commit this build was
cut from and marks the channel `stable`.

## Copyright

Copyright (c) 2026 Michael A Wright

## License

MIT. See [`LICENSE`](LICENSE) and [`COPYRIGHT`](COPYRIGHT).
