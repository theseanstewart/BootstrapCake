**Warning:** Only for CakePHP 4.x

# Bootstrap4Cake Shell Template

Bootstrap4Cake is a shell template for rapidly developing beautiful Bootstrap 4 themed CakePHP applications through the CakePHP  2.x console. The default template uses the ugly CakePHP styling but this template makes your app look beautiful by default.

![2019-01-20-185335_2720x986_scrot](https://user-images.githubusercontent.com/9076747/51443177-224beb00-1ce5-11e9-8839-a6c6d3b3a0a6.png)

## Requirements

* [CakePHP](http://cakephp.org/) >= 2.3
* [Bootstrap](http://getbootstrap.com/) >= 4.0

## Installation

* Extract the files into the proper directory.
* Update your App Controller (app/Controller/AppController.php) to use the Bootstrap layout

```
class AppController extends Controller {
	public function beforeFilter(){
		$this->layout = 'bootstrap';
	}
}
```

* Start baking! If you've never used the console, here's a great tutorial: [http://book.cakephp.org/2.0/en/console-and-shells/code-generation-with-bake.html](http://book.cakephp.org/2.0/en/console-and-shells/code-generation-with-bake.html)
* Make sure you select the bootstrap template when prompted

For more information and screenshots, please visit [http://www.ekoim.com/blog/bootstrap-cakephp-bootstrapcake/](http://www.ekoim.com/blog/bootstrap-cakephp-bootstrapcake/) (Bootstrap3 Version)
