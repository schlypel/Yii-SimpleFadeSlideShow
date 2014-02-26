# SimpleFadeSlideShow
This is a wrapper to use the Simple FadeSlideShow jQuery plugin from Pascal Bajorat with the Yii framework (PHP)

## Sources/Dependencies
* **jQuery** http://jquery.com/
* **Yii Framework** http://www.yiiframework.com/
* **Simple FadeSlideShow** http://www.simplefadeslideshow.com/

## How to use
* download the latest from github or do a checkout ()
* put the folder **SimpleFadeSlideShow** to your extensions folder, usually *protected/extensions*
* use the provided widget in your view

### Example Markup
Thanks to Yii´s auto loading, there is no need to add this extension to your config.

**Minimal markup**

´´´php
$this->widget(
	'ext.SimpleFadeSlideShow.SimpleFadeSlideShow',
	array(
		'images' => array('url.to.image','url.to.another.image')
	)
);
´´´

**Advanced markup**

´´´php
$this->widget(
	'ext.SimpleFadeSlideShow.SimpleFadeSlideShow',
	array(
		'images' => array(
			array(
				'src' => 'url.to.image',
				'href' => 'url.to.open.on.click',
				'text' => 'Some text to show as link title and image alt tag'
			),
			array(
				'src' => 'url.to.another.image',
				'href' => 'url.to.open.on.click',
				'text' => 'Some text to show as link title and image alt tag'
			)
		),
		'width' => 624,
		'height' => 240,
		'interval' => 10000,
		'speed' => 'slow',
		'ListElement' => false,
		'PlayPauseElement' => false,
		'autoPlay' => true,
	)
);
´´´

Basically all options from the jQuery plugin are supported, they may be given directly, if not given, some default values will be used.

Additionally you may give another CSS file or arrow image.

To see a list of all parameters, just have a look at the code, it´s very simple.
