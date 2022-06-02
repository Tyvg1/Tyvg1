 <!DOCTYPE html>
<html lang="ar">

<!-- Mirrored from api.moi.gov.sa-lmd.net/wpsnone/portal/ by HTTrack Website Copier/3.x [XR&CO 2014], Tue, 31 May 2022 14:54:05 GMT -->
<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8">
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, minimum-scale=1">
<meta name="robots" content="noindex" />
<title>وزارة الداخلية - الرئيسية</title>
<link rel="shortcut icon" type="image/x-icon" href="images/moifavicon.html" />
<link rel="stylesheet" type="text/css" href="styles/jquery.dataTables.css" />
<link rel="stylesheet" type="text/css" href="styles/dataTables.responsive.css" />
<link rel="stylesheet" type="text/css" href="styles/slider.css" />
<link rel="stylesheet" type="text/css" href="styles/fontello.css" />
<link rel="stylesheet" type="text/css" href="styles/menu-custom.css" />
<link rel="stylesheet" type="text/css" href="styles/tabs.css" />
<link rel="stylesheet" type="text/css" href="styles/base.css" />
<link rel="stylesheet" type="text/css" href="styles/custom.css" />
<link rel="stylesheet" type="text/css" href="styles/eservices_style.css" />
<link rel="stylesheet" type="text/css" href="styles/jquery-ui.min.css" />

<link rel="stylesheet" type="text/css" href="styles/style_arabic.css" />
<link rel="stylesheet" type="text/css" href="styles/font_arabic.css" />

	
<script type="text/javascript" src="ajax/jquery.min-1.11.1.js"></script>
<script type="text/javascript" src="ajax/jquery.min-1.7.2.js"></script>
<script type="text/javascript" src="ajax/browserValidator.js"></script>
<script type="text/javascript" src="ajax/responsive-switch.js"></script>
<script type="text/javascript" src="ajax/jquery.sliderTabs.js"></script>
<script type="text/javascript" src="ajax/jquery.slides.min.js"></script>
<script type="text/javascript" src="ajax/custom.js"></script>
<script type="text/javascript" src="ajax/slidesjs.initialize.js"></script>
<script type="text/javascript" src="ajax/themeBuilder.js"></script>
<script type="text/javascript" src="ajax/calendar_moi_dateConverter.js"></script>	
</head>
<body class="rtl" lang="ar">

<div class="wrapper">		
<div class="header-moi">	
<div class="absher-business-link">
	<div class="link-wrapper">
	  <div class="btnGoToBusiness">
			<a href="https://www.absher.sa/portal/landing.html" target="_new">
				<div>الدخول إلى منصة أبشر الشاملة</div> 
				<div class="red"></div>
			</a>
		</div>
		<a href="https://www.absher.sa/portal/landing.html" target="_new">
			<img src="images/arrow-1.png" alt="">
		</a>
	</div>
</div>

<div class="row">
	<div class="topnav pull-right">        	     
		<ul class="pull-right">			
			<li class="first"><span id="dateAr"> 
<script language="JavaScript">

var fixd;

function isGregLeapYear(year)
{
return year%4 == 0 && year%100 != 0 || year%400 == 0;
}


function gregToFixed(year, month, day)
{
var a = Math.floor((year - 1) / 4);
var b = Math.floor((year - 1) / 100);
var c = Math.floor((year - 1) / 400);
var d = Math.floor((367 * month - 362) / 12);

if (month <= 2)
e = 0;
else if (month > 2 && isGregLeapYear(year))
e = -1;
else
e = -2;

return 1 - 1 + 365 * (year - 1) + a - b + c + d + e + day;
}

function Hijri(year, month, day)
{
this.year = year;
this.month = month;
this.day = day;
this.toFixed = hijriToFixed;
this.toString = hijriToString;
}

function hijriToFixed()
{
return this.day + Math.ceil(29.5 * (this.month - 1)) + (this.year - 1) * 354 +
Math.floor((3 + 11 * this.year) / 30) + 227015 - 2;
}

function hijriToString()
{
var months = new Array("محرم","صفر","ربيع أول","ربيع الاخر","جمادى أول","جمادى ثانى","رجب","شعبان","رمضان","شوال","ذو القعدة","ذو الحجة");
return this.day + " " + months[this.month - 1]+ " " + this.year;
}

function fixedToHijri(f)
{
var i=new Hijri(1100, 1, 1);
i.year = Math.floor((30 * (f - 227015) + 10646) / 10631);
var i2=new Hijri(i.year, 1, 1);
var m = Math.ceil((f - 29 - i2.toFixed()) / 29.5) + 1;
i.month = Math.min(m, 12);
i2.year = i.year;
i2.month = i.month;
i2.day = 1;
i.day = f - i2.toFixed() + 1;
return i;
}

var tod=new Date();
var weekday=new Array("","  ","","","","","");
var monthname=new Array("يناير","فبراير","مارس","إبريل","مايو","يونيو","يوليو","أغسطس","سبتمبر","أكتوبر","نوفمبر","ديسمبر");

var y = tod.getFullYear();
var m = tod.getMonth();
var d = tod.getDate();
var dow = tod.getDay();
document.write(weekday[dow]  );
m++;
fixd=gregToFixed(y, m, d);
var h=new Hijri(1421, 11, 28);
h = fixedToHijri(fixd);
document.write(h.toString()+"");

</script>  

</span>
				<div id="dateDetail" style="display:none;">
					<ul>
<li id="hijriEn">هجري<p> 
<script language="JavaScript">

var fixd;

function isGregLeapYear(year)
{
return year%4 == 0 && year%100 != 0 || year%400 == 0;
}


function gregToFixed(year, month, day)
{
var a = Math.floor((year - 1) / 4);
var b = Math.floor((year - 1) / 100);
var c = Math.floor((year - 1) / 400);
var d = Math.floor((367 * month - 362) / 12);

if (month <= 2)
e = 0;
else if (month > 2 && isGregLeapYear(year))
e = -1;
else
e = -2;

return 1 - 1 + 365 * (year - 1) + a - b + c + d + e + day;
}

function Hijri(year, month, day)
{
this.year = year;
this.month = month;
this.day = day;
this.toFixed = hijriToFixed;
this.toString = hijriToString;
}

function hijriToFixed()
{
return this.day + Math.ceil(29.5 * (this.month - 1)) + (this.year - 1) * 354 +
Math.floor((3 + 11 * this.year) / 30) + 227015 - 2;
}

function hijriToString()
{
var months = new Array("محرم","صفر","ربيع أول","ربيع الاخر","جمادى أول","جمادى ثانى","رجب","شعبان","رمضان","شوال","ذو القعدة","ذو الحجة");
return this.day + " " + months[this.month - 1]+ " " + this.year;
}

function fixedToHijri(f)
{
var i=new Hijri(1100, 1, 1);
i.year = Math.floor((30 * (f - 227015) + 10646) / 10631);
var i2=new Hijri(i.year, 1, 1);
var m = Math.ceil((f - 29 - i2.toFixed()) / 29.5) + 1;
i.month = Math.min(m, 12);
i2.year = i.year;
i2.month = i.month;
i2.day = 1;
i.day = f - i2.toFixed() + 1;
return i;
}

var tod=new Date();
var weekday=new Array("","  ","","","","","");
var monthname=new Array("يناير","فبراير","مارس","إبريل","مايو","يونيو","يوليو","أغسطس","سبتمبر","أكتوبر","نوفمبر","ديسمبر");

var y = tod.getFullYear();
var m = tod.getMonth();
var d = tod.getDate();
var dow = tod.getDay();
document.write(weekday[dow]  );
m++;
fixd=gregToFixed(y, m, d);
var h=new Hijri(1421, 11, 28);
h = fixedToHijri(fixd);
document.write(h.toString()+"");

</script>  
						
					  </li>
<li id="gregorianEn">ميلادي<p>
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<title>Untitled Document</title>
</head>

<body>   
<script language="JavaScript">

var fixd;

function isGregLeapYear(year)
{
return year%4 == 0 && year%100 != 0 || year%400 == 0;
}


function gregToFixed(year, month, day)
{
var a = Math.floor((year - 1) / 4);
var b = Math.floor((year - 1) / 100);
var c = Math.floor((year - 1) / 400);
var d = Math.floor((367 * month - 362) / 12);

if (month <= 2)
e = 0;
else if (month > 2 && isGregLeapYear(year))
e = -1;
else
e = -2;

return 1 - 1 + 365 * (year - 1) + a - b + c + d + e + day;
}

function Hijri(year, month, day)
{
this.year = year;
this.month = month;
this.day = day;
this.toFixed = hijriToFixed;
this.toString = hijriToString;
}

function hijriToFixed()
{
return this.day + Math.ceil(29.5 * (this.month - 1)) + (this.year - 1) * 354 +
Math.floor((3 + 11 * this.year) / 30) + 227015 - 1;
}

function hijriToString()
{
var months = new Array("محرم","صفر","ربيع أول","ربيع ثانى","جمادى أول","جمادى ثانى","رجب","شعبان","رمضان","شوال","ذو القعدة","ذو الحجة");
return this.day + " " + months[this.month - 1]+ " " + this.year;
}

function fixedToHijri(f)
{
var i=new Hijri(1100, 1, 1);
i.year = Math.floor((30 * (f - 227015) + 10646) / 10631);
var i2=new Hijri(i.year, 1, 1);
var m = Math.ceil((f - 29 - i2.toFixed()) / 29.5) + 1;
i.month = Math.min(m, 12);
i2.year = i.year;
i2.month = i.month;
i2.day = 1;
i.day = f - i2.toFixed() + 2;
return i;
}

var tod=new Date();
var weekday=new Array("","","","","","","");
var monthname=new Array("يناير","فبراير","مارس","إبريل","مايو","يونيو","يوليو","أغسطس","سبتمبر","أكتوبر","نوفمبر","ديسمبر");

var y = tod.getFullYear();
var m = tod.getMonth();
var d = tod.getDate();
var dow = tod.getDay();
document.write(weekday[dow] + " " + d + " " + monthname[m] + " " + y);
m++;
fixd=gregToFixed(y, m, d);
var h=new Hijri(1421, 11, 28);
h = fixedToHijri(fixd);
document.write("");

</script>  
</body>

<!-- Mirrored from api.moi.gov.sa-lmd.net/wpsnone/portal/ by HTTrack Website Copier/3.x [XR&CO 2014], Tue, 31 May 2022 14:54:20 GMT -->
</html>				  </ul>
				</div>
			</li>			

			<li><a href="#"><span>الاتصال
						بنا</span></a></li>
			<li class="last_lang"><a href="#">English</a></li>
		</ul>
	</div>
</div>
	
