# javascript-helper
- 求两点间距离

#
    var a = point2.x - point1.x
    var b = point2.y - point1.y
    var dis = Math.sqrt(a*a+b*b)
    console.log(dis)
- 弹出对话框

#
	<script>
		function f(){
			var b = confirm("Are you OK?")
			if(b){
				// when click sure
				console.log('sure')
			}
		}
		setTimeout(f,1000)
	</script>