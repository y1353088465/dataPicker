
# dataPicker
省市区三级联动 兼容性高，使用相当相当简单
引入文件
 <script src="./index.js"></script>    
 <link rel="stylesheet" href="./index.css">

引用方式   new picker({\n
            el:"demo",//必须，节点绑定\n
            showDom:"show_picker",//绑定页面dom元素 控制picker显示隐藏\n
            //返回的地址信息\n
            success:function success(data){\n
                console.log(data)\n
            }
        })
