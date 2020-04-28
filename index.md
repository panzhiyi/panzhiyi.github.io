<!DOCTYPE html>
<html lang="zh-cn">

<head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0, user-scalable=no"
    />
    <meta name="apple-mobile-web-app-status-bar-style" content="black" />
    <meta name="format-detection" content="email=no" />
    <meta name="apple-mobile-web-app-capable" content="yes" />
    <meta name="format-detection" content="telephone=no" />
    <meta name="renderer" content="webkit">
    <meta name="apple-mobile-web-app-status-bar-style" content="black">
    <meta name="apple-mobile-web-app-title" content="Amaze UI" />
    <meta http-equiv="Cache-Control" content="no-cache, no-store, must-revalidate" />
    <meta http-equiv="Pragma" content="no-cache" />
    <meta http-equiv="Expires" content="0" />
    <title>Zhiyi Pan - homepage</title>
    <link rel="shortcut icon" href="assets/images/favicon.ico" type="image/x-icon">
    <link rel="stylesheet" href="assets/css/typo.css">
    <link rel="stylesheet" href="assets/css/font-awesome.min.css">
    <link rel="stylesheet" href="assets/css/index.css">
    <script>
        function loading() {
            document.getElementsByClassName('avatar')[0].style.display = 'block';
            document.getElementsByClassName('loading')[0].style.display = 'none';
        }
    </script>
</head>

