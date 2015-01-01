SassDoc team
============

> SassDoc team collaboration tools.

Installation
------------

```sh
mkdir -p ~/opt
git clone https://github.com/SassDoc/team.git ~/opt/sassdoc-team
eval "$(echo 'export PATH="$HOME/opt/sassdoc-team:$PATH"' | tee -a ~/.profile)"
```

sd-npm-own
----------

Add SassDoc owners (from [SassDoc npm package](https://www.npmjs.com/package/sassdoc))
to given package.

For example, after the first sassdocify publish, I ran
`sd-npm-own sassdocify` and it dynamically added SassDoc owners to this
new package.
