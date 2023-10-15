# test
**欸我真的我服了不知道怎么用github欸欸欸**

我把一些东西存在这里方便以后复制（）

**彩色大字体**
<style>
    .rainbow-text {
      font-size: 80px;
      font-weight: bold;
      background: linear-gradient(to right, red, orange, yellow, green, blue, indigo, violet);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      text-align: center
    }
  </style>

**文本输入框**
<style>
.textbox {
            margin: 0 auto;
            max-width: 300px;
            min-width: 100px;
            height: 40px;
            border: none;
            border-radius: 10px;
            padding: 10px;
            box-shadow: 0px 2px 5px rgba(0, 0, 0, 0.3);
            transition: width 0.3s ease-in-out;
            text-align: center
            
        }
        .textbox:focus {
            width: 200%; 
        }
</style>
<script>
    function resizeTextbox() {
        var textbox = document.getElementById("myTextbox");
        var textLength = textbox.value.length;
        var numLines = Math.ceil(textLength / 1);
        var newWidth = 200 + (numLines * 20);
        textbox.style.width = newWidth + "px";
    }
</script>
