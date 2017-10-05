# 5e_monster_manual

The intent of this project is to be a complete online catalog for every monster
in the *Dungeons & Dragons* (5th Edition) -universe- multiverse.

## Contributing

There are several ways to contribute to this project:
- Improve the code and open a PR!
  (I am not an expert front end developer,
  I'm certain there are better ways of doing things.)
- Submit a bug report or request a feature in the
  [Issue Tracker](https://git.bmoore.xyz/ben/5e_monster_manual/issues)!
- Add to the monster catalog!
  1. Add your initials to the entries in the
    [catalog](https://git.bmoore.xyz/ben/5e_monster_manual/src/master/CATALOG.md).
  2. Open a PR (with WIP) to reserve your space.
  3. Update your PR with all additions to the catalog.
  4. Remove WIP from the PR so I know it's ready for review.

## Legal

Copyright &copy; 2016 Ben Moore.
[MIT License](https://git.bmoore.xyz/ben/5e_monster_manual/src/dev/LICENSE)

*Dungeons & Dragons* and related materials
Copyright &copy; *Wizards of the Coast LLC, a subsidiary of Hasbro, Inc.*
All rights reserved.

### Other Projects

- [Ractive.js](http://ractivejs.org)
  ([MIT License](https://github.com/ractivejs/ractive/blob/dev/LICENSE.md))
- [JQuery](http://jquery.com)
  ([License](https://github.com/jquery/jquery/blob/master/LICENSE.txt))
- [Bootstrap](https://getbootstrap.com)
  ([MIT License](https://github.com/twbs/bootstrap/blob/v4-dev/LICENSE))
- [Statblock 5e](https://github.com/Valloric/statblock5e)
  ([Apache 2.0 license](https://github.com/Valloric/statblock5e/blob/master/LICENSE.txt))

## TODO

- [x] Incorporate ractive into statblock template
- [x] Add Bootstrap/JQuery
- [ ] Add all monster entries to `monsters/` directory.
- [ ] Minify all `*.json` files in `monsters/` (`jq -c .`)
