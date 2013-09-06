# &lt;linkedin-button&gt;

Web Component wrapper for Linkedin-button's like button using Polymer.

> Maintained by [Gustavo Isensee](https://github.com/gustavoisensee).

## Demo

> [Check it live](http://gustavoisensee.github.io/linkedin-button).

## Usage

1. Import Web Components' polyfill:

	```html
	<script src="http://cdnjs.cloudflare.com/ajax/libs/polymer/0.0.20130816/polymer.min.js"></script>
	```

2. Import Custom Element:

	```html
	<link rel="import" href="src/linkedin-button.html">
	```

3. Start using it!

	```html
	<linkedin-button></linkedin-button>
	```

## Options

Attribute  | Options                   | Default             | Description
---        | ---                       | ---                 | ---
`lang`      | `en_US`, `fr_FR`, `es_ES`, `ru_RU`, `de_DE`, `it_IT`, `pt_BR`, `ro_RO`, `tr_TR`, `ja_JP`, `in_ID`, `ms_MY`, `ko_KR`, `sv_SE`, `cs_CZ`, `nl_NL`, `pl_PL`, `no_NO`, `da_DK`  | `bar`               | language button sharing
`url`      | `url` 	   | `string empty`               | url of the site
`position`   | `top`, `right`, `none ` | `right`               | position counter


## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

* v0.0.2 September 06, 2013

* Started project using [boilerplate-element](https://github.com/customelements/boilerplate-element)

## License

[MIT License](http://opensource.org/licenses/MIT)