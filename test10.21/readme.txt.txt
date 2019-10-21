1.将两个字符利用字符串对象的方法变成一个字符,显示在页面id为h1的元素中
答:

			var h1 = document.getElementById('h1');
			var s1 = new String('123');
			var s2 = new String('456');
			var s3 = s1.concat(s2);
			console.log(s3.match());
2.一个富豪想存87万,给理财顾问写了87w,请自动生成存储870000的方法,显示在页面id为h2的元素中
答:

			var str = '87';
			var estr = str.padEnd(6,'0');
			console.log(estr);

3.一个数字79387.348的工程款,保留两位小数存入,显示在页面id为h3的元素中
答:

4.一张图片是一个相对路径img/head/,icon/1.jpg,我只需要拿到它的文件夹目录后显示在页面id为h4的元素中
答:

5.用户输入验证码,无论大小写输入都会正确的方法,显示在页面id为h5的元素中
答:
                       var s1 = 'ABCDE';
			var s2 = 'abcde';
			console.log(s1.toLocaleLowerCase());
			console.log(s2.toLocaleLowerCase());
