# nsHover
A simple jQuery Hover Plugin

# Usage
Firstly, include the ns.hover.min.js just before the end body tag in your html
<pre>&lt;script src="src/ns.hover.min.js"&gt;&lt;/script&gt;</pre>
just call with the container class and set the options to customize the look and feel. (You must have to set a container class in order to make the child elemnts use this effect. child can be any html tags including images offcourse.)

<pre>
&lt;script&gt;
$(container_class_or_id).nsHover({
    scaling : false,
    speed: 'normal',
    rounded: 'normal',
    bgcolor: '#ffffff',
    bgopacity : 0.5,            
    bgpic : 'imgs/lens.png',
    bgsize : '50%',
    bganim : 'fade',
    shadow : false,
    content: ''
});
&lt;/script&gt;
</pre>

For detail information, docs and exapmple please visit
<a href="http://www.nslabz.com/ns.hover.html" target="_blank">nsHover Plugin by nslabz</a>

