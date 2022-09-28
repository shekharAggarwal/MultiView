# MultiView

## How to Install
Step 1. Add it in your root build.gradle at the end of repositories:
```
allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
}
```
Step 2. Add the dependency
```
dependencies {
	        implementation 'com.github.shekharAggarwal:MultiView:1.0.0'
}
```

## How To Use
### Add annotation CustomPreview
```
@Composable
@CustomPreview
fun DefaultPreview() {
    DevViewTheme {
        Greeting("Android")
    }
}
```
### Add annotation DevicePreview
```
@Composable
@DevicePreview
fun DefaultPreview() {
    DevViewTheme {
        Greeting("Android")
    }
}
```
Or Add both
```
@Composable
@CustomPreview
@DevicePreview
fun DefaultPreview() {
    DevViewTheme {
        Greeting("Android")
    }
}
```
## 👨 Shekhar Aggarwal

<a href="https://twitter.com/ShekharAggarw17"><img src="https://github.com/aritraroy/social-icons/blob/master/twitter-icon.png?raw=true" width="60"></a>
<a href="https://www.linkedin.com/in/shekharaggarwal"><img src="https://github.com/aritraroy/social-icons/blob/master/linkedin-icon.png?raw=true" width="60"></a>
<a href="https://instagram.com/theshekharaggarwal"><img src="https://github.com/aritraroy/social-icons/blob/master/instagram-icon.png?raw=true" width="60"></a>

# 👍 How to Contribute
1. Fork it
2. Create your feature branch (git checkout -b my-new-feature)
3. Commit your changes (git commit -am 'Add some feature')
4. Push to the branch (git push origin my-new-feature)
5. Create new Pull Request
