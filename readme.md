SIT305 project for android
本app主要提供停车场搜索和导航功能，提供停车场列表以及停车场详情数据。
停车场列表支持距离和价格排序，停车场详情，包括图片，剩余车位，价格等等。
停车场详情页面可以进入导航页面，从当前定位通过百度地图搜索找到最近的一条线路，提供导航功能。目前只支持驾驶导航，未来可扩展步行以及自行车导航线路。
除了基本功能之外，还添加注册功能，输入username，并判断当前username是否被注册过。输入密码并确认两次输入的密码是否正确。
注册成功的账号才能在登录界面登录，登录成功的用户下一次进入不需要再次登录，除非在侧滑页面点击logout。
关于页面有app的github地址和开发者信息


本app导航主要使用百度地图，百度定位回去当前经纬度以及地址信息，然后根据经纬度信息来回去天气信息