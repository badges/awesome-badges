# Awesome Badges

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated collection of awesome things related to status badges.

_While this list is maintained by Paul Melnikow from the Shields core team, it
includes Shields-related and non-Shields-related resources._

### Dynamic badge services

- [Shields.io](https://shields.io/) &ndash; Original home of the badges,
  launched in 2014.
- [Badgen.net](https://badgen.net/) &ndash; Fast badge generating service launched
  in 2018.
- [NodeICO](https://nodei.co/) &ndash; Large-format status badges for Node.js
  projects &ndash; which were once very popular!
- [PlayBadges](https://playbadges.pavi2410.me) &ndash; Show off your Play Store™ app's downloads and ratings in your repo

### Badge tools

- [Badgie](https://badgie.me/) &ndash; Scans the contents of your repository and
  adds badges based on what it finds.
- [Badges](https://github.com/bevry/badges) &ndash; Node.js/Deno/Browser npm package for rendering the HTML of various badges
- [Projectz](https://github.com/bevry/projectz) &ndash; Render Badges into your README based on your package.json configuration
- [shields.io Raycast extension](https://www.raycast.com/litomore/badges) &ndash; A more convenient UI for creating shields.io badges
- [shields-badge](https://github.com/galtzo-floss/shields-badge) &ndash; RubyGem for generating shields.io badge URLs and Markdown

### Raster badges

> SVG badges are encouraged because they render better on Retina displays and
> scale up beautifully. However in a few environments, such as Slack and HTML
> email, SVG images won't render, so PNG badges are preferred. Shields offers
> raster badges through its raster server, `raster.shields.io`.

- [svg-to-image-proxy](https://github.com/badges/svg-to-image-proxy) &ndash;
  Rasterizing proxy based on Node and Puppeteer which can be hosted on Vercel.
  (Since 2019 this code has been used to run `raster.shields.io`, however it's
  about to be deprecated in favor of [squint](https://github.com/badges/squint/).)
- [squint](https://github.com/badges/squint/) &ndash; Rasterizing proxy based on
  Rust and [libcairo](https://www.cairographics.org/).

### Static badges

- [For The Badge](https://forthebadge.com/) &ndash; Provides static badges
  using a flat and boxy badge design which has become a classic. (This badge
  format is available as `?style=for-the-badge` on Shields.io.)

### Static badge collections

- [Badges 4 README.md Profile](https://github.com/alexandresanlim/Badges4-README.md-Profile) &ndash; Catalog of Shields.io Badges for readme profiles
- [Project Types](https://project-types.github.io/) &ndash; Static badges for
  four types of open-source project, as classified in Nadia Eghbal's
  _Working in Public_.
- [Simple Badges](https://github.com/developStorm/simple-badges) &ndash; Catalog of Shields.io Badges with Simple Icons

### Dynamic data providers

> Dynamic data providers are third parties who publish data APIs which can be
> used to back one of the dynamic badge services:
>
> - [Shields' Endpoint badge](https://shields.io/endpoint)
> - [Badgen's https badge](https://badgen.net/https)
> - [Badgen's RunKit endpoint badge](https://badgen.net/runkit)

- [Cell Shield](https://cellshield.info) &ndash; a service that allows backing a shields.io badge with a cell from a public Google Spreadsheet.
- [TYPO3 Badges](https://typo3-badges.dev) &ndash; API that provides
  JSON endpoints to render badges of [TYPO3 CMS extensions](https://extensions.typo3.org/)
  via Shields or Badgen.
- [Dynamic Badge Formatter](https://github.com/DenverCoder1/dynamic-badge-formatter) &ndash; Allows users to apply formatters for metrics, versions, dates, and more to dynamic shields.io badges to make them look consistent.

### Badge-rendering software

- [badge-maker](https://github.com/badges/shields/tree/master/badge-maker)
  &ndash; JavaScript; supports plastic, flat, flat-square, for-the-badge, and
  social styles. Powers Shields.io.
- [badgen](https://github.com/badgen/badgen) &ndash; TypeScript; supports classic
  and flat. Powers Badgen.
- [gradient-badge](https://github.com/bokub/gradient-badge) &ndash; JavaScript;
  generates gradient badges in classic and flat.
- [poser](https://github.com/badges/poser) &ndash; PHP.
- [pybadges](https://github.com/google/pybadges) &ndash; Python.
- [browser-support-badge](https://github.com/hustcc/browser-support-badge) &ndash;
  JavaScript; generates browser version compatibility badges.
- [badge4j](https://github.com/silentsoft/badge4j) &ndash; Java.

### Icons

- [Simple Icons](https://simpleicons.org/) &ndash; Home of the bulk of the
  icons used by both Shields and Badgen.
- [Custom Icon Badges](https://github.com/DenverCoder1/custom-icon-badges) &ndash; Allows users to more easily use Octicons and their own icons and logos on shields.io badges.
- [Simple Badges](https://badges.pages.dev/) &ndash; Website for finding and previewing Simple Icons on shields.io badges.

### Academic articles

- [Badges on npm packages](https://cmustrudel.github.io/projects/badges/)
  &ndash; Data-driven assessment based on signaling theory applied to how
  badges are used in npm.
  [Published in ICSE 2018](https://cmustrudel.github.io/papers/icse18badges.pdf).
- [On the Usage of Badges in Open Source Packages on GitHub](http://ceur-ws.org/Vol-2605/9.pdf)
  &ndash; Data-driven study of how status badges are used in Cargo and Packagist
  projects.

### Historical articles

- [An Open Source Rage Diamond](https://olivierlacan.com/posts/an-open-source-rage-diamond/)
  _(Jun. 5, 2014)_ &ndash; An article about the motivation for the Shields
  project by one of its creators.
- [Shields badge specification](https://github.com/badges/shields/blob/master/spec/SPECIFICATION.md)
  &ndash; Visual design specification for Shields.

### Talks

- [Shields.io by Nicco Kunzmann](https://www.youtube.com/watch?v=abBdk8bSPKU) &ndash;
  A talk given by Nicco Kunzmann for I Love Free Software Day in Berlin,
  Feb. 14, 2019.
- [Cool badges for your project by Marcin Mielnicki](https://raw.githubusercontent.com/hacktoberfest-poznan/presentations/master/2018/Cool-badges-for-your-project.pdf)
  ([photos](https://www.facebook.com/media/set/?vanity=hacktoberfest&set=a.258422348195183))
  &ndash; A talk given by Shields core team member Marcin Mielnicki for
  Hacktoberfest Poznań 2018.

### Hosting your own badge service

- [Shields self-hosting](https://github.com/badges/shields/blob/master/doc/self-hosting.md)
  &ndash; Host your own copy of Shields to Heroku, Vercel, using Docker, or on a Node server.
- [Badgen self-hosting](https://github.com/badgen/badgen.net/#environments) &ndash;
  Host your own copy of Badgen on Vercel.

### Achievement badges

- [Open Badges](https://openbadges.org/) &ndash; A specification for
  verifiable digital badges.
- [Badgr](https://www.badgr.org/) &ndash; A service for creating verifiable
  achievement badges, based on the Open Badges specification.
