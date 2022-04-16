# build-envs

This repo contains [Vagrant](https://www.vagrantup.com) build environment setups for various distributions.

If you don't have Vagrant, you can set it up on macOS using Homebrew:

```
brew install virtualbox vagrant
```

Here are example steps that can be followed to build Planck on for a given distro:

1. `cd ubuntu-14.04_64`
2. `vagrant up`
3. `vagrant ssh`
4. `git clone https://github.com/mfikes/planck`
5. `cd planck`
6. `script/build`

When you are finished with a VM you can remove it with `vagrant destroy`.

# License

Copyright © 2018–2022 Mike Fikes and Contributors

Distributed under the Eclipse Public License either version 1.0 or (at your option) any later version.
