---
permalink: "/mega.nz/"
title: "Secure Cloud Storage: MEGA"
header:
 og_image: "https://cdn.statically.io/img/upload.wikimedia.org/wikipedia/en/b/b9/Mega.co.nz_file_uploader.PNG"
---
**Overview**

Mega (stylised in uppercase as MEGA) is a cloud storage and file hosting service offered by Mega Limited, an Auckland-based company.

![MEGA](https://cdn.statically.io/img/upload.wikimedia.org/wikipedia/en/b/b9/Mega.co.nz_file_uploader.PNG)

The service is offered primarily through web-based apps. Mega mobile apps are also available for Windows Phone, Android and iOS. Mega is known for its large 50 GB storage allocation for free accounts.

The website and service was launched on 19 January 2013, by Kim Dotcom, who had founded the now-defunct service Megaupload. However, in 2015 Kim Dotcom disassociated himself from the service and stated that the New Zealand government had seized the shares of a Chinese investor and has control of the site. Mega Limited responded that the authorities have not interfered with its operations.

**Encryption**

Dotcom has said that data on the Mega service will be encrypted client-side using the AES algorithm. Since Mega does not know the encryption keys to uploaded files, they cannot decrypt and view the content. Therefore, they cannot be responsible for the contents of uploaded files.

Dotcom stated that encrypting files allows them to work with a larger number of data hosting companies around the world, decreasing the likelihood of a Megaupload-style seizure of servers by one government. He mentioned in an interview with Ars Technica that "Each file will be kept with at least two different hosters [sic], [in] at least two different locations," and "That’s a great added benefit for us because you can work with the smallest, most unreliable [hosting] companies. It doesn’t matter because they can’t do anything with that data."

{% include tengah.html %}

<div style="display:block;text-align:center">
<a id="download" class="btn btn--primary" href="#notice" rel="nofollow noreferer noopener">
Waiting MEGA..
</a>
</div>
<p id="notice" class="notice notice--primary">
<i>remember this:</i> The links provided above is not appear out of nowhere. It is loaded from the pages or article before you came here. So if the links is broken, you can go back to previous page and ask/report at the comment section. <b>Reload or clear browser cache if it takes to long</b>.
</p>

{% include bawah.html %}

<script>
function getQueryVariable(e){
 for(
  var r=window.location.search.substring(1),
      t=r.split("&"),
      n=0;
      n<t.length;
      n++
 )
 {
  var a=t[n].split("=");
  if(a[0]==e)return a[1]
 }
 return!1
}
window.onload=function(){
  var klik=f=getQueryVariable("key"),
           e=getQueryVariable("file"),
           d=document.getElementById("download"),
           c=document.getElementById("notice"),
           x="https://mega.nz/file/";
  d.innerHTML=f,
  d.href=x+f+"#"+e;
  c.innerHTML="Your link now ready, click the button <b>"+f+"</b> above!";
  d.classList.remove("btn--primary");
  d.classList.add("btn--success");
  c.classList.remove("notice--primary");
  c.classList.add("notice--success");
}; 
</script>
