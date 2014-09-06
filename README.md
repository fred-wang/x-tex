# About

x-tex is a simple container for (La)TeX expressions that automatically converts them into MathML, which uses the [X-Tag Polylib](http://x-tags.org/). For a more native implementation with Web Components and Shadow DOM, see [this example from TeXZilla](http://fred-wang.github.io/TeXZilla/examples/customElement.html).

# Usage

```
        <x-tex>\frac{x^2}{a^2} + \frac{y^2}{b^2} = 1</x-tex>
        <x-tex display="block">\Gamma(t) = \lim_{n \to \infty} \frac{n! \; n^t}{t \; (t+1)\cdots(t+n)}= \frac{1}{t} \prod_{n=1}^\infty \frac{\left(1+\frac{1}{n}\right)^t}{1+\frac{t}{n}} = \frac{e^{-\gamma t}}{t} \prod_{n=1}^\infty \left(1 + \frac{t}{n}\right)^{-1} e^{\frac{t}{n}}</x-tex>
        <x-tex dir="rtl">س = \frac{-ب\pm\sqrt{ب^٢-٤اج}}{٢ا}</x-tex>
```

# Install

*Requirements*

Node / NPM

Bower (Package Manager)

	$ npm install bower -g

For development
	
	$ bower install

Inside your project run:

	$ bower install x-tag-tex


This downloads the component and dependencies to ./components
