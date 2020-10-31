# Alternative Alert
Other way to create a beautiful alert with `Alternative Alert`.

Try it ! &rArr; [**Alternative Alert**](https://aldyrifaldi.github.io/Alternative-Alert)


##Instalation
### CSS
##### 	Bootstrap 4 Latest
    https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/css/bootstrap.min.css
### JS
##### Jquery
```javascript
https://code.jquery.com/jquery-3.5.1.slim.min.js
```
##### Bootstrap 4 (Recommended Latest Version)
 
```javascript
https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js
```

##### LottieJs
```javascript
https://cdnjs.cloudflare.com/ajax/libs/lottie-web/5.7.3/lottie.min.js
```
##### Alternative Alert (FAT Version)
    https://cdn.jsdelivr.net/gh/aldyrifaldi/Alternative-Alert@v0.1-alpha/js/alt-alert.js

##### Alternative Alert (MIN Version)
    https://cdn.jsdelivr.net/gh/aldyrifaldi/Alternative-Alert@v0.1-alpha/js/alt-alert.min.js

## Examples
The most basic message
```javascript
Alt.alternative({title:"Hello World"})
```
A message signalling an success
```javascript
Alt.alternative({status:"success",title:"Hurrah",text:"Your request successfully"})
```
Handling result of Alternative Alert
```javascript
Alt.alternative({
	status: "question",
	title: "Are You Sure",
	text: "Your data will delete permanently",
	showCancelButton: true,
}).then((res) => {
	if(res) {
		Alt.alternative({
			status: "success",
			title: "Deleted",
			text: "Data deleted permanently"
		})
	}
})
```
[Go here to see more details documentation](https://aldyrifaldi.github.io/Alternative-Alert "Go here to see more details documentation")

## Browser Support
| Chrome  |Firefox   | IE11  | Edge  | Safari   | Opera  |
| :------------: | :------------: | :------------: | :------------: | :------------: | :------------: |
|  	&#10003; | 	&#10003;  | 	&#10003;  | 	&#10003;  | 	&#10003;  | 	&#10003;  |


## Licence

MIT License

Copyright (c) 2020 Aldy Rifaldi.B

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
