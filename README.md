# Alternative Alert
Other way to create a beautiful alert with `Alternative Alert`.

Try it ! &rArr; [**Alternative Alert**](https://aldyrifaldi.github.io/Alternative-Alert)


##Instalation
### CSS
##### 	Bootstrap 4 Latest
    https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/css/bootstrap.min.css
### JS
##### Bootstrap 4 (Recommended Latest Version)
 
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ho+j7jyWK8fNQe+A12Hb8AhRq26LrZ/JpcUGGOn+Y7RsweNrtN/tE3MoK7ZeZDyx" crossorigin="anonymous"></script>
##### LottieJs
        <script src="https://cdnjs.cloudflare.com/ajax/libs/lottie-web/5.7.3/lottie.min.js" integrity="sha512-35O/v2b9y+gtxy3HK+G3Ah60g1hGfrxv67nL6CJ/T56easDKE2TAukzxW+/WOLqyGE7cBg0FR2KhiTJYs+FKrw==" crossorigin="anonymous"></script>
    
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
