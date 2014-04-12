PullToRefresh Android Module for Titanium
====================
<br>
New module "<strong>Pull to refresh android for titanium</strong>" using tableview existing on the marketplace appcelerator.
<br>Module  personalizable (you can change label text and picture in the header pull)
integrate this module will not cause any major modification in your existing code, just add the tableview to the module widget and add the widget to the window.

<strong><a href="https://marketplace.appcelerator.com/apps/8362">Download the module from the market</a></strong>

<h1>Overview</h1>


<img width="115" height="115" src="http://www.ezziprod.com/pulltorefresh/images/logo.png">
<br>
<img width="326" height="326" src="http://www.ezziprod.com/pulltorefresh/images/pull1.png">
<br>
<img width="326" height="326" src="http://www.ezziprod.com/pulltorefresh/images/pull2.png">
<br>
<img width="326" height="326" src="http://www.ezziprod.com/pulltorefresh/images/pull3.png">
<br>
<br>

<h1>Installation</h1>
<ul>
<li>
Get the module existing on the market from here <a href="https://marketplace.appcelerator.com/apps/8362">Android pull to refresh</a>
</li>
<li>Declare it in your tiapp.xml file
<br>
<pre>
&lt;modules&gt;
&lt;module platform="android" version="1.0"&gt;com.ezziprod.pulltorefresh&lt;/module&gt;
&lt;/modules&gt;
</pre>
</li>
</ul>

<h1>Configuration</h1>

<pre>
<strong>imagePull</strong> : your arrow picture
<strong>imageLoad</strong> : your loader picture
<strong>textPull</strong> : your message when start pulling, default : Pull to refresh...
<strong>textRelease</strong> : your message when view is pulled more than 80px, default : Release to refresh...
<strong>textLoading</strong> : your message when start loading, default : Loading...
<strong>textUpdate</strong> : your message to inform user for last update, default : ''
</pre>
<pre>
pullToRefreshView.headerPullView({
    'imagePull' : 'grayArrow.png',
    'imageLoad' : 'loader.png',
    'textPull' : 'Pull to refresh...',
    'textRelease' : 'Release to refresh...',
    'textLoading' : 'Loading...',
    'textUpdate' : 'Last update : ' + getDate()
});
</pre>


<h3>Create your tableview and add it to the module... and add the module widget to your window, you will get a result like this video <a href="https://www.youtube.com/watch?v=Ozkdy5Ljv7I">Youtube</a></h3>

<h1>Changelog</h1>
<h2>1.0 _11/04/2014</h2>
