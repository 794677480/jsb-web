1.�������ַ������ַ�������ķ������һ���ַ�,��ʾ��ҳ��idΪh1��Ԫ����
��:
		<script type="text/javascript">
		    var h1=document.getElementById('h1');
			var a='���';
			var b='tom';
			var c=a.concat(b);
			h1.innerText=c;
		</script>

2.һ���������87��,����ƹ���д��87w,���Զ����ɴ洢870000�ķ���,��ʾ��ҳ��idΪh2��Ԫ����
��:
		<script type="text/javascript">
			var h2=document.getElementById('h2')
			var a='87w';
			var b=a.slice(0,2);
			var c=b.padEnd(6,0);
			h2.innerText=c;
		</script>

3.һ������79387.348�Ĺ��̿�,������λС������,��ʾ��ҳ��idΪh3��Ԫ����
��:
		<script type="text/javascript">
			var a=79387.348;
			var b=a.toFixed(2);
			h3.innerText=b;
		</script>

4.һ��ͼƬ��һ�����·��img/head/icon/1.jpg,��ֻ��Ҫ�õ������ļ���Ŀ¼����ʾ��ҳ��idΪh4��Ԫ����
��:
		<script type="text/javascript">
			var img=document.getElementById('a');
			var src=img.getAttribute('src');
                        var h4=document.getElementById('h4');
			var s=src.substr(0,15);
			h4.innerText=s;			
		</script>

5.�û�������֤��,���۴�Сд���붼����ȷ�ķ���,��ʾ��ҳ��idΪh5��Ԫ����
��:
		<script type="text/javascript">
			var inp=document.getElementById('inp');
			var btn=document.getElementById('btn');
			var h5=document.getElementById('h5');	          
			btn.onclick=function(){
			var a=inp.value;
			var b=a.toLowerCase();
                        if (b=='abcd') {
                        h5.innerText='������ȷ';
                        }else{
                      	 h5.innerText='����������';
                        }
              
			}
		</script>