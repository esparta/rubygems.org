# RubyGems.org (née Gemcutter)
The Ruby community's gem host.

## Purpose

* Provide a better API for dealing with gems
* Create more transparent and accessible project pages
* Enable the community to improve and enhance the site

## Support

<a href="https://rubytogether.org/"><img src="https://rubytogether.org/images/rubies.svg" width=200></a>
<a href="https://rubycentral.org/"><img src="http://rubycentral.org/images/logo.png" width=200></a><br/>

http://rubycentral.org/images/logo.png

[RubyGems.org](RubyGems.org) is managed by [Ruby Central](http://rubycentral.org), a community-funded organization supported by conference participation for [RailsConf](railsconf.org) and [RubyConf](rubyconf.org) through tickets and sponsorships.

[RubyTogether](rubytogether.org) sponsors individuals to work on development and operations work of RubyGems.org to augment the work of many volunteers. If you are interested in joining, you can do so as a [developer](https://rubytogether.org/developers) or as a [company](https://rubytogether.org/companies). The availability of RubyGems.org is not dependent on these paid contributors and is the sole responsibility of Ruby Central.

Hosting fees are paid by Ruby Central and CDN fees are generously donated by [Fastly](fastly.com).

## Links

* [Mailing List][]
* [FAQ][]
* [IRC][]: #rubygems on Freenode
* [Travis][]: [![Build Status](https://img.shields.io/travis/rubygems/rubygems.org/master.svg)][travis]
* [Gemnasium][]: [![Dependency Status](https://img.shields.io/gemnasium/rubygems/rubygems.org.svg)][gemnasium]
* [Code Climate][]: [![Maintainability](https://api.codeclimate.com/v1/badges/7110bb3f9b765042d604/maintainability)](https://codeclimate.com/github/rubygems/rubygems.org/maintainability)
* [Trello Board][]

[mailing list]: https://groups.google.com/group/rubygems-org
[faq]: http://help.rubygems.org/kb/gemcutter/faq
[irc]: https://webchat.freenode.net/?channels=rubygems
[travis]: https://travis-ci.org/rubygems/rubygems.org
[gemnasium]: https://gemnasium.com/rubygems/rubygems.org
[code climate]: https://codeclimate.com/github/rubygems/rubygems.org
[trello board]: https://trello.com/board/rubygems-org/513f9634a7ed906115000755

## Contributions

Please follow our [contribution guidelines][].

[contribution guidelines]: https://github.com/rubygems/rubygems.org/blob/master/CONTRIBUTING.md

To get setup, please check out the [Development Setup][].

[development setup]: https://github.com/rubygems/rubygems.org/blob/master/CONTRIBUTING.md#development-setup

Our deployment process is documented on the wiki as well, there's a multi-step
[Checklist][] to run through.

[checklist]: https://github.com/rubygems/rubygems-infrastructure/wiki/Deploys

Also please take note of our [Code of Conduct](https://github.com/rubygems/rubygems.org/blob/master/CODE_OF_CONDUCT.md).

If you have any trouble or questions getting set up please create an issue on this repository and we'll be happy to help!

## Organization

RubyGems.org consists of a few major parts:

* Rails app: To manage users and allow others to view gems, etc.
* Gem processor: Handles incoming gems and storing them in Amazon S3 (production) or
  on the filesystem in `server/` (development).

## License

RubyGems.org uses the MIT license. Please check the [LICENSE][] file for more details.

[license]: https://github.com/rubygems/rubygems.org/blob/master/MIT-LICENSE
