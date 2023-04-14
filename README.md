# page
android 标签管理器
![WX20230414-183414](https://user-images.githubusercontent.com/26162088/232022130-c8371f59-8840-4e00-b645-53f5687b40bb.png)
的使用方式是：
 <com.test.test.view.viewuitls.HotTagView
                        android:id="@+id/accpay_diao_fl"
                        android:padding="3dp"
                        android:layout_width="match_parent"
                        android:layout_height="match_parent"
                        app:text_size="5sp"
                        app:text_color="@color/black_bigb"
                        app:stroke_width="3dp"
                        app:line_color="#F4F4F4"
                        app:background_color="#F4F4F4"
                        app:textview_padding_left="13dp"
                        app:textview_padding_right="13dp"
                        app:textview_padding_top="4dp"
                        app:textview_padding_bottom="4dp"
                        app:textview_margin_left="5dp"
                        app:textview_margin_right="5dp"
                        app:textview_margin_top="10dp"/>
                        
                        
                        //添加数据
                        List<String> strings=new ArrayList<>();
		strings.add("吃饭1");
		strings.add("喝奶茶");
		strings.add("早饭");
		strings.add("骑驴觅驴");
		strings.add("喝汤");
		strings.add("加油1万元");
		strings.add("干某事888元");
		strings.add("走路10万公里");
		strings.add("想不出了");
		strings.add("就这样吧");
		strings.add("今天开心了吗");
		strings.add("哈哈哈");
		strings.add("吃饭dsaaaaaa17");
		strings.add("又被笑到");
		strings.add("难过了");
		strings.add("略略");
		accpay_diao_fl.setTags(strings);
    
    取得最后选择的数据
    accpay_diao_fl.getClickData();
