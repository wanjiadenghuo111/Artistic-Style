# Artistic-Style
## astyle_3.0.1_linux 
**'delete-empty-lines'** filed it is overridden to delete multiple consecutive empty lines instead of deleting all empty lines, you got try it !
----------------------------------------------------------------------------------------------
	## before:
	fun
	{
	
		int a;

		int b;
		
	}

	fun
	{
		int a;
		int b;
	}

----------------------------------------------------------------------------------------------
	##now:
	fun
	{
	
		int a;




		int b;
		
	}

	fun
	{
		
		int a;

		int b;
		
	}


-------------------------------
	--style=allman
	indent=spaces=4	        # 缩进采用4个空格
	indent-switches         # -S  设置 switch 整体缩进
	#indent-cases 	        # -K  设置 cases 整体缩进
	indent-namespaces       # -N  设置 namespace 整体缩进
	indent-preproc-block    # -xW 设置预处理模块缩进
	indent-preproc-define 	# -w  设置宏定义模块缩进	
	pad-oper                # -p  操作符前后填充空格
	delete-empty-lines      # -xe 删除多余空行
	add-braces              # -j  单行语句加上大括号
	#align-pointer=name      # *、&这类字符靠近变量名字
	align-pointer=type       #*、&这类字符靠近类型
	indent-col1-comments	 #缩进从第一列开始的 c++ 注释
	
### http://www.mdeditor.com/  It's easier than github to write md .
