1.将两个字符利用字符串对象的方法变成一个字符,显示在页面id为h1的元素中
答:
		<script type="text/javascript">
		    var h1=document.getElementById('h1');
			var a='你好';
			var b='tom';
			var c=a.concat(b);
			h1.innerText=c;
		</script>

2.一个富豪想存87万,给理财顾问写了87w,请自动生成存储870000的方法,显示在页面id为h2的元素中
答:
		<script type="text/javascript">
			var h2=document.getElementById('h2')
			var a='87w';
			var b=a.slice(0,2);
			var c=b.padEnd(6,0);
			h2.innerText=c;
		</script>

3.一个数字79387.348的工程款,保留两位小数存入,显示在页面id为h3的元素中
答:
		<script type="text/javascript">
			var a=79387.348;
			var b=a.toFixed(2);
			h3.innerText=b;
		</script>

4.一张图片是一个相对路径img/head/icon/1.jpg,我只需要拿到它的文件夹目录后显示在页面id为h4的元素中
答:
		<script type="text/javascript">
			var img=document.getElementById('a');
			var src=img.getAttribute('src');
                        var h4=document.getElementById('h4');
			var s=src.substr(0,15);
			h4.innerText=s;			
		</script>

5.用户输入验证码,无论大小写输入都会正确的方法,显示在页面id为h5的元素中
答:
		<script type="text/javascript">
			var inp=document.getElementById('inp');
			var btn=document.getElementById('btn');
			var h5=document.getElementById('h5');	          
			btn.onclick=function(){
			var a=inp.value;
			var b=a.toLowerCase();
                        if (b=='abcd') {
                        h5.innerText='输入正确';
                        }else{
                      	 h5.innerText='请重新输入';
                        }
              
			}
		</script>