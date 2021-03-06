<a name=""></a>
##  4.3.3.1 (2018-05-29)

#### Bug Fixes

*   drop hotspot support hidpi ([1521c978](1521c978))
*   used list error. ([7e991834](7e991834))
*   hot spot invalid. ([7760af39](7760af39))
*   optimize rolling speed. ([a1fdb3c4](a1fdb3c4))
*   unified dialog icon size. ([b44378ff](b44378ff))
*   tips rect has no vertical. ([f9bf57ce](f9bf57ce))
*   2D only draw rect. ([2061a3b2](2061a3b2))
*   modify display jump btn logic. ([6633542c](6633542c))

#### Features

*   add scroll animation. ([0139257f](0139257f))


<a name=""></a>
##  4.3.3 (2018-05-23)


#### Features

*   optimize the window mode border. ([872ed8e2](872ed8e2))
*   append new item will show the jump button. ([8412e1a4](8412e1a4))
*   keep align horizontal center ([0d3656e9](0d3656e9))
*   adjust ui. ([c63390e4](c63390e4))
*   drop pixmap add shadow effect. ([92e0e75f](92e0e75f))
*   optimize the drag effect. ([1129b6a2](1129b6a2))
*   support drag and drop. ([7ae725de](7ae725de))
*   jump to control-center when click time & date label ([2801928f](2801928f))
*   button to increase image ([18e13292](18e13292))
*   open control-center account settings when click avatar ([e4ed2169](e4ed2169))
*   add rounded button. ([725bcbbf](725bcbbf))
*   add the separator between searchWidget and appsview. ([3a974e20](3a974e20))
*   save the used list. ([09d400c8](09d400c8))
*   the new installation tips ([26e4f082](26e4f082))
*   save used list config & fix switch model incorrect ([5b747876](5b747876))
*   sort used data model ([6ea47f7c](6ea47f7c))
*   add switch button to new frame ([6dbb3222](6dbb3222))
*   add used model ([5c5de36d](5c5de36d))
*   add date time to NewFrame ([dd7df8bf](dd7df8bf))
*   add new frame ([3dd096d1](3dd096d1))
*   read auto-exit settings ([3da8c20b](3da8c20b))
*   hold deepin-manual, forbid uninstall ([d8ac5134](d8ac5134))
*   add auto-exit timer ([7a065508](7a065508))
*   change drag pixmap opacity ([582cf793](582cf793))
*   support mouse wheel to adjust icon size ([874b375e](874b375e))
* **NewFrame:**
  *  add search tips label ([418cc845](418cc845))
  *  add right menu ([fc85a8bb](fc85a8bb))
  *  add right bar & search widget. ([066f430f](066f430f))
* **mini:**  hide frame when popup uninstall dialog ([6248e7c6](6248e7c6))
* **rightBar:**  respond to each button ([14bb6686](14bb6686))
* **windowed_frame:**  search support input method. ([010669f9](010669f9))

#### Bug Fixes

*   unified dialog icon size. ([b44378ff](b44378ff))
*   tips rect has no vertical. ([f9bf57ce](f9bf57ce))
*   2D only draw rect. ([2061a3b2](2061a3b2))
*   modify display jump btn logic. ([6633542c](6633542c))
*   block tab key ([1322d4d3](1322d4d3))
*   disable drop animation ([7b5b1084](7b5b1084))
*   new tips not vertical center. ([ca396f5b](ca396f5b))
*   wm support transparent to draw a shadow effect. ([557daa6f](557daa6f))
*   drag indicator pixmap support HiDPI. ([a32b6b92](a32b6b92))
*   use apt remove app the list did not deleted. ([a8c75ef9](a8c75ef9))
*   don't swap places when rolling. ([7bde0835](7bde0835))
*   incorrect drag start pos ([70de7dfd](70de7dfd))
*   used list does not append new app & remove app item(s). ([cebb07ee](cebb07ee))
*   drag start index error ([a412eee1](a412eee1))
*   no refresh when uninstalled for used model ([6980d1df](6980d1df))
*   switch error & refactor switchbtn ([2936830a](2936830a))
*   optimize created apps do not refresh list ([288e24f8](288e24f8))
*   not auto quit ([f8e8d082](f8e8d082))
*   Not scrolling enlarge at the top ([3716f2e7](3716f2e7))
*   gsettings key error ([ebde0e07](ebde0e07))
*   Adapt lintian ([8e5ff24f](8e5ff24f))
*   window position error in mini mode ([eb0310c6](eb0310c6))
*   autostart icon disappear ([35f2129b](35f2129b))
*   show paint error when show_detail ([b06bcd50](b06bcd50))
*   not display chainsproxy when not configuration ([6ef7f873](6ef7f873))
* **WindowFrame:**  use DRegionMonitor check mouse point ([9f59c7ac](9f59c7ac))
* **autostart:**  autostart mark indicator position error in HiDPI ([f18937a1](f18937a1))
* **background:**
  *  fallback to default when wallpaper not found ([cb018a6e](cb018a6e))
  *  not update gradient when background blur changed ([dde22974](dde22974))
  *  use blur interface ([af054c2f](af054c2f))
* **listview:**  right click is not selected ([196b111d](196b111d))
* **menu:**  Memory leak, no destruction of all objects. ([54c54b69](54c54b69))
* **miniframe:**  can move by mouse ([07930233](07930233))
* **view:**  item not update when move to new one ([17e5a66b](17e5a66b))



<a name="4.3.2"></a>
### 4.3.2 (2018-03-16)


#### Bug Fixes

* **autostart:**  autostart mark indicator position error in HiDPI ([f18937a1](f18937a1))



<a name="4.3.1"></a>
## 4.3.1 (2018-03-08)


#### Features

*   add auto-exit timer ([7a065508](7a065508))
*   change drag pixmap opacity ([582cf793](582cf793))
*   support mouse wheel to adjust icon size ([874b375e](874b375e))
* **mini:**  hide frame when popup uninstall dialog ([6248e7c6](6248e7c6))

#### Bug Fixes

*   Adapt lintian ([8e5ff24f](8e5ff24f))
*   window position error in mini mode ([eb0310c6](eb0310c6))
*   autostart icon disappear ([35f2129b](35f2129b))
*   show paint error when show_detail ([b06bcd50](b06bcd50))
*   not display chainsproxy when not configuration ([6ef7f873](6ef7f873))
* **background:**
  *  fallback to default when wallpaper not found ([cb018a6e](cb018a6e))
  *  not update gradient when background blur changed ([dde22974](dde22974))
  *  use blur interface ([af054c2f](af054c2f))
* **menu:**  Memory leak, no destruction of all objects. ([54c54b69](54c54b69))
* **miniframe:**  can move by mouse ([07930233](07930233))
* **view:**  item not update when move to new one ([17e5a66b](17e5a66b))



### 4.3.0
* Fix position error.

### 4.2.9
* Update translate files.

### 4.2.8
* Add menu option to disable HiDPI-scale on application.

### 4.2.7
* Fix non-integer HiDPI-scale 1px black line.

### 4.2.6
* Improve HiDPI painting

### 4.2.5
* Update translations.

### 4.2.4
* Improve item icon adjust policy.
  Improve graphics paint algorithm.

### 4.2.3
* Fix: uninstll dialog icon too smaill at HiDPI screen.

### 4.2.2
* Feature: Hide frame when uninstall dialog popup.
* Fix: startup mark icon placed pos error

### 4.2.1
* Fix autostart icon disappear

### 4.2.0
* HiDPI Support

### 4.1.9
* Minor bug fixes
