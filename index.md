<header class="header"></header>

<article class="container">
    <section class="side" id="side">

        <!-- 左栏固定开关，记得及时删除这段代码 Start-->
        <label class="switch" style="display: none;" onchange="switchFixed()">
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
            @media (min-width: 	750px){
                .switch{position:relative;display:inline-block!important;width:60px;height:34px;}
                .switch input{display:none;}
                .slider{position:absolute;cursor:pointer;top:0;left:0;right:0;bottom:0;background-color:#ccc;-webkit-transition:.4s;transition:.4s;}
                .slider:before{position:absolute;content:"";height:26px;width:26px;left:4px;bottom:4px;background-color:white;-webkit-transition:.4s;transition:.4s;}
                input:checked + .slider{background-color:#1abc9c;}
                input:focus + .slider{box-shadow:0 0 1px #1abc9c;}
                input:checked + .slider:before{-webkit-transform:translateX(26px);-ms-transform:translateX(26px);transform:translateX(26px);}.slider.round{border-radius:34px;}
                .slider.round:before{border-radius:50%;}
            }
        </style>
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
                <img src="img/helloworld.jpg">
            </section>

            <h1 class="name">方岩</h1>
            <h4 class="info-job">石家庄铁道大学</h4>

        </section>

        <!-- 基本信息 -->
        <section class="profile info-unit">
            <h2>
                <i class="fa fa-user" aria-hidden="true"></i>基本信息</h2>
            <hr/>
            <ul>
                <li>
                    <label>个人信息</label>
                    <span>方岩/ 男 / 22岁</span>
                </li>
                <li>
                    <label>英语水平</label>
              
                </li>
                <li>
                    <label>计算机水平</label>
                    <span>软考中级</span>
                </li>
                <li>
                    <label>爱好</label>
                    <span>篮球，编程</span>
                </li>
                <li>
                    <label>擅长</label>
                    <span>java,python</span>
                </li>
            </ul>
        </section>

        <!-- 联系方式 -->
        <section class="contact info-unit">
            <h2>
                <i class="fa fa-phone" aria-hidden="true"></i>联系方式</h2>
            <hr/>
            <ul>
                <li>
                    <label>手机</label>
                    <a href="tel:19930500463 target="_blank">199-3050-0463</a>
                </li>
                <li>
                    <label>邮箱</label>
                    <a href="mailto:ze.zh@hotmail.com" target="_blank">1157644432@qq.com</a>
                </li>
                <li>
                    <label>个人主页</label>
                    <a href="http://fangyan3524.github.io/" target="_blank">fangyan3524.github.io</a>
                </li>
                <li>
                    <label>Github</label>
                    <a href="http://fangyan3524.github.io/" target="_blank">fangyan3524.github.io</a>
                </li>
            </ul>
        </section>

        <!-- 技能点 -->
        <section class="skill info-unit">
            <h2>
                <i class="fa fa-code" aria-hidden="true"></i>技能点</h2>
            <hr/>
            <ul>
                <li>
                    <label>HTML</label>
                    <progress value="60" max="100"></progress>
                </li>
                <li>
                    <label>CSS</label>
                    <progress value="60" max="100"></progress>
                </li>
                <li>
                    <label>JavaScript</label>
                    <progress value="60" max="100"></progress>
                </li>
                <li>
                    <label>Hadoop</label>
                    <progress value="60" max="100"></progress>
                </li>
                <li>
                    <label>mysql</label>
                    <progress value="50" max="100"></progress>
                </li>
                <li>
                    <label>Android</label>
                    <progress value="50" max="100"></progress>
                </li>
            </ul>
        </section>

        <section class="qrcode info-unit">
            <h2><i class="fa fa-qrcode" aria-hidden="true"></i>二维码</h2>
            <hr/>
            <img src="./assets/1.png" style="width: 100%;" alt="">
        </section>

        <!-- 技术栈 -->
        <!-- <div class="stack info-unit">
                <h2><i class="fa fa-code" aria-hidden="true"></i>其他</h2>
                <hr/>
                <ul>
                    <li>
                        <label>前端</label>
                        <span>React、jQuery、微信小程序、Bootstrap、SASS、LESS</span>
                    </li>
                    <li>
                        <label>后端</label>
                        <span>Node.js、MySQL、MongoDB、WordPress、ThinkPHP</span>
                    </li>
                    <li>
                        <label>其他</label>
                        <span>Git、SVN、Markdown</span>
                    </li>
                </ul>
            </div> -->
    </section>

    <section class="main">

        <!-- 教育经历 -->
        <section class="edu info-unit">
            <h2>
                <i class="fa fa-graduation-cap" aria-hidden="true"></i>教育经历</h2>
            <hr/>
            <ul>
                <li>
                    <h3>
                        <span>石家庄铁道大学（本科）</span>
                        <time>2018.9-2022.7</time>
                    
                </li>
                
            </ul>
        </section>

        <!-- 工作经历 -->
        <section class="work info-unit">
            <h2>
                <i class="fa fa-shopping-bag" aria-hidden="true"></i>学习经历</h2>
            <hr/>
            <ul>
                <li>
                    <h3>
                        <span>东软杯比赛</span>
                        <time>2020.9 至 2020.12</time>
                    </h3>
                    <ul class="info-content">
                        <li>架构设计
                            <mark>CURD</mark>，实现
                            <mark>前后端完全分离</mark>。</li>
                        <li>配合UI和后端，根据产品需求提供H5页面嵌入到后台模板，要求
                            <mark>移动端显示正常</mark>。</li>
                        <li>主要参与项目的静态页面开发工作，要求
                            <mark>更好的动态交互</mark>。</li>
                    </ul>
                </li>
            </ul>
        </section>

        <!-- 项目经验 -->
        <section class="project info-unit">
            <h2>
                <i class="fa fa-terminal" aria-hidden="true"></i>个人项目</h2>
            <hr/>
            <ul>
                <li>
                    <h3>
                        <span>[项目1]河北重大需求征集系统</span>
                        <span class="link">
                            <a href="#" target="_blank">Demo</a>
                        </span>
                        <time>2020.9-2020.11</time>
                    </h3>
                    <ul class="info-content">
                        <li>技术栈：HTML+CSS+Spring</li>
                        <li>
                            <i class="fa fa-paper-plane-o" aria-hidden="true"></i>
                            [目标]实现技术需求征集，审核，图表显示
                            <br/>
                            <i class="fa fa-users" aria-hidden="true"></i>
                            [团队]同专业同学一起
                            <br/>
                            <i class="fa fa-bars" aria-hidden="true"></i>
                            [贡献]完成
                            <mark>“调研-设计-实现-文档”</mark>等工作，主要负责系统原型、功能框架及数据提交流程、元数据及源数据的管理与共享方案的设计以及系统开发等工作
                            <br/>
                        </li>
                    </ul>
                </li>
            </ul>
        </section>

        <!-- 自我评价 -->
        <section class="work info-unit">
            <h2>
                <i class="fa fa-pencil" aria-hidden="true"></i>自我评价/期望</h2>
            <hr/>
            <p>能力欠缺还有进步空间
                <span class="mark-txt">“努力学习吧”</span> </p>
        </section>
    </section>
</article>



<footer class="footer">
    <p>© 方岩
        <time>2021年06月30日</time>.</p>
</footer>

<!-- 侧栏
<aside>
    <ul>
        <li>
            <a href="https://gitee.com/itsay/resume" target="_blank">源代码</a>
        </li>
        <li>
            <a href="http://if2er.com/" target="_blank">Blog</a>
        </li>
    </ul>
</aside> -->

<script src="./assets/js/index.js"></script>