<div class="logovp pull-left">
	<a href="#"> 
    <img src="images/absher_emblem.png" alt="" width="inherit" height="inherit" class="absher-emblem-mobile">
    <img id="logoimg" src="images/moi_logo_rtl.png" alt="" width="237" height="70" class="moi-logo-mobile">
	</a>
</div>
	
<div class="loginForm public"></div>
<div class="version_switch">
	<span class="version_switch_icon">
	</span>
	<span> <a class="arabic-link pull-right" href="#">English</a>
	</span>	
</div> 			
</div>
<!-- القائمة -->
<div class="mainnav"><div class="nav-holder">
<ul class="nav-items">
	<li class="home active" id="0">
		<a class="parent" href="index4c58.html?rZLNUsIwFIVfJRuWTm6b0JZlxkFahVFBlGbDpG2wYUhabAD16U27h8oMWeXnu2dyzhzM8QpzI47qU1hVGbFz55QHa0gojT3qPz0TNgYWPExH8xF4iQf4owPuJyym4RQgmk6GkLB4OR-9EgKMYP6f-XPAzO-bf8cc89zY2pY41ZVChToJM4B2W1ZaorwyVho7ALHbIZFVB4vcmwOUUY39-kFVtpW5VUfZoDUqDlbJptWsc1XgNJI0zCQALWiWkWAoQhFu3E0R5iIiQdSRzalFeXj2n2O_x6cz0vk8s1ibE--QS0n3afCLYbqsF9Lg9KKTGPDiinR6xPxbinlXiT32Fcs1X233e85cvdoKfVu8ulm_ar1c6ojouxWol7I-_r5ttF7Pmj-wh4pv/dz/d5/L0lHSkovd0RNQUZrQUVnQSEhLzROVkUvYXI&amp;v=Mozilla50WindowsNT100Win64x64AppleWebKit53736KHTMLlikeGeckoChrome9804758102Safari53736Windows_10">				
				<i class="homesprite home-mainmenu_home"></i> <span>الرئيسية</span>
		</a>
	</li>
	<li class="aboutmoi" id="1">
		<a class="parent" href="#" onMouseOver="setVisibility( sub1 ,  inline );" onMouseOut="setVisibility( sub1 , none );">				
				<i class="homesprite home-mainmenu_aboutmoi"></i> <span>عن الوزارة</span>
		</a>
		<div id="sub1" class="sub-nav sub-navSectors" style="display:none;" onMouseOver="setVisibility( sub1 ,  inline );" onMouseOut="setVisibility( sub1 , none );">
			<ul class="sector-levelSectors">
				<li>
					<a href="#">أهداف ومهام الوزارة</a>
					<ul class="menuSubLevel2">
					</ul></li>
				<li>
					<a href="#">الهيكل التنظيمي</a>
					<ul class="menuSubLevel2">
					</ul></li>
				<li>
					<a href="#">لمحة تاريخية</a>
					<ul class="menuSubLevel2">
					</ul></li>
				<li>
					<a href="#">عنوان الوزارة</a>
					<ul class="menuSubLevel2">
					</ul></li>
				<li>
					<a href="#">مراكز الاستقبال والتواصل الإلكتروني</a>
					<ul class="menuSubLevel2">
					</ul></li>
				<li>
					<a href="#">الأخبار</a>
					<ul class="menuSubLevel2">
					</ul></li>
				<li>
					<a href="#">تصريحات المتحدث الأمني</a>
					<ul class="menuSubLevel2">
					</ul></li>
				<li>
					<a href="#">المناقصات</a>
					<ul class="menuSubLevel2">
					</ul></li>
				<li>
					<a href="#">البلاغات الأمنية</a>
					<ul class="menuSubLevel2">
					</ul></li>
				<li>
					<a href="#">النماذج الإلكترونية</a>
					<ul class="menuSubLevel2">
					</ul></li>
				<li>
					<a href="#">الأسئلة الشائعة</a>
					<ul class="menuSubLevel2">
					</ul></li>
				<li>
					<a href="#">أنظمة وتعليمات</a>
					<ul class="menuSubLevel2">
					</ul></li>	
				<li>
					<a href="#">اتصل بنا</a>
					<ul class="menuSubLevel2">
					</ul></li>		
				<li>
					<a target="_blank" href="https://webmail.cloud.moi.gov.sa/owa">البريد الالكتروني لمنسوبي الوزارة</a>
					<ul class="menuSubLevel2">
					</ul></li>				
			</ul>
		</div>
    </li>	
	<li class="electronicinquiries" id="2">
		<a class="parent" href="#" onMouseOver="setVisibility( sub2 ,  inline );" onMouseOut="setVisibility( sub2 , none );">				
				<i class="homesprite home-mainmenu_publiceservices"></i> <span >الاستعلامات الإلكترونية</span>
		</a>
		<div id="sub2" class="sub-nav " style="display:none;" onMouseOver="setVisibility( sub2 ,  inline );" onMouseOut="setVisibility( sub2 , none );" >
        
        
        
   
   
   
   
   
   
  <ul class="sector-level" >
  
  
  
  
  
  
				<li class="moidiwan" onMouseOver="setVisibility( sub111 ,  inline );"  onMouseOut="setVisibility( sub111 , none );" id="sec-li-0">
					<h3 >ديوان وزارة الداخلية</h3>
                    
                    
                    
                    
                    
                    
                  <div id="sub111" onMouseOver="setVisibility( sub111 ,  inline );" onMouseOut="setVisibility( sub111 , none );" >
					<div  class="sector-sub sec-li-0 menu-hover" style="display:block;" id="sec-li-0">
						<ul class="left">
							<li  ><a href="#">الاستعلام
									العام عن رصيد مدفوعات الخدمات المتبقي</a> </li>
	
							<li style=""><a href="#">الاستعلام
									العام عن المعاملات</a> </li>
							
							<li  ><a href="#">
									الاستعلام العام عن طلبات التصاريح</a> </li>
						</ul>
					</div></div>
				</li>
				<li class="civilaffairs " onMouseOver="setVisibility( sub222 ,  inline );"  onMouseOut="setVisibility( sub222 , none );">
					<h3>الأحوال المدنية</h3>
                    
                    
                    
                    
                    
                    
                  <div id="sub222" style="display:none;" onMouseOver="setVisibility( sub222 ,  inline );" onMouseOut="setVisibility( sub222 , none );" >
					<div class="sector-sub sec-li-1 menu-hover" >
						<ul class="left">
							<li  ><a  href="#">الاستعلام
									العام عن أحقية القيام بالحج</a> </li>
							<li style=""><a href="#">الاستعلام عن معاملة في الاحوال المدنية
									</a> </li>
							
							
							<li style=""><a href="#">حجز موعد
									</a> </li>

							<li style=""><a href="#">الاستعلام عن صلاحية الهوية </a> </li>
						</ul>
					</div></div>
				</li>
				<li class="labourimportation" onMouseOver="setVisibility( sub333 ,  inline );"  onMouseOut="setVisibility( sub333 , none );">
					<h3>الإستقدام</h3>
                    
                    
                    
                    <div id="sub333" style="display:none;" onMouseOver="setVisibility( sub333 ,  inline );" onMouseOut="setVisibility( sub333 , none );" >
					<div class="sector-sub sec-li-2 menu-hover">
						<ul class="left">
							<li style=""><a href="#">الاستعلام
									عن طلبات تأشيرات العمل</a> </li>
						</ul>
					</div></div>
			</li>
				<li class="passports" onMouseOver="setVisibility( sub444 ,  inline );"  onMouseOut="setVisibility( sub444 , none );">
					<h3>الجوازات</h3>
                    
                    
                    <div id="sub444" style="display:none;" onMouseOver="setVisibility( sub444 ,  inline );" onMouseOut="setVisibility( sub444 , none );" >
					<div class="sector-sub sec-li-3 menu-hover">
						<ul class="left">
							<li style=""><a href="#">
									الاستعلام العام عن أحقية القيام بالحج</a> </li>
							<li style=""><a href="#">الاستعلام
									العام عن صلاحية التأمين الصحي للمقيمين فقط</a>
							</li>
							<li style=""><a href="#">الاستعلام
									عن العمالة الجديدة والزائرين</a> </li>
							<li style=""><a href="#">الاستعلام العام عن حالة تأشيرة خروج وعودة</a> </li>

							<li style=""><a href="#">الاستعلام
									العام عن البصمة</a> </li>
							<li style=""><a href="iqamaa_search.html">الاستعلام
									عن صلاحية الإقامة</a> </li>
							<li style=""><a href="#">الاستعلام عن وصول العمالة</a> </li>
							<li style=""><a href="#">حجز
									موعد</a> </li>
						</ul>
					</div></div>
				</li>
				<li class="traffic" onMouseOver="setVisibility( sub555 ,  inline );"  onMouseOut="setVisibility( sub555 , none );">
					<h3>المرور</h3>
                    
                    
                    <div id="sub555" style="display:none;" onMouseOver="setVisibility( sub555 ,  inline );" onMouseOut="setVisibility( sub555 , none );" >
					<div class="sector-sub sec-li-4 menu-hover">
						<ul class="left">
							<li style=""><a href="#">الاستعلام
									عن المخالفات المرورية</a> </li>
							<li style=""><a href="#"> الاستعلام عن تفاصيل المخالفة المرورية</a> </li>

							<li style=""><a href="#">
									الاستعلام العام عن صلاحية التأمين على المركبات</a> </li>
						</ul>
					</div></div>
				</li>
				<li class="emirates" onMouseOver="setVisibility( sub666 ,  inline );"  onMouseOut="setVisibility( sub666 , none );">
					<h3>إمارات المناطق</h3>
                    
                    
                    
                    <div id="sub666" style="display:none;" onMouseOver="setVisibility( sub666 ,  inline );" onMouseOut="setVisibility( sub666 , none );" >
					<div class="sector-sub sec-li-5 menu-hover">
						<ul class="left">
							<li style="">
								<span class="lebelcolor">إمارة المنطقة الشرقية</span> 
								<ul class="sublvl">
									<li><a href="#">الاستعلام
											عن المعاملات</a></li>
								</ul>
							</li>
							<li style="">
								<span class="lebelcolor">إمارة الحدود الشمالية</span> 
								<ul class="sublvl">
									<li><a href="#">الاستعلام
											عن المعاملات</a></li>
								</ul>
							</li>
						</ul>
					</div>
				</li>
				<li class="hajjpermit" onMouseOver="setVisibility( sub777 ,  inline );"  onMouseOut="setVisibility( sub777 , none );">
					<h3>تصاريح الحج</h3>
                    
                    
                    <div id="sub777" style="display:none;" onMouseOver="setVisibility( sub777 ,  inline );" onMouseOut="setVisibility( sub777 , none );" >
					<div class="sector-sub sec-li-6 menu-hover">
						<ul class="left">
							<li style=""><a href="#">الاستفسار عن تصريح حج</a></li>
						</ul>
					</div></div>
				</li>
			</ul>
            
            
            
            
            
            
            
            
            
		</div>
	</li>
	<li class="eservices" id="3">
		<a class="parent" href="#" onMouseOver="setVisibility( sub3 ,  inline );" onMouseOut="setVisibility( sub3 , none );">				
				<i class="homesprite home-mainmenu_eservices"></i> <span>الخدمات الإلكترونية</span>
		</a>
		<div id="sub3" class="sub-nav " style="display:none;" onMouseOver="setVisibility( sub3 ,  inline );" onMouseOut="setVisibility( sub3 , none );">
			<ul class="sector-level" id="sector-level4" style="height:51px !important;">
            
            
            
            
				<li class="civilaffairs"onMouseOver="setVisibility( sub001 ,  inline );"  onMouseOut="setVisibility( sub001 , none );" id="sec-li-7" >
					<h3>الأحوال المدنية</h3>
                    
                    
                    
                    