<body>

    <header class="header"></header>

    <article class="container">
        <section class="side" id="side">

            <!-- 左栏固定开关，记得及时删除这段代码 Start-->
            <!-- <label class="switch" style="display: none;" onchange="switchFixed()">
                <script type="text/javaScript">
                    function switchFixed(){
                        var value = document.getElementById('side').style.position === 'fixed' ? 'absolute' : 'fixed';
                        document.getElementById('side').style.position = value;
                    }
                </script>
                <input id="cb" type="checkbox">
                <span class="slider round"></span>
            </label> 
            <style>
                @media (min-width: 414px){
                    .switch{position:relative;display:inline-block!important;width:60px;height:34px;}
                    .switch input{display:none;}
                    .slider{position:absolute;cursor:pointer;top:0;left:0;right:0;bottom:0;background-color:#ccc;-webkit-transition:.4s;transition:.4s;}
                    .slider:before{position:absolute;content:"";height:26px;width:26px;left:4px;bottom:4px;background-color:white;-webkit-transition:.4s;transition:.4s;}
                    input:checked + .slider{background-color:#1abc9c;}
                    input:focus + .slider{box-shadow:0 0 1px #1abc9c;}
                    input:checked + .slider:before{-webkit-transform:translateX(26px);-ms-transform:translateX(26px);transform:translateX(26px);}.slider.round{border-radius:34px;}
                    .slider.round:before{border-radius:50%;}
                }
            </style> -->
            <!-- 左侧固定开关，记得及时删除这段代码 End-->

            <!-- 个人肖像 -->
            <section class="me">
                <section class="portrait">
                    <div class="loading">
                        <span></span>
                        <span></span>
                        <span></span>
                        <span></span>
                        <span></span>
                    </div>
                    <!-- 头像照片 -->
                    <img class="avatar" src="assets/images/avatar.jpg" onload="loading()">
                </section>

                <h1 class="name">Zhiyi Pan</h1>
                <h4 class="info-job">研究方向：计算机视觉</h4>

            </section>

            <!-- Scholar Links 
            <section class="profile info-unit">
                <h2>
                    <i class="fa fa-user" aria-hidden="true"></i>Scholar Links</h2>
                <hr/>
                <ul>
                    <li>
                        <a href="https://github.com/panzhiyi" target="_blank">GitHub</a>
                    </li>
                    <li>
                        <label>年龄</label>
                        <span>23岁</span>
                    </li>
                    <li>
                        <label>坐标</label>
                        <span>青岛</span>
                    </li>
                </ul>
            </section>
            -->

            <!-- Scholar Links -->
            <section class="contact info-unit">
                <h2>
                    <i class="fa fa-phone" aria-hidden="true"></i>Scholar Links</h2>
                <hr/>
                <ul>
                    <li>
                        <label>GitHub</label>
                        <a href="https://github.com/panzhiyi" target="_blank">GitHub</a>
                    </li>
                    <li>
                        <label>Google Scholar</label>
                        <a href="https://scholar.google.com/citations?hl=en&user=Mdtik3oAAAAJ" target="_blank">Google Scholar</a>
                    </li>
                    <li>
                        <label>Email</label>
                        <a href="mailto:panzhiyi@mail.sdu.edu.cn" target="_blank">Email</a>
                    </li>
                </ul>
            </section>

            <!-- 技术栈 
            <div class="stack info-unit">
                    <h2><i class="fa fa-code" aria-hidden="true"></i>技术栈</h2>
                    <hr/>
                    <ul>
                        <li>
                            <label>AI</label>
                            <span>Python、OpenCV、TensorFlow、Caffe、PocketSphinx、LibSVM</span>
                        </li>
                        <li>
                            <label>客户端</label>
                            <span>Qt、VB、C#、Android</span>
                        </li>
                        <li>
                            <label>嵌入式</label>
                            <span>C、C++、ARM、MIPS、Linux内核裁剪</span>
                        </li>
                        <li>
                            <label>前端</label>
                            <span>HTML、js、jQuery、Bootstrap</span>
                        </li>
                        <li>
                            <label>后端</label>
                            <span>PHP、SpringMVC、JAVA、ASP、MySQL、MapReduce、HBase</span>
                        </li>
                        <li>
                            <label>其他</label>
                            <span>Git、Markdown、LaTeX</span>
                        </li>
                    </ul>
                </div>
        </section>
        -->

        <section class="main">

            <!-- 教育经历 -->
            <section class="edu info-unit">
                <h2>
                    <i class="fa fa-graduation-cap" aria-hidden="true"></i>教育经历</h2>
                <hr/>
                <ul>
                    <li>
                        <h3>
                            <span>山东大学 - 计算机技术（硕士）</span>
                            <time>2018.9-至今</time>
                        </h3>
                        <!-- <p>专业排名
                            <mark>X/XX</mark>，期间发表国际会议英文摘要X篇，国内核心期刊文章X篇（其中第一作者X篇），
                            获XXX，XXX2次，XXX2次。(此处根据自身情况填写，可以突出自己的亮点，
                            或者跟求职目标相关的内容)</p> -->
                    </li>
                    <li>
                        <h3>
                            <span>山东科技大学 - 物联网工程（本科）</span>
                            <time>2014.9-2018.7</time>
                        </h3>
                        <!-- <p>专业排名
                            <mark>10/80</mark></p>-->
                    </li>
                </ul>
            </section>

            <!-- 工作经历 -->
            <section class="work info-unit">
                <h2>
                    <i class="fa fa-shopping-bag" aria-hidden="true"></i>工作经历</h2>
                <hr/>
                <ul>
                    <li>
                        <h3>
                            <span>小米移动软件有限公司－软件工程师（实习）</span>
                            <time>2017.7 至 2018.5</time>
                        </h3>
                        <ul class="info-content">
                            <li>对业内领先目标检测网络效果进行复现，对小米目标检测数据集进行
                                <mark>数据增强</mark>，使用开源数据集和小米数据集对各种目标检测网络进行训练
                                <mark>评估各网络在小米测试机上效果</mark>。</li>
                            <li>参与米家智能摄像头研发，独立开发米家智能摄像头PC端v1，
                                <mark>适配Windows、Linux</mark>。</li>
                            <li>独立开发目标检测算法评估程序
                                <mark>支持绘制ROC、PR曲线等，可以计算AP、Accuracy等</mark>。</li>
                        </ul>
                    </li>
                    <li>
                        <h3>
                            <span>青岛卓迅电子科技有限公司－PHP开发工程师（实习）</span>
                            <time>2016.1-2016.3</time>
                        </h3>
                        <ul class="info-content">
                            <li>负责某款智能电箱网页管理端整体架构</li>
                            <li>管理页面UI设计及数据可视化</li>
                            <li>相关业务逻辑设计与实现</li>
                        </ul>
                    </li>
                </ul>
            </section>

            <!-- 项目经验 -->
            <section class="project info-unit">
                <h2>
                    <i class="fa fa-terminal" aria-hidden="true"></i>项目经验</h2>
                <hr/>
                <ul>
                    <li>
                        <h3>
                            <span>基于OpenCV的全景图拼接</span>
                            <span class="link">
                                <a href="#" target="_blank">Demo</a>
                            </span>
                            <time>2017.6-2017.7</time>
                        </h3>
                        <ul class="info-content">
                            <li>技术栈：OpenCV</li>
                            <li>
                                <i class="fa fa-paper-plane-o" aria-hidden="true"></i>
                                [应用项目]基于监控摄像头的青岛市小珠山森林火灾报警系统
                                <br/>
                                <i class="fa fa-users" aria-hidden="true"></i>
                                [团队]同 2 位同专业同学一起
                                <br/>
                                <i class="fa fa-bars" aria-hidden="true"></i>
                                [贡献]利用OpenCV实现各个角度图片拼接成全景图，
                                <mark>主要包括特征点检测、桶形变换</mark>等工作,设计动态链接库供其他开发者调用。
                                <br/>
                                <i class="fa fa-thumbs-o-up" aria-hidden="true"></i>
                            </li>
                        </ul>
                    </li>
                    <li>
                        <h3>
                            <span>基于Haar级联分类器的敌方机器人检测</span>
                            <span class="link">
                                <a href="#" target="_blank">Demo</a>
                            </span>
                            <time>2017.03-2017.06</time>
                        </h3>
                        <ul class="info-content">
                            <li>技术栈：OpenCV</li>
                            <li>
                                <i class="fa fa-paper-plane-o" aria-hidden="true"></i>
                                [目标]实现通过从2D图片中有效检测目标机器人位置
                                <br/>
                                <i class="fa fa-users" aria-hidden="true"></i>
                                [个人]独立完成
                                <br/>
                                <i class="fa fa-bars" aria-hidden="true"></i>
                                [主要工作]采集大量目标机器人图片，手动标注，训练级联分类器。
                                <br/>
                                <i class="fa fa-thumbs-o-up" aria-hidden="true"></i>
                                [应用赛事]RoboMasters机器人对抗赛
                            </li>
                        </ul>
                    </li>
                    <li>
                        <h3>
                            <span>面向老年人的智能家居系统</span>
                            <span class="link">
                                <a href="#" target="_blank">Demo</a>
                            </span>
                            <time>2016.09-2017.03</time>
                        </h3>
                        <ul class="info-content">
                            <li>技术栈：嵌入式软件开发、网络编程、Android</li>
                            <li>
                                <i class="fa fa-paper-plane-o" aria-hidden="true"></i>
                                [目标]实现智能家居基本功能、可视楼宇对讲、跌倒检测
                                <br/>
                                <i class="fa fa-users" aria-hidden="true"></i>
                                [团队]与 2 位同学
                                <br/>
                                <i class="fa fa-bars" aria-hidden="true"></i>
                                [贡献]1、借助Pocket Sphinx实现离线语音识别,从而实现家居系统快速实时语音控制;
                                2、自主开发开源音频采集及传输软件——wave-streamer,配合mjpg-streamer移植到RT5350开发板上
                                实现IP Camera功能;
                                3、从智能手环获取三轴加速度信息，基于SVM的实现跌倒检测。
                                4、完成智能家居手机控制端开发,实现与服务器对接。
                                <br/>
                                <i class="fa fa-thumbs-o-up" aria-hidden="true"></i>
                                [效果]作品取得第五届“中国软件杯”大学生软件设计大赛 国赛 二等奖(10/1500)
                            </li>
                        </ul>
                    </li>
                    <li>
                        <!--<h3>
                            <span>[项目4]肿瘤流行病数据可视化</span>
                            <span class="link">
                                <a href="#" target="_blank">Demo</a>
                            </span>
                            <time>201X.X-201X.X</time>
                        </h3>
                        <ul class="info-content">
                            <li>技术栈：HTML 5+D3.js+ECharts+MySQL</li>
                            <li>
                                <i class="fa fa-paper-plane-o" aria-hidden="true"></i>
                                [目标]实现常见肿瘤流行病数据多维度可视化展示、数据透视及分析
                                <br/>
                                <i class="fa fa-users" aria-hidden="true"></i>
                                [团队]与 1 位
                                <br/>
                                <i class="fa fa-bars" aria-hidden="true"></i>
                                [贡献]分析项目需求，清洗并整理相关数据(扩展第三方知识组织系统和 Google trends 数据)，并用
                                <mark>D3.js</mark> 和
                                <mark>ECharts</mark> 进行图形化展示以及实现简易自动分析 功能
                                <br/>
                                <i class="fa fa-thumbs-o-up" aria-hidden="true"></i>
                                [效果]作品取得第二届共享杯国家级竞赛“特等奖”(1/1500)
                            </li>
                        </ul> -->
                    </li>

                </ul>
            </section>

            <!-- 自我评价
            <section class="work info-unit">
                <h2>
                    <i class="fa fa-pencil" aria-hidden="true"></i>自我评价/期望</h2>
                <hr/>
                <p>[此处如果有一些能够量化的、且比较个性的指标会有加分，比如喜爱跑步坚持夜跑200小时或者200km等]
                    <span class="mark-txt">“多静多思考，反省不张扬”</span>是我给自己总结的“十字箴言”，鞭策自己做人既不能以己度人，也不以人观己，要脚踏实地做事，坚持自己的梦想和本心。</p>
            </section> -->
        </section>
    </article>



    <footer class="footer">
        <p>© 2018 Last update:
            <time>Mar 19, 2020</time>.</p>
    </footer>

    <!-- 侧栏 -->
    <aside>
        <ul>
            <li>
                <a href="https://github.com/lhc3538" target="_blank">CV</a>
            </li>
            <li>
                <a href="https://blog.csdn.net/lell3538" target="_blank">中文版本</a>
            </li>
        </ul>
    </aside>

    <script src="./assets/js/index.js"></script>
</body>

</html>
