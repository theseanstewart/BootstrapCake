# BootstrapCake Shell Template

BootstrapCake is a shell template for rapidly developing beautiful Bootstrap themed CakePHP applications through the CakePHP console. The default template uses the ugly CakePHP styling but this template makes your app look beautiful by default.

## Requirements

* [CakePHP](http://cakephp.org/) >= 2.3
* [Bootstrap](http://getbootstrap.com/) >= 3.0

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

For more information and screenshots, please visit [http://www.ekoim.com/blog/bootstrap-cakephp-bootstrapcake/](http://www.ekoim.com/blog/bootstrap-cakephp-bootstrapcake/)