<div id="sub001" onMouseOver="setVisibility( sub001 ,  inline );" onMouseOut="setVisibility( sub001 , none );" >
<div class="sector-sub sec-li-7 menu-hover">
						<ul class="left">
							<li ><a href="#">الاستعلام عن التأمين الصحي</a>
								</li>
							<li ><a href="#">الاستعلام
									عن أحقية القيام بالحج</a> </li>
							<li ><a href="#">خدمة
									بيـانـاتـي</a> </li>
							<li ><a href="#">حجز
									موعد</a> </li>

							<li ><a href="#">الإبلاغ
									عن الوثائق المفقودة</a> </li>
							<li ><a href="#">خدمة
									تقدير</a> </li>
							<li ><a href="#">خدمة
									طلب و ثيقة بدل فاقد</a> </li>
							<li >
								
							</li>
							<li >
								
							</li>
						</ul>
					</div></div>
                    
                    
                    
                    
                    
                    
				</li>
                
                
                
                
                
<li class="moidiwan" onMouseOver="setVisibility( sub002 ,  inline );"  onMouseOut="setVisibility( sub002 , none );" id="sec-li-7">
					<h3>ديوان وزارة الداخلية</h3>
                    
                    
                    
<div id="sub002" style="display:none;" onMouseOver="setVisibility( sub002 ,  inline );" onMouseOut="setVisibility( sub002 , none );" > 
                   
<div class="sector-sub sec-li-8 menu-hover">
						<ul class="left">
							<li style=""><a href="#">الاستعلام
									عن رصيد مدفوعات الخدمات المتبقي</a> </li>
						</ul>
					</div></div>
				</li>
                
                
                
                
                
<li class="passports" onMouseOver="setVisibility( sub003 ,  inline );"  onMouseOut="setVisibility( sub003 , none );" id="sec-li-7">
					<h3>الجوازات</h3>
                    
                    
<div id="sub003" style="display:none;" onMouseOver="setVisibility( sub003 ,  inline );" onMouseOut="setVisibility( sub003 , none );" >                    
<div class="sector-sub sec-li-9 menu-hover">
						<ul class="left">
							<li style=""><a href="#">خدمات
									التأشيرات</a> </li>
							<li style=""><a href="#">تمديد
									تأشيرة زيارة</a> </li>
							<li style=""><a href="#">
									تجديد الإقامة</a> </li>
							<li style=""><a href="#">خدمات
									التابعين</a> </li>
							<li style=""><a href="#">تصاريح
									السفر للتابعين</a> </li>
							<li style=""><a href="#">إصدار
									الإقامة</a> </li>
							<li style=""><a href="#">نقل
									الخدمات</a> </li>
							<li style=""><a href="#">حجز
									موعد</a> </li>

							<li style=""><a href="#">إصدار جواز السفر</a> </li>
							<li style=""><a href="#">تجديد جواز السفر</a> </li>
							<li style="">
								
							</li>
							<li style="">
								
							</li>
							<li style="">
								
							</li>
							<li style="">
								
							</li>
						</ul>
					</div></div>
				</li>
                
                
                
                
                
<li class="traffic" onMouseOver="setVisibility( sub004 ,  inline );"  onMouseOut="setVisibility( sub004 , none );" id="sec-li-7">
					<h3>المرور</h3>
                    
<div id="sub004" style="display:none;" onMouseOver="setVisibility( sub004 ,  inline );" onMouseOut="setVisibility( sub004 , none );" >                    
<div class="sector-sub sec-li-10 menu-hover">
						<ul class="left">
							<li style=""><a href="#">الاستعلام
									عن وثيقة تأمين لمركبة</a> </li>
							<li style=""><a href="#">اضافة
									مستخدم لمركبة</a> </li>
							<li style=""><a href="#">إلغاء
									مستخدم المركبة</a> </li>
							<li class="" style=""><span class="lebelcolor">طلبات تفويض بإنتظار الموافقة</span> 
								<ul class="sublvl">
									<li><a href="#">طلبات
											تفويض قيادة</a></li>
									<li><a href="#">طلبات
											تفويض مستخدم فعلي</a></li>
								</ul></li>

							<li class="" style=""><span class="lebelcolor">الاستعلام عن تفاويض المركبات</span> 
								<ul class="sublvl">
									<li><a href="#">التفاويض
											على مركبات املكها</a></li>
									<li><a href="#">مركبات
											انا مفوض عليها</a></li>
								</ul></li>
							<li style=""><a href="#">خدمة
									المركبات</a> </li>
							<li style=""><a href="#">تجديد
									رخصة القيادة</a> </li>
						</ul>
					</div></div>
				</li>
<li class="publicsecurity" onMouseOver="setVisibility( sub005 ,  inline );"  onMouseOut="setVisibility( sub005 , none );" id="sec-li-7">
					<h3>الأمن العام</h3>
                    
                    
                    
<div id="sub005" style="display:none;" onMouseOver="setVisibility( sub005 ,  inline );" onMouseOut="setVisibility( sub005 , none );" >                    
<div class="sector-sub sec-li-11 menu-hover">
						<ul class="left">
							<li style=""><a href="#">التبليغ
									عن مشتبه به بالانتماء للفئات الضالة</a> </li>
							<li style=""><a href="#">الاستعلام
									عن رخص السلاح</a> </li>

							<li class="" style=""><span class="lebelcolor">الجرائم الالكترونية</span> 
								<ul class="sublvl">
									<li><a href="#">بلاغ-
											اختراق المواقع الإلكترونية</a></li>
									<li><a href="#">بلاغ-الرسائل
											البريدية الالكترونية</a></li>
									<li><a href="#">بلاغ-المشاركة
											الإلكترونية</a></li>
									<li><a href="#">بلاغ-رسائل
											القنوات الفضائية</a></li>
									<li><a href="#">الرسائل النصية</a></li>
								</ul></li>
							<li style=""><a href="#">متابعة
									البلاغات</a> </li>
						</ul>
					</div></div>
				</li>
<li class="emirates" onMouseOver="setVisibility( sub006 ,  inline );"  onMouseOut="setVisibility( sub006 , none );" id="sec-li-12" style=" display:none;">
					<h3 >الإمارات</h3>
                    
                    
<div class="emirates" id="sub006" style="display:none;" onMouseOver="setVisibility( sub006 ,  inline );" onMouseOut="setVisibility( sub006 , none );" >                    
<div class="sector-sub sec-li-12 menu-hover" >
						<ul class="left" >
							<li class="emirateofjazanprovince" onClick="doHideExp(this);" style="">
								<span class="lebelcolor">إمارة منطقة جازان</span>
								<ul class="sublvl">
									<li class="electronicservices"><a href="#">الخدمات الإلكترونية</a></li>
								</ul>
							</li>
							<li class="emirateofaseerprovince" onClick="doHideExp(this);" style="">
								<span class="lebelcolor">إمارة منطقة عسير</span>
								<ul class="sublvl">
									<li class="electronicservices"><a href="#">الخدمات الإلكترونية</a></li>
								</ul>
							</li>
							<li class="emirateofnajranprovince" onClick="doHideExp(this);" style="">
								<span class="lebelcolor">إمارة منطقة نجران</span>
								<ul class="sublvl">
									<li class="electronicservices"><a href="#">الخدمات الإلكترونية</a></li>
								</ul>
							</li>
							<li class="emirateofeasternprovince" onClick="doHideExp(this);" style="">
								<span class="lebelcolor">إمارة منطقة الشرقية</span>
								<ul class="sublvl">
									<li class="electronicservices"><a href="#">الخدمات الإلكترونية</a></li>
								</ul>
							</li>
							<li class="emirateofriyadhprovince" onClick="doHideExp(this);" style="">
								<span class="lebelcolor">إمارة منطقة الرياض</span>
								<ul class="sublvl">
									<li class="electronicservices"><a href="#">الخدمات الإلكترونية</a></li>
								</ul>
							</li>
							<li class="emirateofmakkahprovince" onClick="doHideExp(this);" style="">
								<span class="lebelcolor">إمارة منطقة مكة المكرمة</span>
								<ul class="sublvl">
									<li class="electronicservices"><a href="#">الخدمات الإلكترونية</a></li>
								</ul>
							</li>
							<li class="emirateofal-jowfprovince" onClick="doHideExp(this);" style="">
								<span class="lebelcolor">إمارة منطقة الجوف</span>
								<ul class="sublvl">
									<li class="electronicservices"><a href="#">الخدمات الإلكترونية</a></li>
								</ul>
							</li>
							<li class="emirateofal-baahaprovince" onClick="doHideExp(this);" style="">
								<span class="lebelcolor">إمارة منطقة الباحة</span>
								<ul class="sublvl">
									<li class="electronicservices"><a href="#">الخدمات الإلكترونية</a></li>
								</ul>
							</li>
							<li class="emirateofal-qasimprovince" onClick="doHideExp(this);" style="">
								<span class="lebelcolor">إمارة منطقة القصيم</span>
								<ul class="sublvl">
									<li class="electronicservices"><a href="#">الخدمات الإلكترونية</a></li>
								</ul>
							</li>
							<li class="emirateofhaelprovince" onClick="doHideExp(this);" style="">
								<span class="lebelcolor">إمارة منطقة حائل</span>
								<ul class="sublvl">
									<li class="electronicservices"><a href="#">الخدمات الإلكترونية</a></li>
								</ul>
							</li>
							<li class="emirateoftaboukprovince" onClick="doHideExp(this);" style="">
								<span class="lebelcolor">إمارة منطقة تبوك</span>
								<ul class="sublvl">
									<li class="electronicservices"><a href="#">الخدمات الإلكترونية</a></li>
								</ul>
							</li>
							<li class="emirateofnorthernborders" onClick="doHideExp(this);" style="">
								<span class="lebelcolor">إمارة منطقة الحدود الشمالية</span>
								<ul class="sublvl">
									<li class="electronicservices"><a href="#">الخدمات الإلكترونية</a></li>
								</ul>
							</li>
							<li class="emirateofal-madinahprovince" onClick="doHideExp(this);" style="">
								<span class="lebelcolor">إمارة منطقة المدينة المنورة</span>
								<ul class="sublvl">
									<li class="electronicclaim" style="display:none;"><a href="#">الإستدعاء
											الإلكتروني</a>
									</li>
									<li class="marriagerequests" style="display:none;">
										<a href="#">طلبات الزواج</a>
									</li>
									<li class="requisitionservices" style="display:none;">
										<a href="#">خدمات الاستدعاء</a>
									</li>
									<li class="inquirerequeststatus" style="display:none;">
										<a href="#">الإستعلام عن طلبات سابقة</a>
									</li>
									<li class="marriage">
										<a href="#">خدمات الزواج</a>
									</li>
									<li class="prisoners">
										<a href="#">خدمات السجناء</a>
									</li>
									<li class="burialandmortality">
										<a href="#">خدمات الدفن والوفيات</a>
									</li>
									<li class="compliants">
										<a href="#">الشكاوى</a>
									</li>
									<li class="otherrequests">
										<a href="#">طلبات أخرى</a>
									</li>
									<li class="inquiryservice">
										<a href="#">خدمة الاستعلام</a>
									</li>
									<li class="electronicservices"><a href="#">الخدمات الإلكترونية</a></li>
								</ul>
							</li>
						</ul>
					</div></div>
				</li>
                
                
                
                
                
