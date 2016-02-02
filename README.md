Redmine whitepaper theme
==============

This is github-like theme for Redmine.
It is based on A1 theme version 1.0.3 by Kirill Bezrukov www.redminecrm.com, and gitmike theme version 1.0.7 by makotokw.

![snapshot](https://github.com/chase0213/redmine-theme-whitepaper/blob/master/snapshots/overview.png)

## Installation

### Install theme

1. Download from https://github.com/chase0213/redmine-theme-whitepaper/tags
1. Move to `redmine/public/theme/whitepaper`

Or by using git:

```
cd redmine/public/theme
git clone git://github.com/makotokw/redmine-theme-whitepaper.git whitepaper
```

### Change theme

1. Open your redmine on a browser
1. Login as admin user
1. Go to ``Administration > Settings > Display``
1. Select ``whitepaper`` on ``Theme``

## Development

```
cd redmine/public/theme
git clone git://github.com/makotokw/redmine-theme-whitepaper.git whitepaper
cd gitmike
gem install compass
npm install -g gulp
npm install
gulp debug
```

## License

GPL3

## Change Log

* **1.0.0** (2016/01/18): Forked from [redmine-theme-gitmike](https://github.com/makotokw/redmine-theme-gitmike)
