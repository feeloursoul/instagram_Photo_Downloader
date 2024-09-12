# instagram_Photo_Downloader
<br>
```
javascript:(function() {    const img = document.querySelector('article img');    if (img) {        const a = document.createElement('a');        a.href = img.src;        a.download = 'instagram_photo.jpg';        document.body.appendChild(a);        a.click();        document.body.removeChild(a);    } else {        alert('%E7%94%BB%E5%83%8F%E3%81%8C%E8%A6%8B%E3%81%A4%E3%81%8B%E3%82%8A%E3%81%BE%E3%81%9B%E3%82%93%E3%81%A7%E3%81%97%E3%81%9F%E3%80%82');    }})();
```
<br>
Paste the JavaScript code directly into the address box. Give your bookmarklet a name and save it.
<br>
<br>

![image](https://github.com/user-attachments/assets/82f44e51-546c-4bd5-b081-b40da4f8f62f)

<br>
<br>
Click bookmarklet on address box.
<br>
<br>
![image](https://github.com/user-attachments/assets/2b2467fd-0007-4cab-8c45-e75457994172)

Save Image As right click and download your favorite photo.