<li class="expatriateaffairs" onMouseOver="setVisibility( sub007 ,  inline );"  onMouseOut="setVisibility( sub007 , none );" id="sec-li-7">
					<h3>الإدارة العامة لشؤون الوافدين</h3>
                    
                    
                    
                    
                    
                    
<div id="sub007" style="display:none;" onMouseOver="setVisibility( sub007 ,  inline );" onMouseOut="setVisibility( sub007 , none );" >                    
<div class="sector-sub sec-li-13 menu-hover">
						<ul class="left">
							<li style=""><a href="#">استقدام
									العوائل للمقيمين</a> </li>

							<li style=""><a href="#">حجز
									موعد</a> </li>
						</ul>
					</div></div>
                    
				</li>
                
                
                
<li class="authorization" onMouseOver="setVisibility( sub008 ,  inline );"  onMouseOut="setVisibility( sub008 , none );" id="sec-li-7">
					<h3>تفويض الخدمات الإلكترونية</h3>
                    
                    
                    
<div id="sub008" style="display:none;" onMouseOver="setVisibility( sub008 ,  inline );" onMouseOut="setVisibility( sub008 , none );" >                    
<div class="sector-sub sec-li-14 menu-hover">
						<ul class="left">
							<li style=""><a href="#">تفويض
									الخدمات الإلكترونية</a> </li>
						</ul>
					</div></div>
				</li>
                
                
                
                
                
<li class="postaldeliveryservice" onMouseOver="setVisibility( sub009 ,  inline );"  onMouseOut="setVisibility( sub009 , none );" id="sec-li-7">
					<h3>توصيل الوثائق بالبريد</h3>
                    
 
 
 
 
<div id="sub009" style="display:none;" onMouseOver="setVisibility( sub009 ,  inline );" onMouseOut="setVisibility( sub009 , none );" >                    
<div class="sector-sub sec-li-15 menu-hover">
						<ul class="left">
							<li style=""><a href="#">توصيل
									الوثائق بالبريد</a> </li>
						</ul>
					</div></div>
				</li>
			</ul>
		</div>
	</li>
	<li class="nationals" id="4">
		<a class="parent" href="#">				
				<i class="homesprite home-mainmenu_nationals"></i> <span>المواطنون</span>
		</a>
	</li>
	<li class="expats" id="5">
		<a class="parent" href="#">				
				<i class="homesprite home-mainmenu_expats"></i> <span>المقيمون</span>
		</a>
	</li>
	<li class="emirates" id="6">
		<a class="parent" href="#" onMouseOver="setVisibility( sub4 ,  inline );" onMouseOut="setVisibility( sub4 , none );">				
				<i class="homesprite home-mainmenu_emirates"></i> <span>الإمارات</span>
		</a>
		<div id="sub4" class="sub-nav sub-navSectors" style=" display:none;" onMouseOver="setVisibility( sub4 ,  inline );" onMouseOut="setVisibility( sub4 , none );">
			<ul class="sector-levelSectors">
				<li class="emirateofriyadhprovince "><a href="#">إمارة
						منطقة الرياض</a>
					<ul class="menuSubLevel2">
					</ul></li>
				<li class="emirateofmakkahprovince "><a href="#">إمارة
						منطقة مكة المكرمة</a>
					<ul class="menuSubLevel2">
					</ul></li>
				<li class="emirateofmadinahprovince "><a href="#">إمارة
						منطقة المدينة المنورة</a>
					<ul class="menuSubLevel2">
					</ul></li>
				<li class="emirateofeasternprovince "><a href="#">إمارة
						المنطقة الشرقية</a>
					<ul class="menuSubLevel2">
					</ul></li>
				<li class="emirateofal-jowfprovince "><a href="#">إمارة
						منطقة الجوف</a>
					<ul class="menuSubLevel2">
					</ul></li>
				<li class="emirateofal-baahaprovince "><a href="#">إمارة
						منطقة الباحة</a>
					<ul class="menuSubLevel2">
					</ul></li>
				<li class="emirateofaseerprovince "><a href="#">إمارة
						منطقة عسير</a>
					<ul class="menuSubLevel2">
					</ul></li>
				<li class="emirateofal-qasimprovince "><a href="#">إمارة
						منطقة القصيم</a>
					<ul class="menuSubLevel2">
					</ul></li>
				<li class="emirateofhaelprovince "><a href="#">إمارة
						منطقة حائل</a>
					<ul class="menuSubLevel2">
					</ul></li>
				<li class="emirateoftaboukprovince "><a href="#">إمارة
						منطقة تبوك</a>
					<ul class="menuSubLevel2">
					</ul></li>
				<li class="emirateofnorthernbordersprovince "><a href="#">إمارة
						منطقة الحدود الشمالية</a>
					<ul class="menuSubLevel2">
					</ul></li>
				<li class="emirateofjazanprovince "><a href="#">إمارة
						منطقة جازان</a>
					<ul class="menuSubLevel2">
					</ul></li>
				<li class="emirateofnajranprovince "><a href="#">إمارة
						منطقة نجران</a>
					<ul class="menuSubLevel2">
					</ul></li>
			</ul>
		</div>
	</li>
	<li class="sectors" id="7">
		<a class="parent" href="#" onMouseOver="setVisibility( sub5 ,  inline );" onMouseOut="setVisibility( sub5 , none );">
				<i class="homesprite home-mainmenu_sectors"></i> <span>القطاعات</span>
		</a>
		<div id="sub5" class="sub-nav sub-navSectors" style="display:none;" onMouseOver="setVisibility( sub5 ,  inline );" onMouseOut="setVisibility( sub5 , none );">
			<ul class="sector-levelSectors">
				<li class="moidiwan " style="height:auto"><a href="#">ديوان الوزارة</a>
					<ul class="menuSubLevel2">
						<li><a href="#">الإدارة
								العامة للشؤون العسكرية</a> 
							<ul class="sublvl">
							</ul></li>
						<li><a href="#">شؤون
								المناطق</a> 
							<ul class="sublvl">
							</ul></li>
						<li><a href="#">شؤون
								الوافدين</a> 
							<ul class="sublvl">
							</ul></li>
					</ul></li>
				<li class="publicsecurity " style="height:225px">
					<a href="#">الأمن
						العام</a>
					<ul class="menuSubLevel2">
						<li><a href="#">المديرية
								العامة </a> 
							<ul class="sublvl">
							</ul></li>
						<li><a href="#">الإدارة العامة للمرور</a>
							
							<ul class="sublvl">
								<li><a href="#">مرور
										الرياض</a></li>
								<li><a href="#">مرور
										المدينة المنورة</a></li>
							</ul></li>
						<li><a href="#">الشرطة</a>
							
							<ul class="sublvl">
								<li><a href="#">شرطة
										الرياض</a></li>
								<li><a href="#">شرطة
										المدينة المنورة</a></li>
								<li><a href="#">شرطة
										المنطقة الشرقية</a></li>
							</ul></li>
					</ul>
				</li>
				<li class="civildefence " style="height:74px;"><a href="#">الدفاع
						المدني</a>
					<ul class="menuSubLevel2">
						<li><a href="#">الدفاع
								المدني بالمدينة المنورة </a> 
							<ul class="sub">
							</ul></li>
					</ul></li>
				<li class="specialforces "><a href="#">قوات
						الأمن الخاصة</a>
					<ul class="menuSubLevel2">
					</ul></li>
				<li class="investigationoffice " style="border-right: 1px solid #d3d3d3;"><a href="#">المباحث
						العامة</a>
					<ul class="menuSubLevel2">
					</ul></li>
				<li class="passports"><a href="#">الجوازات</a>
					<ul class="menuSubLevel2">
					</ul></li>
				<li class="civilaffairs "><a href="#">الأحوال
						المدنية</a>
					<ul class="menuSubLevel2">
					</ul></li>
				<li class="kfsc "><a href="#">الكلية
						الأمنية</a>
					<ul class="menuSubLevel2">
					</ul></li>
				<li class="agencyforplanningandsecuritydevelopment " style=""><a href="#">وكالة الوزارة للتخطيط والتطويرالأمني</a>
					<ul class="menuSubLevel2">
					</ul></li>					
				<li class="prisons "><a href="#">السجون</a>
					<ul class="menuSubLevel2">
					</ul></li>
				<li class="nationalinformationcenter " style="height:75px;"><a href="#">مركز
						المعلومات الوطني</a>
					<ul class="menuSubLevel2">
					</ul></li>
				<li class="nationalcenterforsecurityoperations "><a href="#">المركز الوطني للعمليات الأمنية</a>
					<ul class="menuSubLevel2">
					</ul></li>
				<li class="ideologicalsecurity "><a href="#">الأمن
						الفكري</a>
					<ul class="menuSubLevel2">
					</ul></li>
				<li class="crimeresearch "><a href="#">أبحاث
						الجريمة</a>
					<ul class="menuSubLevel2">
					</ul></li>
				<li class="premisessecurity "><a href="#"> أمن المنشأت</a>
					<ul class="menuSubLevel2">
					</ul></li>
				<li class="developmentprojects "><a href="#">المشروعات
						التطويرية</a>
					<ul class="menuSubLevel2">
					</ul></li>
				<li class="saudiinterpol "><a href="#">الانتربول
						السعودي</a>
					<ul class="menuSubLevel2">
					</ul></li>
				<li class="narcoticscontrol "><a href="#">مكافحة
						المخدرات</a>
					<ul class="menuSubLevel2">
					</ul></li>
				<li class="financialinvestigation "><a href="#">التحريات
						المالية</a>
					<ul class="menuSubLevel2">
					</ul></li>
				<li class="borderguards "><a href="#">حرس
						الحدود </a>
					<ul class="menuSubLevel2">
					</ul></li>
				<li class="mujahideen "><a href="#">المجاهدين</a>
					<ul class="menuSubLevel2">
					</ul></li>
				<li class="medicalservices "><a href="#">الخدمات
						الطبية </a>
					<ul class="menuSubLevel2">
					</ul></li>
				<li class="officersclub "><a href="#">نادي
						الضباط</a>
					<ul class="menuSubLevel2">
					</ul></li>
				<li class="weaponsdepartment "><a href="#">الأسلحة
						والمتفجرات</a>
					<ul class="menuSubLevel2">
					</ul></li>
				<li class="generalsecurityaviationcommand "><a href="#">القيادة
						العامة لطيران الأمن</a>
					<ul class="menuSubLevel2">
					</ul></li>
				<li class="industrialsecurity "><a href="#">الهيئة العليا للأمن الصناعي</a></li>
			</ul>
		</div>
	</li>
	<li class="business" id="8">
		<a class="parent" href="#">				
				<i class="homesprite home-mainmenu_business"></i> <span>الأعمال</span>
		</a>
	</li>
	<li class="employment" id="9">
		<a class="parent" href="#">
				<i class="homesprite home-mainmenu_employment"></i> <span>التوظيف</span>
		</a>
	</li>
