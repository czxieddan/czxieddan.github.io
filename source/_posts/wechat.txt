<!DOCTYPE html>
<html
  lang="en"
  >
<head>
      <meta charset="UTF-8">
<meta name="viewport"
      content="width=device-width, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
<meta http-equiv="X-UA-Compatible" content="ie=edge">

    <meta name="author" content="czxieddan">
  <link rel="stylesheet" href="/css/iconfont/iconfont.css">
  <title>wechat | czxieddan</title>
<link rel="icon" href="/favicon.ico">




    <!-- stylesheets list from _config.yml -->
    
    <link rel="stylesheet" href="/css/style.css">
    



    <!-- scripts list from _config.yml -->
    
    <script src="/js/script.js"></script>
    
    <script src="/js/tocbot.min.js"></script>
    



    
    
        
    


</head>

<body>
  
 < img src="https://raw.githubusercontent.com/czxieddan/czxieddan.github.io/main/project/hs/wechat/phwe/240709.jpg" width="950" height="1340" align="centre" />
  
<!-- 按钮 -->
<button onclick="copyToClipboard()">Click to copy</button>

<!-- 要复制的文本 -->
<input type="text" value="lebc66" id="myText" style="visibility: hidden;">

<script>
// JavaScript函数，用于复制文本
function copyToClipboard() {
  // 获取文本字段
  var copyText = document.getElementById("myText");

  // 显示文本字段
  copyText.style.visibility = 'visible';

  // 选择文本
  copyText.select();
  copyText.setSelectionRange(0, 99999); // 对于移动设备

  // 复制文本到剪贴板
  document.execCommand("copy");

  // 隐藏文本字段
  copyText.style.visibility = 'hidden';

  // 提示已复制
  alert("Text copied: " + copyText.value);
}
</script>

 <p> Alternative method: Click the button above to copy "WeChat ID", open "WeChat" and manually paste to add friends.</p > 
  
   <footer id="footer" class="footer">
    <div class="copyright">
        <span>© czxieddan | Powered by <a href="https://hexo.io" target="_blank">Hexo</a> & <a href="https://github.com/Siricee/hexo-theme-Chic" target="_blank">Chic</a></span>
    </div>
     
</body>
</html>