</ul>
</div>
</div>
<script language="JavaScript">
function setVisibility(id, visibility) {
document.getElementById(id).style.display = visibility;
}
</script><!-- نهاية القائمة -->

	

 <div class="container row">
			









<table class="layoutRow ibmDndRow component-container " cellpadding="0" cellspacing="0" role="presentation">
	<tr>

        
            

		<td valign="top" >
            









<table class="layoutColumn ibmDndColumn component-container id-Z7_9QGCHH42KG1A60AI72O0I51GI1 layoutNode" cellpadding="0" cellspacing="0" role="presentation">
	
	<tr>
		<td style="width:100%;" valign="top">
			<div class= component-control id-Z7_9QGCHH42KG1A60AI72O0I51GA4  ><!--customSkin2-->





































    
    

    
    

    
    
    





    
    
        
            
            <div class="container-wcm row">
<style>
@media screen and (max-width: 759px) {

div.gitex-banner{
 display: block !important;
 visibility: visible !important;
 background: none !important;
 margin: 0 !important;
 padding: 5px 0 !important;
 border-left: 0 !important;
 border-right: 0 !important;
}


}
</style>

<!-- main -->

			<div class="main pull-left">
			
		<!-- banner-->
				<div class="banner">
					<!-- slides-->
					<div id="slides">

<img src="images/1-ar.jpg" alt=""  title="">

<img src="images/2-ar.jpg" alt=""  title="">

<img src="images/3-ar.jpg" alt=""  title="">

<img src="images/4-ar.jpg" alt=""  title="">



					</div>
					<!-- /slides-->
					
					<!-- caption-->
				    <div class="caption">
				    	<h2>مرحباً</h2>
				    	<p>ماذا تريد أن تفعل اليوم؟</p>
				    </div>
				    <!-- /caption-->
				    
				   <h4 class="popular">الأكثر انتشارا </h4>
				   <!-- slidesjs-pagination-->
				   
				   
			<ul class="slidesjs-pagination" style="display:none;">
			
			<li class="slidesjs-pagination-item">
			<a title="" target="" href="#">قنوات بنكية لتفعيل حسابك</a>
							</li>
	
		

	<li class="slidesjs-pagination-item">
		<a href="#"  data-slidesjs-item="2" class="">تم نقل منصة التوظيف </a></li>





	<li class="slidesjs-pagination-item">
		<a href="#" data-slidesjs-item="2" class="">تم نقل منصة أبشر</a></li>
		
							
	
	<li class="slidesjs-pagination-item">
		<a href="#" data-slidesjs-item="2" class="">
 الوقاية من كورونا</a></li>
							

						</ul>
						<!-- /slidesjs-pagination-->
					
				</div>
				<!--/ banner -->




<div class="separator"></div>

 
</div>



        
        
    

    
        





        







    
 </div>
		</td>
	</tr>
	
	<tr>
		<td style="width:100%;" valign="top">
			<div class= component-control id-Z7_9QGCHH42KG1A60AI72O0I51GA6  ><!--customSkin2-->





































    
    

    
    

    
    
    





    
    
        
            
            <div class="container-wcm row">
<div class="rowsec">
	<div class="service-group pull-left">

		<!-- service-block 2 -->

<!-- service-block -->
<div class="service-block pull-left diwan">
	<i class="homesprite home-business pull-right"></i>
	<h4>
		<a title="" target="" href="javascript:;"><span class="arrow"></span></a>
	</h4>
	<ul class="tmp mlist">
<li>
<a href="#">



الاستعلام العام عن رصيد مدفوعات الخدمات المتبقي


</a>

</li><li>
<a href="#">



الاستعلام عن التعاميم


</a>

</li><li>
<a href="public.html">



الاستعلام العام عن طلبات التصاريح 


</a>

</li><li>
<a href="#">



الاستعلام العام عن المعاملات


</a>

</li>
	</ul>

</div>
<!-- /service-block -->

		<!-- /service-block 2 -->
		<!-- service-block 3 -->

<div class="service-block pull-right last passport">
	<i class="homesprite home-passport pull-right"></i>
	<h4>
		<a title="" target="" href="javascript:;"><span class="arrow"></span></a>
	</h4>
	<ul class="mlist"><li>
<a href="#">



خدمات التأشيرات


</a>

</li><li>
<a href="#">



تجديد الإقامة


</a>

</li><li>
<a href="#">



إصدار الإقامة


</a>

</li><li>
<a href="#">



تصاريح السفر للتابعين


</a>

</li><li>
<a href="#">



تجديد الجواز


</a>

</li><li>
<a href="#">



إصدار الجواز


</a>

</li><li>
<a href="#">



تمديد تأشيرة زيارة


</a>

</li><li>
<a href="#">



التبليغ عن تغيب العمالة المنزلية


</a>

</li><li>
<a href="#">



تفويض استلام القادمات للعمل 


</a>

</li><li>
<a href="#">



تمديد تأشيرة الزيارة الاستثنائية لليمنيين


</a>

</li><li>
<a href="#">



نقل الخدمات


</a>

</li><li>
<a href="#">



تعديل المهنة


</a>

</li><li>
<a href="#">



خدمات التابعين


</a>

</li><li>
<a href="#">



الجواز مسجل مسبقا لنفس الجنسية


</a>

</li><li>
<a href="#">



معلومات سجل السفر


</a>

</li><li>
<a href="#">



معلومات جواز السفر


</a>

</li><li>
<a href="#">



الاستعلام عن تفاويض استلام القادمات للعمل


</a>

</li><li>
<a href="#">



معلومات العنوان


</a>

</li><li>
<a href="#">



المعلومات الشخصية


</a>

</li><li>
<a href="#">



اﻻستعلام العام عن البصمة


</a>

</li><li>
<a href="#">



الاستعلام العام عن أحقية القيام بالحج


</a>

</li><li>
<a href="#">



الاستعلام العام عن صلاحية التأمين الصحي للمقيمين فقط


</a>

</li><li>
<a href="#">



الاستعلام العام عن حالة تأشيرة خروج وعودة


</a>

</li><li>
<a href="#">



الاستعلام عن وصول العمالة


</a>

</li><li>
<a href="iqamaa_search.html">



الاستعلام عن صلاحية الإقامة


</a>

</li><li>
<a href="#">



الاستعلام عن العمالة الجديدة والزائرين


</a>

</li></ul>
</div>

		<!-- /service-block 3 -->
	</div>
	<div class="service-group last pull-left">
		<!-- service-block 4 -->

<div class="service-block pull-left traffic">
	<i class="homesprite home-traffic pull-right"></i>
	<h4>
		<a title="" target="" href="javascript:;"><span class="arrow"></span></a>
	</h4>
	<ul class="mlist"><li>
<a href="#">



خدمة المركبات


</a>

</li><li>
<a href="#">



إضافة مستخدم لمركبة


</a>

</li><li>
<a href="#">



تجديد إستمارة المركبة 


</a>

</li><li>
<a href="#">



تجديد رخصة القيادة


</a>

</li><li>
<a href="#">



إلغاء مستخدم لمركبة


</a>

</li><li>
<a href="#">



طلبات تفويض قيادة بإنتظار الموافقة


</a>

</li><li>
<a href="#">



طلبات تفويض مستخدم فعلي بإنتظار الموافقة


</a>

</li><li>
<a href="#">



الإستعلام عن تفاويض مركبات أملكها 


</a>

</li><li>
<a href="#">



الإستعلام على مركبات أنا مفوض عليها


</a>

</li><li>
<a href="#">



معلومات رخصة القيادة


</a>

</li><li>
<a href="#">



الاستعلام عن المخالفات المرورية


</a>

</li><li>
<a href="#">



الاستعلام العام عن صلاحية التأمين على المركبات


</a>

</li><li>
<a href="#">



التفاويض على مركبات أملكها


</a>

</li><li>
<a href="#">



الاستعلام عن تفاصيل المخالفة المرورية


</a>

</li><li>
<a href="#">



مركبات انا مفوض عليها


</a>

</li></ul>
</div>

		<!-- /service-block 4 -->

		<!-- service-block 1 -->

<div class="service-block pull-right last civil">
	<i class="homesprite home-civil pull-right"></i>
	<h4>
		<a title="" target="" href="javascript:;"><span class="arrow"></span></a>
	</h4>
	<ul class="mlist"><li>
<a href="#">



خدمة بيـانـاتـي


</a>

</li><li>
<a href="#">



الإبلاغ عن الوثائق المفقودة


</a>

</li><li>
<a href="#">



الاستعلام عن معاملة

</a>

</li><li>
<a href="#">



حجز موعد


</a>

</li><li>
<a href="#">



خدمة التعريف بتابع


</a>

</li><li>
<a href="#">



خدمة تقدير


</a>

</li><li>
<a href="#">



الاستعلام عن التأمين الصحي


</a>

</li><li>
<a href="#">



معلومات العنوان


</a>

</li><li>
<a href="#">



المعلومات الشخصية


</a>

</li><li>
<a href="#">



خدمة تحسين


</a>

</li><li>
<a href="#">



حجز موعد


</a>

</li><li>
<a href="#">



الاستعلام العام عن أحقية القيام بالحج


</a>

</li><li>
<a href="#">



خدمة التحقق من صلاحية الهوية


</a>

</li></ul>
</div>

		<!-- /service-block 1 -->

	</div>
</div>

<style>.toggleable:nth-last-child(2){display:none !important;}</style>


					
<script language="javascript" type="text/javascript">
//<![CDATA[

var listlenghts = {"one":5, "two":5, "three":5, "four":5, "five":5, "six":5};

var expandable = true ;

var services_sector_names = 
{
"block2":"الجوازات", "block3":"المرور"
, "block4":"الأحوال المدنية", "block1":"ديوان الوزارة"
} ;	

$(document).ready(function(){

//altering the name of eServices list headers
$( div.rowsec div div h4 a ).each(function(index){
try{
tempSectorTitle = services_sector_names["block"+(index+1)] ;
if(typeof tempSectorTitle !=  undefined )
$(this).html(tempSectorTitle +  <span class="arrow"></span> );
}
catch(nex){
//alert(nex)
}
});

var expander_text = "More"
var collapse_text = "Less"
var  lnk_start =  <a title="" target="" href="javascript:;">  ;
var lnk_end =  </a>  ;

expander_text = "المزيد" ;
collapse_text = "أقل"


try
{
		listlenghts = $.map(listlenghts, function(el) { return el; });
		$( ul.mlist ).each(function(index){
		  var LiN = $(this).find( li ).length;
		  if( LiN > listlenghts[index]){    
			$( li , this).eq(listlenghts[index] - 1).nextAll().hide().addClass( toggleable );
if(expandable)
{
$(this).append( <li class="more moreLessLink">  + lnk_start + expander_text + lnk_end +  </li> );
}
		  }
		});
		
		//$( ul.mlist ).on( click , .more , function(){
                $( ul.mlist .more ).click(function(){
		if( $(this).hasClass( less ) ){    
			$(this).html(lnk_start + expander_text + lnk_end).removeClass( less );    
		}else{
			$(this).html(lnk_start + collapse_text + lnk_end).addClass( less ); 
		}

			$(this).siblings( li.toggleable ).slideToggle();

		});
}catch(pex)
{
		//alert(pex);
}	
})
//]]>
</script>
 
</div>



        
        
    

    
        





        







    
 </div>
		</td>
	</tr>
	
	<tr>
		<td style="width:100%;" valign="top">
			<div class= component-control id-Z7_9QGCHH42KG1A60AI72O0I51GA5  ><!--customSkin2-->





































    
    

    
    

    
    
    





    
    
        
            
            <div class="container-wcm row">
				<!-- /service container -->
				<div class="all-services">
                <div class="separator"></div>
                <div class="row" id="moi-service-down-banner"><a href="#">

<img src="images/baneer-221.jpg" alt=""  title=""></a></div></div>


<div class="separator"></div>






					
				
				<div class="row">
				
					<!-- schedule-appt -->
					<div class="schedule-appt pull-left collapse-block">
					
						<span class="schedule-need pull-left collapse-toggle ">احجز موعداً<span class="arrow">حدد موعدك مع أحد قطاعات الوزارة في الوقت والمكان المناسبين.</span></span>
						
<span class="schedule-make pull-left collapse-block-content ">
							
                            
                            
                            
                            
                            
                            
                             <a title="" target="" href="#"><span class="link">الأحوال المدنية</span></a>
                            <a title="" target="" href="#"><span class="link">الجوازات</span></a>
                            
                            <a title="" target="" href="#"><span class="link">استقدام العوائل</span></a>
						
							<a title="" target="" href="#"><span class="link">تصاريح الأسلحة</span></a>
							</span>
					</div>
					<!-- /schedule-appt -->
					<div class="not-sure-block pull-left  collapse-block">
						<!-- not-sure -->
<div class="not-sure pull-left collapse-toggle">
<a style="padding:0px; margin:0px" title="" target="" href="#"  class="moi-activate row pull-right">
مراكز التسجيل والتفعيل &nbsp; &nbsp;

<!--
يمكنك  تفعيل حسابك على الخدمات الإلكترونية من خلال أجهزة الخدمة الذاتية أو البنوك أو مراكز التفعيل. 
-->
<br><br>
<span class="link pull-right">المزيد...<span class="arrow"></span></span>
</a>


</div>
						<!-- /not-sure -->
						
						<!-- get-help -->
						<div class="get-help pull-right collapse-block-content">
							<h5>
<!-- a href="?1dmy&amp;mapping=%2FHome%2FHome%2Fdp-home&amp;urile=wcm%3apath%3a%2FGeneral%2FHelp%2BAR%2FPortal%2BHelp%2FHLP_Portal_%2BHelp_Default_AR"></a -->
المساعدة
</h5>
							<ul>
								<li><a href="#">

المساعدة لتسجيل وتفعيل حسابك</a></li>

								
					
								<li><a href="#" >كيف نساعدك عبر الهاتف أو البريد الإلكتروني.</a></li>
							</ul>
						</div>
						<!-- /get-help -->
					</div>
				</div>
 
</div>



        
        
    

    
        





        







    
 </div>
		</td>
	</tr>
	
	<tr>
		<td style="width:100%;" valign="top">
			<div class= component-control id-Z7_9QGCHH42KG1A60AI72O0I51GA7  ><!--customSkin2-->





































    
    

    
    

    
    
    





    
    
        
            
            <div class="container-wcm row">
<div class="row eservice-block collapse-block">
					<a class="eservice-reg pull-left collapse-toggle" href="#">سجل للحصول على الخدمات الإلكترونية، ولتتمكن من الوصول إلى جميع الخدمات بسهولة وفي أي وقت.<span class="arrow"></span></a>
					
					<!-- eservice-info -->
					<div class="eservice-info pull-right collapse-block-content">
						<h5>هناك الكثير من الأشياء التي يمكنك القيام بها بسهولة بمجرد تسجيلك:</h5>
						<ul>
							<li>إنجاز الكثير من الأعمال التي كانت تستغرق وقتاً طويلاً في دقائق.</li>
							<li>استقبال التنبيهات عندما تتطلب الأمور انتباهكم.</li>
							<li>خدمة التقدم للوظائف إلكترونياً وتقديم الشكاوى والبلاغات.</li>
						</ul>
					</div>
					<!-- /eservice-info -->
				</div>
		</div>
 
</div>



        
        
    

    
        





        







    
 </div>
		</td>
	</tr>
	 
</table>
		</td>

        
            

		<td valign="top" >
            









<table class="layoutColumn ibmDndColumn component-container id-Z7_9QGCHH42KG1A60AI72O0I51GI5 layoutNode" cellpadding="0" cellspacing="0" role="presentation">
	
	<tr>
		<td style="width:100%;" valign="top">
			<div class= component-control id-Z7_9QGCHH42KG1A60AI72O0I51GQ4  ><!--customSkin2-->





































    
    

    
    

    
    
    


    
        
            
            <div class="container-wcm row">
<div class="sidebar pull-right">
    <!-- headline new ticker -->
    <div class="news-ticker">
       <ul><li id="1">           
    <a href="#">			 
     <h3> مجلس الوزراء يعقد جلسته ـ عبر الاتصال المرئي ـ برئاسة خادم الحرمين الشريفين
</h3>
    </a>
<span id= pdate_1 ></span>

   <img src="images/281x179_19.jpg" width="260" height="168">
   <p>عقد مجلس الوزراء، جلسته اليوم ــ عبر الاتصال المرئي ــ برئاسة خادم الحرمين الشريفين الملك سلمان بن عبد العزيز آل سعود، رئيس مجلس الوزراء ـ حفظه الله ـ. . 
     <a class="more" href="#">
المزيد <span class="arrow"></span></a>
   </p>

<script>


var year =  ٢٠٢٢  ;
var month =  ٠١  ;
var day =  ١٦  ;

var engmonth="";
var engyear="";
var engday="";

switch (year)
{
case "٢٠٠٦":engyear = "2006";break;case "٢٠٠٧":engyear = "2007";break;case "٢٠٠٨":engyear = "2008";break;
case "٢٠٠٩":engyear = "2009";break;case "٢٠١٠":engyear = "2010";break;case "٢٠١١":engyear = "2011";break;
case "٢٠١٢":engyear = "2012";break;case "٢٠١٣":engyear = "2013";break;case "٢٠١٤":engyear = "2014";break;
case "٢٠١٥":engyear = "2015";break;
case "٢٠١٦":engyear = "2016";break;case "٢٠١٧":engyear = "2017";break;case "٢٠١٨":engyear = "2018";break;
default:engyear = "2022";
}

switch (month)
{
case "٠١":engmonth = "01";break;case "٠٢":engmonth = "02";break;case "٠٣":engmonth = "03";break;case "٠٤":engmonth = "04";break;case "٠٥":engmonth = "05";break;
case "٠٦":engmonth = "06";break;case "٠٧":engmonth = "07";break;case "٠٨":engmonth = "08";break;case "٠٩":engmonth = "09";break;case "١٠":engmonth = "10";break;
case "١١":engmonth = "11";break;case "١٢":engmonth = "12";break;
default:engmonth = "12";
}

switch (day)
{
case "٠١":engday = "01";break;case "٠٢":engday = "02";break;case "٠٣":engday = "03";break;case "٠٤":engday = "04";break;case "٠٥":engday = "05";break;
case "٠٦":engday = "06";break;case "٠٧":engday = "07";break;case "٠٨":engday = "08";break;case "٠٩":engday = "09";break;case "١٠":engday = "10";break;
case "١١":engday = "11";break;case "١٢":engday = "12";break;case "١٣":engday = "13";break;case "١٤":engday = "14";break;case "١٥":engday = "15";break;
case "١٦":engday = "16";break;case "١٧":engday = "17";break;case "١٨":engday = "18";break;case "١٩":engday = "19";break;case "٢٠":engday = "20";break;
case "٢١":engday = "21";break;case "٢٢":engday = "22";break;case "٢٣":engday = "23";break;case "٢٤":engday = "24";break;case "٢٥":engday = "25";break;
case "٢٦":engday = "26";break;case "٢٧":engday = "27";break;case "٢٨":engday = "28";break;case "٢٩":engday = "29";break;case "٣٠":engday = "30";break;
case "٣١":engday = "31";break;
default:
  engday = "03";
}

updateFromGregorian(engyear,engmonth,engday,  pdate_1 );


</script>
</li>


<li id="2">           
    <a href="#">			 
     <h3>مكتب تحقيق الرؤية بوزارة الداخلية ينظم ورشة عمل توعوية عن مؤشرات  الأداء في الوزارة وقطاعاتها</h3>
    </a>
<span id= pdate_2 ></span>

   <img src="#" width="260" height="168">
   <p>نظم مكتب تحقيق الرؤية بوزارة الداخلية اليوم الخميس الموافق 15 محرم 1442هـ ورشة عمل توعوية عن مؤشرات  الأداء في الوزارة وقطاعاتها ، بحضور 122 مشارك ، ويأتي ذلك في إطار الشراكة الاستراتيجية بين المكتب والمركز الوطني . 
     <a class="more" href="#">
المزيد <span class="arrow"></span></a>
   </p>

<script>


var year =  ٢٠٢٢  ;
var month =  ٠١  ;
var day =  ١٥  ;

var engmonth="";
var engyear="";
var engday="";

switch (year)
{
case "٢٠٠٦":engyear = "2006";break;case "٢٠٠٧":engyear = "2007";break;case "٢٠٠٨":engyear = "2008";break;

case "٢٠٠٩":engyear = "2009";break;case "٢٠١٠":engyear = "2010";break;case "٢٠١١":engyear = "2011";break;
case "٢٠١٢":engyear = "2012";break;case "٢٠١٣":engyear = "2013";break;case "٢٠١٤":engyear = "2014";break;
case "٢٠١٥":engyear = "2015";break;
case "٢٠١٦":engyear = "2016";break;case "٢٠١٧":engyear = "2017";break;case "٢٠١٨":engyear = "2018";break;
default:engyear = "2022";
}

switch (month)
{
case "٠١":engmonth = "01";break;case "٠٢":engmonth = "02";break;case "٠٣":engmonth = "03";break;case "٠٤":engmonth = "04";break;case "٠٥":engmonth = "05";break;
case "٠٦":engmonth = "06";break;case "٠٧":engmonth = "07";break;case "٠٨":engmonth = "08";break;case "٠٩":engmonth = "09";break;case "١٠":engmonth = "10";break;
case "١١":engmonth = "11";break;case "١٢":engmonth = "12";break;
default:engmonth = "12";
}

switch (day)
{
case "٠١":engday = "01";break;case "٠٢":engday = "02";break;case "٠٣":engday = "03";break;case "٠٤":engday = "04";break;case "٠٥":engday = "05";break;
case "٠٦":engday = "06";break;case "٠٧":engday = "07";break;case "٠٨":engday = "08";break;case "٠٩":engday = "09";break;case "١٠":engday = "10";break;
case "١١":engday = "11";break;case "١٢":engday = "12";break;case "١٣":engday = "13";break;case "١٤":engday = "14";break;case "١٥":engday = "15";break;
case "١٦":engday = "16";break;case "١٧":engday = "17";break;case "١٨":engday = "18";break;case "١٩":engday = "19";break;case "٢٠":engday = "20";break;
case "٢١":engday = "21";break;case "٢٢":engday = "22";break;case "٢٣":engday = "23";break;case "٢٤":engday = "24";break;case "٢٥":engday = "25";break;
case "٢٦":engday = "26";break;case "٢٧":engday = "27";break;case "٢٨":engday = "28";break;case "٢٩":engday = "29";break;case "٣٠":engday = "30";break;
case "٣١":engday = "31";break;
default:
  engday = "03";
}

updateFromGregorian(engyear,engmonth,engday,  pdate_2 );


</script>
</li>


<li id="3">           
    <a href="#">			 
     <h3>مجلس الوزراء يعقد جلسته ـ عبر الاتصال المرئي ـ برئاسة خادم الحرمين الشريفين</h3>
    </a>
<span id= pdate_3 ></span>

   <img src="images/281x179_17.html" width="260" height="168">
   <p>عقد مجلس الوزراء، جلسته اليوم ــ عبر الاتصال المرئي ــ برئاسة خادم الحرمين الشريفين الملك سلمان بن عبد العزيز آل سعود، رئيس مجلس الوزراء ـ حفظه الله ـ.. . 
     <a class="more" href="#">
المزيد <span class="arrow"></span></a>
   </p>

<script>


var year =  ٢٠٢٢  ;
var month =  ٠١  ;
var day =  ١٦  ;

var engmonth="";
var engyear="";
var engday="";

switch (year)
{
case "٢٠٠٦":engyear = "2006";break;case "٢٠٠٧":engyear = "2007";break;case "٢٠٠٨":engyear = "2008";break;
case "٢٠٠٩":engyear = "2009";break;case "٢٠١٠":engyear = "2010";break;case "٢٠١١":engyear = "2011";break;
case "٢٠١٢":engyear = "2012";break;case "٢٠١٣":engyear = "2013";break;case "٢٠١٤":engyear = "2014";break;
case "٢٠١٥":engyear = "2015";break;
case "٢٠١٦":engyear = "2016";break;case "٢٠١٧":engyear = "2017";break;case "٢٠١٨":engyear = "2018";break;
default:engyear = "2022";
}

switch (month)
{
case "٠١":engmonth = "01";break;case "٠٢":engmonth = "02";break;case "٠٣":engmonth = "03";break;case "٠٤":engmonth = "04";break;case "٠٥":engmonth = "05";break;
case "٠٦":engmonth = "06";break;case "٠٧":engmonth = "07";break;case "٠٨":engmonth = "08";break;case "٠٩":engmonth = "09";break;case "١٠":engmonth = "10";break;
case "١١":engmonth = "11";break;case "١٢":engmonth = "12";break;
default:engmonth = "12";
}

switch (day)
{
case "٠١":engday = "01";break;case "٠٢":engday = "02";break;case "٠٣":engday = "03";break;case "٠٤":engday = "04";break;case "٠٥":engday = "05";break;
case "٠٦":engday = "06";break;case "٠٧":engday = "07";break;case "٠٨":engday = "08";break;case "٠٩":engday = "09";break;case "١٠":engday = "10";break;
case "١١":engday = "11";break;case "١٢":engday = "12";break;case "١٣":engday = "13";break;case "١٤":engday = "14";break;case "١٥":engday = "15";break;
case "١٦":engday = "16";break;case "١٧":engday = "17";break;case "١٨":engday = "18";break;case "١٩":engday = "19";break;case "٢٠":engday = "20";break;
case "٢١":engday = "21";break;case "٢٢":engday = "22";break;case "٢٣":engday = "23";break;case "٢٤":engday = "24";break;case "٢٥":engday = "25";break;
case "٢٦":engday = "26";break;case "٢٧":engday = "27";break;case "٢٨":engday = "28";break;case "٢٩":engday = "29";break;case "٣٠":engday = "30";break;
case "٣١":engday = "31";break;
default:
  engday = "03";
}

updateFromGregorian(engyear,engmonth,engday,  pdate_3 );


</script>
</li>


   </ul>  
</div>
<div class="controls">
   <a title="" target="" href="javascript:;" class="control_prev pull-left">&lt;</a>
   <span class="count pull-left">
        <span id="current"></span>من<span id="total"></span>
   </span>
   <a title="" target="" href="javascript:;" class="control_next pull-left">&gt;</a>
</div>




 
</div>



        
        
    

    
        





        







    
 </div>
		</td>
	</tr>
	
	<tr>
		<td style="width:100%;" valign="top">
			<div class= component-control id-Z7_9QGCHH42KG1A60AI72O0I51GQ6  ><!--customSkin2-->





































    
    

    
    

    
    
    





    
    
        
            
            <div class="container-wcm row">
<div class="separator"></div>
<div class="events_box">

    <div class="events_box_header">

		
<div class="events_box_heading pull-left">تصريحات المتحدث الأمني</div>

		
<div class="events_box_link pull-right">
<a title="" target="" href="#" />استعراض الكل</a></div>
		<div class="events_box_body">
			<img " src="images/2.jpg" alt="thumbnail" width="80" height="51" align="right" style="margin-left:3px" />

<span style="font-weight:bold;"><h4> مقتل المطلوب عبدالله بن ميرزا القلاف</h4></span>

<div class="bodytext" display:block" id= pdate_1.1 ></div>
الأربعاء 7 محرم 1442<span>
صرح مصدر مسؤول برئاسة أمن الدولة بأنه نتيجة لعمليات الرصد والمتابعة الأمنية للعناصر الإرهابية ببلدة العوامية بمحافظة القطيف، فقد رصدت الجهات الأمنية</span>
<div class="more_link pull-right">
<a href="#">المزيد...</a>
</div>

</div> <!--events_box_body ends -->
</div>        




<div class="sidebar pull-right">

<a title="" target="" href="#">

<img src="images/911_w260_Ar.jpg" alt=""  title="">

</a>

</div>








<div class="sidebar pull-right">
<br>
<a title="" target="" href="#">

<img src="images/resault1_ar.jpg" alt="" width="260"  title="">

</a>

</div>








    <div class="news-list events_box" style="width:260px; height:165px !important">
		<div class="events_box_header">
			<div class="events_box_heading pull-left">فعاليات وأحداث</div>
                        <div class="events_box_link pull-right">
<a title="" target="" href="#" />استعراض الكل</a>
</div>
		</div>
	
		<ul style="width:auto !important; height:165px !important" ><li id="1">
<div class="grid-col-container">							
<div class="grid-col1-3">
<img src="images/moi-logo_event.jpg" alt="Event Thumbnail" width="65" height="65"></div>
<div class="grid-col2-3">
<h4 style="font-weight: bold !important"><a style="color: #352A25 !important" href="#">المنتدى السعودي الأول لأعمال التطوع</a></h4>
<div class="bodytext" display:block" id= eventdate_1.1 ></div>
الأربعاء 7 محرم 1442</div>

</div>
<div class="more_link pull-right"><a href="#">





المزيد... </a>


</div>
		 						
</li>


<li id="2">
<div class="grid-col-container">							
<div class="grid-col1-3">
<img src="images/logo2_event.jpg" alt="Event Thumbnail" width="65" height="65"></div>
<div class="grid-col2-3">
<h4 style="font-weight: bold !important"><a style="color: #352A25 !important" href="#">حفل تكريم متقاعدي وزارة الداخلية </a></h4>
<div class="bodytext" display:block" id= eventdate_1.2 ></div>
الأربعاء 7 محرم 1442</div>

</div>
<div class="more_link pull-right"><a href="#">المزيد... </a>


</div>
		 						
</li>


</ul>  
</div>
<div class="controls">
	<a title="" target="" href="javascript:;" class="control_prev_events pull-left">&lt;</a>

	<span class="count pull-left"><span id="event_current"></span>  من <span id="event_total"></span></span>

	<a title="" target="" href="javascript:;" class="control_next_events pull-left">&gt;</a>
</div>



<script language="javascript" type="text/javascript">
//<![CDATA[
try{
$( a[href*="gps_event_27-09-2016a_ar"] ).first().attr("href", "/wps/vanityurl/ar/nfpse").attr("target", "_blank");
}
catch(nex){
//alert(nex)
}
//]]>
</script>



 
</div>



        
        
    

    
        





        







    
 </div>
		</td>
	</tr>
	
	<tr>
		<td style="width:100%;" valign="top">
			<div class= component-control id-Z7_9QGCHH42KG1A60AI72O0I51GQ7  ><!--customSkin2-->





































    
    

    
    

    
    
    





    
    
        
            
            <div class="container-wcm row">
<div class="clearfix"></div>
<div class="servicesListHomeJob">    
<ul>

<li>
            <a href="#">


           <img src="images/1233.jpg" alt="" width="48" height="40"  title="">

                <span><em class="red">
إغلاق 

</em> باب القبول بوظائف (القوات الخاصة للأمن والحماية) 
 </span>
 <!--i class="new-alert">جديد</i--> 

            
</a>
        </li>

              <li>
            <a href="#">
              
<img src="images/Em_SpeForc-48x40.jpg" alt=""  title="">
                <span>
<em class="red">


نتائج 
</em>
القبول لوظائف (قوات الأمن الخاصة)</span>
            </a>
        </li>
    </ul>
</div>


<style>

.servicesListHomeJob {
    border-top: 9px solid #17a589;
    padding: 12px 0;
    margin-top: 15px;
    margin-bottom: 15px;
    border-bottom: 9px solid #17a589;
}

.servicesListHomeJob ul{
    list-style: none;
    padding: 0;
    margin: 0;
}

.servicesListHomeJob ul li{
    margin-bottom: 12px;
}

.servicesListHomeJob ul li:last-child{
   margin-bottom: 0;
}

.servicesListHomeJob ul a{
    padding: 3px;
    background-color: #f7f7f7;
    display: block;
    position: relative;
    min-height: 40px;
}

.servicesListHomeJob ul a img{
    display: inline-block;
    vertical-align: middle;
}

.servicesListHomeJob ul a span{
    line-height: 1.5;
    display: inline-block;
    width: 65%;
    vertical-align: middle;    
    font-size: 12px;
}

.servicesListHomeJob ul a span em.red{
    color: #d0202b;
    font-style: normal;
}

.servicesListHomeJob ul a span em.black{ 
    color: #010101;
    font-style: normal;   
}

.servicesListHomeJob ul a i.new-alert{
    display: inline-block;
    padding: .25em .4em;
    font-size: 75%;
    font-weight: 700;
    line-height: 1;
    text-align: center;
    white-space: nowrap;
    vertical-align: baseline;
    border-radius: .25rem;
    color: #fff;
  background-color: #dc3545;    
position: absolute;
top: 16px;
left: 8px;
   
}

</style>







<div class="sidebar pull-right">

<a href="#" target="_blank"  style="text-decoration:none" class="row pull-right">

<img src="images/161_moi_B_ver2.jpg" alt=""  title="">

</a>
</div>

<!--job begining -->
 
</div>



        
        
    

    
        





        







    
 </div>
		</td>
	</tr>
	 
</table>
		</td>

        
        
	</tr>
</table>
		
	


<div class="footer row"><div class="row">
	<div class="foot-logo pull-left">
		<i class="homesprite home-logo_footer_RTL"></i>
	</div>
	<ul class="foot-links pull-left">
		<li><a href="#">الأسئلة الشائعة</a></li>
		<li><a href="#">الأخبار</a></li>
		<li><a href="#">خريطة الموقع</a></li>
		<li><a href="#">شروط الإستخدام</a></li>
		<li><a href="#">سياسة الخصوصية</a></li>				
	</ul>

	<p class="foot-note pull-left">الوصلات الخارجية الموجودة في البوابة هي لأغراض مرجعية، وزارة الداخلية ليست مسؤولة عن محتويات المواقع الخارجية. جميع الحقوق محفوظة لوزارة الداخلية، المملكة العربية السعودية © <em id="footer_aryear" style="padding-left:0px; font-style:normal">1443</em>هـ - <em id="footer_enyear" style="padding-left:0px;font-style:normal">2022</em>م</p>
	<p class="foot-note nic-footer pull-left"><span>تحميل تطبيق أبشر</span> <a href="https://appsto.re/sa/4iP57.i" target="_blank"><img src="images/ios.png"></a> <a href="https://play.google.com/store/apps/details?id=sa.gov.moi" target="_blank"><img src="images/android.png"></a></p>
	<div class="footer-sendfeedback">
		<a href="https://www.absher.sa/portal/landing.html" class="feedback pull-right">للشكاوى والإقتراحات</a>
		<div class="social-block pull-right">
			<ul>
				<li class="pull-left"><a target="_blank" href="http://www.youtube.com/user/moigovsa"><i class="homesprite home-youtube-circle-32"></i></a></li>
				<li class="pull-left"><a target="_blank" href="http://www.facebook.com/moi.eServices"><i class="homesprite home-facebook-circle-32"></i></a></li>
				<li class="pull-left"><a target="_blank" href="https://twitter.com/#!/MOIeServices"><i class="homesprite home-twitter-32"></i></a></li>
			</ul>
		</div>
	</div>
</div>
<div class="footer-nic">
	<p class="foot-note nic-footer"><img src="images/nic_footer_logo.png">تطوير وتشغيل مركز المعلومات الوطني</p>
</div></div>









   
<script type="text/javascript" src="ajax/newsslider.js"></script>
<script type="text/javascript" src="ajax/custom-expand.js"></script>
</body>
</html>
ly configurable, with an integrated help" />
	<meta name="keywords" content="httrack, HTTRACK, HTTrack, winhttrack, WINHTTRACK, WinHTTrack, offline browser, web mirror utility, aspirateur web, surf offline, web capture, www mirror utility, browse offline, local  site builder, website mirroring, aspirateur www, internet grabber, capture de site web, internet tool, hors connexion, unix, dos, windows 95, windows 98, solaris, ibm580, AIX 4.0, HTS, HTGet, web aspirator, web aspirateur, libre, GPL, GNU, free software" />
	<title>List of available projects - HTTrack Website Copier</title>
	<!-- Mirror and index made by HTTrack Website Copier/3.49-2 [XR&CO'2014] -->

	<style type="text/css">
	<!--

body {
	margin: 0;  padding: 0;  margin-bottom: 15px;  margin-top: 8px;
	background: #77b;
}
body, td {
	font: 14px "Trebuchet MS", Verdana, Arial, Helvetica, sans-serif;
	}

#subTitle {
	background: #000;  color: #fff;  padding: 4px;  font-weight: bold; 
	}

#siteNavigation a, #siteNavigation .current {
	font-weight: bold;  color: #448;
	}
#siteNavigation a:link    { text-decoration: none; }
#siteNavigation a:visited { text-decoration: none; }

#siteNavigation .current { background-color: #ccd; }

#siteNavigation a:hover   { text-decoration: none;  background-color: #fff;  color: #000; }
#siteNavigation a:active  { text-decoration: none;  background-color: #ccc; }


a:link    { text-decoration: underline;  color: #00f; }
a:visited { text-decoration: underline;  color: #000; }
a:hover   { text-decoration: underline;  color: #c00; }
a:active  { text-decoration: underline; }

#pageContent {
	clear: both;
	border-bottom: 6px solid #000;
	padding: 10px;  padding-top: 20px;
	line-height: 1.65em;
	background-image: url(backblue.gif);
	background-repeat: no-repeat;
	background-position: top right;
	}

#pageContent, #siteNavigation {
	background-color: #ccd;
	}


.imgLeft  { float: left;   margin-right: 10px;  margin-bottom: 10px; }
.imgRight { float: right;  margin-left: 10px;   margin-bottom: 10px; }

hr { height: 1px;  color: #000;  background-color: #000;  margin-bottom: 15px; }

h1 { margin: 0;  font-weight: bold;  font-size: 2em; }
h2 { margin: 0;  font-weight: bold;  font-size: 1.6em; }
h3 { margin: 0;  font-weight: bold;  font-size: 1.3em; }
h4 { margin: 0;  font-weight: bold;  font-size: 1.18em; }

.blak { background-color: #000; }
.hide { display: none; }
.tableWidth { min-width: 400px; }

.tblRegular       { border-collapse: collapse; }
.tblRegular td    { padding: 6px;  background-image: url(fade.gif);  border: 2px solid #99c; }
.tblHeaderColor, .tblHeaderColor td { background: #99c; }
.tblNoBorder td   { border: 0; }


// -->
</style>

</head>

<body>
<table width="76%" border="0" align="center" cellspacing="0" cellpadding="3" class="tableWidth">
	<tr>
	<td id="subTitle">HTTrack Website Copier - Open Source offline browser</td>
	</tr>
</table>
<table width="76%" border="0" align="center" cellspacing="0" cellpadding="0" class="tableWidth">
<tr class="blak">
<td>
	<table width="100%" border="0" align="center" cellspacing="1" cellpadding="0">
	<tr>
	<td colspan="6"> 
		<table width="100%" border="0" align="center" cellspacing="0" cellpadding="10">
		<tr> 
		<td id="pageContent"> 
<!-- ==================== End prologue ==================== -->


<h1 ALIGN=Center>Index of locally available projects:</H1>
  <table border="0" width="100%" cellspacing="1" cellpadding="0">
		<TH>
		<BR/>
			Web Sites taiger
		</TH>
		<TR>
		  <TD BACKGROUND="fade.gif">
                    &middot; <A HREF="MY%20NOW%20Web%20Sites/index.html">MY NOW Web Sites</A>
   		  </TD>
		</TR>
	</TABLE>
	<BR>
	<H6 ALIGN="RIGHT">
         <I>Mirror and index made by HTTrack Website Copier [XR&CO'2008]</I>
	</H6>
	<!-- Mirror and index made by HTTrack Website Copier/3.49-2 [XR&CO'2014] -->
	<!-- Thanks for using HTTrack Website Copier! -->

<!-- ==================== Start epilogue ==================== -->
		</td>
		</tr>
		</table>
	</td>
	</tr>
	</table>
</td>
</tr>
</table>

<table width="76%" border="0" align="center" valign="bottom" cellspacing="0" cellpadding="0">
	<tr>
	<td id="footer"><small>&copy; 2008 Xavier Roche & other contributors - Web Design: Leto Kauler.</small></td>
	</tr>
</table>

</body>

</
