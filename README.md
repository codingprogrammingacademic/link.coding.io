<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Competitive Programmer's Journey</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        body { font-font-family: 'Inter', sans-serif; }
        .chart-container { position: relative; width: 100%; max-width: 600px; margin-left: auto; margin-right: auto; height: 300px; max-height: 400px; }
        @media (min-width: 768px) { .chart-container { height: 350px; } }
        .flow-line::after { content: ''; position: absolute; left: 50%; transform: translateX(-50%); top: 100%; height: 3rem; width: 2px; background-color: #4A5568; }
        .timeline-icon { background-color: #FFFFFF; border: 2px solid #4A5568; }
        
        /* Language-specific styles */
        [lang="en"] .lang-zh { display: none; }
        [lang="zh"] .lang-en { display: none; }
    </style>
</head>
<body class="bg-[#F0F4F8]">
    <div class="container mx-auto p-4 md:p-8 max-w-5xl">
        <header class="text-center mb-12 relative">
            <button id="language-switcher" class="absolute top-0 right-0 p-2 bg-[#1D3557] text-white rounded-lg hover:bg-opacity-80 transition-colors">中文</button>
            <h1 class="text-4xl md:text-5xl font-bold text-[#1A202C] mb-2">
                <span class="lang-en">The Competitive Programmer's Journey</span>
                <span class="lang-zh">竞争性程序员之旅</span>
            </h1>
            <p class="text-lg text-[#4A5568]">
                <span class="lang-en">From visual blocks to elite algorithms, this is the path to mastery.</span>
                <span class="lang-zh">从可视化编程到精英算法，这是通往大师之路。</span>
            </p>
        </header>
        <main class="relative">

            <section id="foundation" class="mb-12">
                <div class="relative text-center mb-6 flow-line">
                    <div class="w-12 h-12 rounded-full inline-flex items-center justify-center text-2xl timeline-icon">🧩</div>
                </div>
                <h2 class="text-center text-3xl font-bold text-[#2D3748] mb-4">
                    <span class="lang-en">The Foundation: Visual Logic</span>
                    <span class="lang-zh">基础：可视化编程</span>
                </h2>
                <p class="text-center text-md text-[#4A5568] max-w-3xl mx-auto mb-8">
                    <span class="lang-en">The journey starts by building a strong foundation in computational thinking and problem-solving using visual, block-based programming.</span>
                    <span class="lang-zh">旅程始于使用可视化、基于块的编程，在计算思维和解决问题方面打下坚实的基础。</span>
                </p>
                <div class="grid grid-cols-1 gap-8">
                    <div class="bg-white rounded-lg shadow-md p-6">
                        <h3 class="font-bold text-xl mb-3 text-[#E63946]">
                            <span class="lang-en">Stage 1: Scratch</span>
                            <span class="lang-zh">阶段一：Scratch</span>
                        </h3>
                        <p class="text-sm text-[#4A5568] mb-4">
                            <span class="lang-en">Learn programming fundamentals without complex syntax using a visual, block-based system.</span>
                            <span class="lang-zh">使用可视化、基于块的系统，无需复杂的语法即可学习编程基础知识。</span>
                        </p>
                        <ul class="list-disc list-inside text-[#4A5568] space-y-2 text-sm">
                            <li><span class="lang-en">Variables, Loops & Conditionals</span><span class="lang-zh">变量、循环与条件语句</span></li>
                            <li><span class="lang-en">Event-driven programming</span><span class="lang-zh">事件驱动编程</span></li>
                            <li><span class="lang-en">Develop a problem-solving mindset</span><span class="lang-zh">培养解决问题的思维模式</span></li>
                        </ul>
                    </div>
                </div>
            </section>

            <section id="python-path" class="mb-12">
                <div class="relative text-center mb-6 flow-line">
                    <div class="w-12 h-12 rounded-full inline-flex items-center justify-center text-2xl timeline-icon">🐍</div>
                </div>
                <h2 class="text-center text-3xl font-bold text-[#2D3748] mb-4">
                    <span class="lang-en">The Python Path: From Basics to Advanced Applications</span>
                    <span class="lang-zh">Python 之路：从基础到高级应用</span>
                </h2>
                <p class="text-center text-md text-[#4A5568] max-w-3xl mx-auto mb-8">
                    <span class="lang-en">Progress from fundamental syntax to building complex applications, mastering data structures, object-oriented principles, and powerful libraries along the way.</span>
                    <span class="lang-zh">从基础语法到构建复杂应用，一路掌握数据结构、面向对象原则和强大的库。</span>
                </p>
                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                    <div class="bg-white rounded-lg shadow-md p-6">
                        <h3 class="font-bold text-xl mb-3 text-[#E63946]">
                            <span class="lang-en">Python 1: Core Fundamentals</span>
                            <span class="lang-zh">Python 1：核心基础</span>
                        </h3>
                        <p class="text-sm text-[#4A5568]">
                            <span class="lang-en">Introduces the basics of Python language, variables, operators, conditional statements, loop statements, lists, and basic applications of functions.</span>
                            <span class="lang-zh">介绍 Python 语言基础知识、变量、运算符、条件语句、循环语句、列表和函数的基础应用。</span>
                        </p>
                    </div>
                    <div class="bg-white rounded-lg shadow-md p-6">
                        <h3 class="font-bold text-xl mb-3 text-[#E63946]">
                            <span class="lang-en">Python 2: Data Structures & OOP</span>
                            <span class="lang-zh">Python 2：数据结构与面向对象编程</span>
                        </h3>
                        <p class="text-sm text-[#4A5568]">
                            <span class="lang-en">Explain advanced data structures, such as tuple, set, dictionary, advanced application of functions, and introduce object-oriented programming.</span>
                            <span class="lang-zh">解释高级数据结构，如元组、集合、字典、函数的高级应用，并介绍面向对象编程。</span>
                        </p>
                    </div>
                    <div class="bg-white rounded-lg shadow-md p-6">
                        <h3 class="font-bold text-xl mb-3 text-[#E63946]">
                            <span class="lang-en">Python 3: Advanced Techniques</span>
                            <span class="lang-zh">Python 3：高级技术</span>
                        </h3>
                        <p class="text-sm text-[#4A5568]">
                            <span class="lang-en">Explain multidimensional list, nested loops, recursive functions, advanced object-oriented programming, and introduce the use of basic Python libraries.</span>
                            <span class="lang-zh">解释多维列表、嵌套循环、递归函数、高级面向对象编程，并介绍基本 Python 库的使用。</span>
                        </p>
                    </div>
                    <div class="bg-white rounded-lg shadow-md p-6">
                        <h3 class="font-bold text-xl mb-3 text-[#457B9D]">
                            <span class="lang-en">Python 4: Libraries & Visualization</span>
                            <span class="lang-zh">Python 4：库与可视化</span>
                        </h3>
                        <p class="text-sm text-[#4A5568]">
                            <span class="lang-en">Explain the use of various Python standard libraries and third-party libraries, including the creation of various applications such as drawing, painting, graph, graphical user interface, animations, etc.</span>
                            <span class="lang-zh">解释各种 Python 标准库和第三方库的使用，包括创建各种应用程序，如绘图、绘画、图表、图形用户界面、动画等。</span>
                        </p>
                    </div>
                    <div class="bg-white rounded-lg shadow-md p-6">
                        <h3 class="font-bold text-xl mb-3 text-[#457B9D]">
                            <span class="lang-en">Python 5: Application Design</span>
                            <span class="lang-zh">Python 5：应用设计</span>
                        </h3>
                        <p class="text-sm text-[#4A5568]">
                            <span class="lang-en">Explain game design and data analysis. Game design is the main content of the lecture, and the focus will be on design and developing four simple games. Finally, a brief introduction to data analysis will be given.</span>
                            <span class="lang-zh">解释游戏设计和数据分析。游戏设计是课程的主要内容，重点是设计和开发四款简单的游戏。最后，将简要介绍数据分析。</span>
                        </p>
                    </div>
                    <div class="bg-white rounded-lg shadow-md p-6">
                        <h3 class="font-bold text-xl mb-3 text-[#1D3557]">
                            <span class="lang-en">Python 6: Specializations</span>
                            <span class="lang-zh">Python 6：专业化</span>
                        </h3>
                        <p class="text-sm text-[#4A5568] mb-4">
                            <span class="lang-en">This course covers website backend development, data analysis, and traditional machine learning methods. Interested students can continue with the later Python data analysis courses, large language models, image recognition, and Python full-stack development courses.</span>
                            <span class="lang-zh">本课程涵盖网站后端开发、数据分析和传统机器学习方法。感兴趣的学生可以继续学习后续的 Python 数据分析、大语言模型、图像识别和 Python 全栈开发课程。</span>
                        </p>
                        <p class="text-xs text-red-600 mt-2 font-semibold">
                            <span class="lang-en">(This course is limited to students who have taken AP Calculus.)</span>
                            <span class="lang-zh">（本课程仅限于已修读 AP 微积分的学生。）</span>
                        </p>
                    </div>
                </div>
            </section>

            <section id="performance-leap" class="mb-12">
                <div class="relative text-center mb-6 flow-line">
                    <div class="w-12 h-12 rounded-full inline-flex items-center justify-center text-2xl timeline-icon">🚀</div>
                </div>
                <h2 class="text-center text-3xl font-bold text-[#2D3748] mb-4">
                    <span class="lang-en">The Performance Leap: Transition to C++</span>
                    <span class="lang-zh">性能飞跃：过渡到 C++</span>
                </h2>
                <p class="text-center text-md text-[#4A5568] max-w-3xl mx-auto mb-8">
                    <span class="lang-en">While Python is excellent for learning, competitive programming demands maximum performance. C++ offers the speed and low-level control necessary to solve complex problems within tight time limits. This section highlights the importance of this transition.</span>
                    <span class="lang-zh">Python 非常适合学习，但竞争性编程需要极致的性能。C++ 提供了在紧张的时间限制内解决复杂问题所需的速度和底层控制。本节重点介绍此过渡的重要性。</span>
                </p>
                <div class="grid grid-cols-1 md:grid-cols-2 gap-8 items-center">
                    <div class="bg-white rounded-lg shadow-md p-6">
                        <h3 class="font-bold text-xl mb-3 text-[#457B9D]">
                            <span class="lang-en">Why C++? Speed & Efficiency</span>
                            <span class="lang-zh">为什么选择 C++？速度与效率</span>
                        </h3>
                        <p class="text-sm text-[#4A5568] mb-4">
                            <span class="lang-en">C++ is a compiled language, which runs significantly faster than interpreted languages like Python. The chart illustrates the conceptual performance gap that makes C++ the standard for competitions.</span>
                            <span class="lang-zh">C++ 是一种编译型语言，其运行速度明显快于 Python 等解释型语言。图表说明了概念上的性能差距，这使得 C++ 成为竞赛的标准。</span>
                        </p>
                        <ul class="list-disc list-inside text-[#4A5568] space-y-2 text-sm">
                            <li><span class="lang-en">Static typing for error prevention</span><span class="lang-zh">静态类型以防止错误</span></li>
                            <li><span class="lang-en">Mastery of the Standard Template Library (STL)</span><span class="lang-zh">掌握标准模板库（STL）</span></li>
                            <li><span class="lang-en">Essential containers: vector, set, map</span><span class="lang-zh">基本容器：vector, set, map</span></li>
                            <li><span class="lang-en">Key algorithms: sort, binary_search</span><span class="lang-zh">关键算法：sort, binary_search</span></li>
                        </ul>
                    </div>
                    <div class="bg-white rounded-lg shadow-md p-6">
                        <div class="chart-container">
                            <canvas id="performanceChart"></canvas>
                        </div>
                    </div>
                </div>
            </section>

            <section id="cpp-courses" class="mb-12">
                <div class="relative text-center mb-6 flow-line">
                    <div class="w-12 h-12 rounded-full inline-flex items-center justify-center text-2xl timeline-icon">💻</div>
                </div>
                <h2 class="text-center text-3xl font-bold text-[#2D3748] mb-4">
                    <span class="lang-en">C++ Mastery Series</span>
                    <span class="lang-zh">C++ 精通系列</span>
                </h2>
                <p class="text-center text-md text-[#4A5568] max-w-3xl mx-auto mb-8">
                    <span class="lang-en">The C++ sequence is designed to systematically build your proficiency from syntax basics, through object-oriented programming, and finally to advanced algorithms and classic problems.</span>
                    <span class="lang-zh">C++ 系列课程旨在系统地培养您的 C++ 熟练度，从基本语法到面向对象编程，再到高级算法和经典问题。</span>
                </p>
                <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                    <div class="bg-white rounded-lg shadow-md p-6">
                        <h3 class="font-bold text-xl mb-3 text-[#457B9D]">
                            <span class="lang-en">C++ 1: Syntax & Fundamentals</span>
                            <span class="lang-zh">C++ 1：语法与基础</span>
                        </h3>
                        <p class="text-sm text-[#4A5568] mb-4">
                            <span class="lang-en">This course introduces basic C++ syntax, topics include the analysis and use of concepts such as: primitive data types and their operators, basic I/O, control statements, decision making, looping, function, arrays, strings and file I/O.</span>
                            <span class="lang-zh">本课程介绍基本的 C++ 语法，主题包括：原始数据类型及其运算符、基本 I/O、控制语句、决策、循环、函数、数组、字符串和文件 I/O 的分析和使用。</span>
                        </p>
                        <ul class="list-disc list-inside text-[#4A5568] space-y-2 text-sm">
                            <li><span class="lang-en">Primitive data types & operators</span><span class="lang-zh">原始数据类型和运算符</span></li>
                            <li><span class="lang-en">Basic input/output</span><span class="lang-zh">基本输入/输出</span></li>
                            <li><span class="lang-en">Control flow (if, switch, loops)</span><span class="lang-zh">控制流（if, switch, loops）</span></li>
                            <li><span class="lang-en">Functions, arrays, strings</span><span class="lang-zh">函数、数组、字符串</span></li>
                            <li><span class="lang-en">Basic file input/output</span><span class="lang-zh">基本文件输入/输出</span></li>
                        </ul>
                    </div>
                    <div class="bg-white rounded-lg shadow-md p-6">
                        <h3 class="font-bold text-xl mb-3 text-[#457B9D]">
                            <span class="lang-en">C++ 2: Object-Oriented Programming</span>
                            <span class="lang-zh">C++ 2：面向对象编程</span>
                        </h3>
                        <p class="text-sm text-[#4A5568] mb-4">
                            <span class="lang-en">This course covers object-oriented programming principles and techniques using C++. Topics include pointers, classes, overloading, data abstraction, information hiding, encapsulation, inheritance, polymorphism, file processing, templates, exceptions, container classes, and low-level language features.</span>
                            <span class="lang-zh">本课程使用 C++ 涵盖面向对象编程原则和技术。主题包括指针、类、重载、数据抽象、信息隐藏、封装、继承、多态、文件处理、模板、异常、容器类和低级语言特性。</span>
                        </p>
                        <ul class="list-disc list-inside text-[#4A5568] space-y-2 text-sm">
                            <li><span class="lang-en">Pointers & memory management</span><span class="lang-zh">指针和内存管理</span></li>
                            <li><span class="lang-en">Classes & overloading</span><span class="lang-zh">类和重载</span></li>
                            <li><span class="lang-en">Abstraction, encapsulation, inheritance</span><span class="lang-zh">抽象、封装、继承</span></li>
                            <li><span class="lang-en">Polymorphism & templates</span><span class="lang-zh">多态和模板</span></li>
                            <li><span class="lang-en">Exceptions & file processing</span><span class="lang-zh">异常和文件处理</span></li>
                            <li><span class="lang-en">Container classes & STL</span><span class="lang-zh">容器类和 STL</span></li>
                        </ul>
                    </div>
                    <div class="bg-white rounded-lg shadow-md p-6">
                        <h3 class="font-bold text-xl mb-3 text-[#457B9D]">
                            <span class="lang-en">C++ 3: Classic Algorithms & Problems</span>
                            <span class="lang-zh">C++ 3：经典算法与问题</span>
                        </h3>
                        <p class="text-sm text-[#4A5568] mb-4">
                            <span class="lang-en">This course introduces advanced algorithm use various classic problem include eight queens problem, eight number, Hanoi tower, Shortest path, Stale marriage, pretty print eight queens, subset sum, and Bishop.</span>
                            <span class="lang-zh">本课程介绍高级算法，并应用各种经典问题，包括八皇后问题、八数码、汉诺塔、最短路径、稳定婚姻、漂亮的八皇后打印、子集和、和主教问题。</span>
                        </p>
                        <ul class="list-disc list-inside text-[#4A5568] space-y-2 text-sm">
                            <li><span class="lang-en">Eight queens problem</span><span class="lang-zh">八皇后问题</span></li>
                            <li><span class="lang-en">Eight number puzzle</span><span class="lang-zh">八数码谜题</span></li>
                            <li><span class="lang-en">Hanoi tower</span><span class="lang-zh">汉诺塔</span></li>
                            <li><span class="lang-en">Shortest path algorithms</span><span class="lang-zh">最短路径算法</span></li>
                            <li><span class="lang-en">Stable marriage problem</span><span class="lang-zh">稳定婚姻问题</span></li>
                            <li><span class="lang-en">Pretty print eight queens</span><span class="lang-zh">漂亮的八皇后打印</span></li>
                            <li><span class="lang-en">Subset sum problem</span><span class="lang-zh">子集和问题</span></li>
                            <li><span class="lang-en">Bishop placement problem</span><span class="lang-zh">主教放置问题</span></li>
                        </ul>
                    </div>
                </div>
            </section>

            <section id="web-technology-branch" class="mb-12">
                <div class="relative text-center mb-6 flow-line">
                    <div class="w-12 h-12 rounded-full inline-flex items-center justify-center text-2xl timeline-icon">🌐</div>
                </div>
                <h2 class="text-center text-3xl font-bold text-[#2D3748] mb-4">
                    <span class="lang-en">Web Development Branch</span>
                    <span class="lang-zh">Web 开发分支</span>
                </h2>
                <p class="text-center text-md text-[#4A5568] max-w-3xl mx-auto mb-8">
                    <span class="lang-en">Explore front-end web technologies and browser-based game design, building interactive applications and games using modern web standards.</span>
                    <span class="lang-zh">探索前端 Web 技术和基于浏览器的游戏设计，使用现代 Web 标准构建交互式应用程序和游戏。</span>
                </p>
                <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                    <div class="bg-white rounded-lg shadow-md p-6">
                        <h3 class="font-bold text-xl mb-3 text-[#457B9D]">
                            <span class="lang-en">Web Technology I - Front End</span>
                            <span class="lang-zh">Web 技术 I - 前端</span>
                        </h3>
                        <p class="text-sm text-[#4A5568] mb-4">
                            <span class="lang-en">This course focuses on students developing competency in coding the user experience and user interaction (UI/UX) for front-end, browser-based web applications using HTML, CSS, JavaScript & CSS Frameworks. The student will publish static websites to the internet using traditional web servers and modern object storage while learning current best practices and design patterns for UI/UX website implementation.</span>
                            <span class="lang-zh">本课程重点培养学生使用 HTML、CSS、JavaScript 和 CSS 框架为前端、基于浏览器的 Web 应用程序编写用户体验和用户交互（UI/UX）代码的能力。学生将学习当前 UI/UX 网站实施的最佳实践和设计模式，同时使用传统 Web 服务器和现代对象存储将静态网站发布到互联网。</span>
                        </p>
                        <ul class="list-disc list-inside text-[#4A5568] space-y-2 text-sm">
                            <li><span class="lang-en">HTML & CSS languages</span><span class="lang-zh">HTML 和 CSS 语言</span></li>
                            <li><span class="lang-en">CSS & JavaScript frameworks</span><span class="lang-zh">CSS 和 JavaScript 框架</span></li>
                            <li><span class="lang-en">Responsive web design</span><span class="lang-zh">响应式网页设计</span></li>
                            <li><span class="lang-en">Source code/version control</span><span class="lang-zh">源代码/版本控制</span></li>
                            <li><span class="lang-en">UI/UX best practices & design patterns</span><span class="lang-zh">UI/UX 最佳实践和设计模式</span></li>
                            <li><span class="lang-en">Publish websites to the internet (web servers & object storage)</span><span class="lang-zh">将网站发布到互联网（Web 服务器和对象存储）</span></li>
                        </ul>
                    </div>
                    <div class="bg-white rounded-lg shadow-md p-6">
                        <h3 class="font-bold text-xl mb-3 text-[#457B9D]">
                            <span class="lang-en">Web Based Game Design</span>
                            <span class="lang-zh">基于网页的游戏设计</span>
                        </h3>
                        <p class="text-sm text-[#4A5568] mb-4">
                            <span class="lang-en">This course is about creating Interactive Webpage Games, a hands-on course designed for aspiring developers and enthusiasts eager to build classic arcade-style games using vanilla JavaScript and HTML5 Canvas! Perfect for beginners with basic HTML, CSS, and JavaScript knowledge, this course guides you through creating five iconic browser-based games—Snake, Pong, Space Shooter, Tetris, and Ink Spill (a Flood It clone)—step by step, covering game loops, collision detection, animations, scoring, and more. With no game engines required, you’ll master practical skills like physics, user input, and array manipulation while building a portfolio of playable games that run in any modern browser.</span>
                            <span class="lang-zh">本课程是关于创建交互式网页游戏，这是一门专为有抱负的开发者和爱好者设计的实践课程，他们渴望使用纯 JavaScript 和 HTML5 Canvas 构建经典的街机风格游戏！本课程非常适合具备基本 HTML、CSS 和 JavaScript 知识的初学者，它将逐步指导您创建五款标志性的基于浏览器的游戏——贪吃蛇、Pong、太空射击、俄罗斯方块和 Ink Spill（Flood It 的克隆版）——涵盖游戏循环、碰撞检测、动画、计分等。无需游戏引擎，您将掌握物理、用户输入和数组操作等实用技能，同时构建一个可在任何现代浏览器中运行的可玩游戏作品集。</span>
                        </p>
                        <ul class="list-disc list-inside text-[#4A5568] space-y-2 text-sm">
                            <li><span class="lang-en">Snake</span><span class="lang-zh">贪吃蛇</span></li>
                            <li><span class="lang-en">Pong</span><span class="lang-zh">Pong</span></li>
                            <li><span class="lang-en">Space Shooter</span><span class="lang-zh">太空射击</span></li>
                            <li><span class="lang-en">Tetris</span><span class="lang-zh">俄罗斯方块</span></li>
                            <li><span class="lang-en">Ink Spill (Flood It)</span><span class="lang-zh">Ink Spill（Flood It）</span></li>
                            <li><span class="lang-en">Game loop & animation basics</span><span class="lang-zh">游戏循环和动画基础</span></li>
                            <li><span class="lang-en">Collision detection</span><span class="lang-zh">碰撞检测</span></li>
                            <li><span class="lang-en">Scoring systems</span><span class="lang-zh">计分系统</span></li>
                            <li><span class="lang-en">User input & event handling</span><span class="lang-zh">用户输入和事件处理</span></li>
                            <li><span class="lang-en">Physics & array manipulation</span><span class="lang-zh">物理和数组操作</span></li>
                            <li><span class="lang-en">Building a playable game portfolio for browsers</span><span class="lang-zh">为浏览器构建可玩的游戏作品集</span></li>
                        </ul>
                    </div>
                    <div class="bg-white rounded-lg shadow-md p-6">
                        <h3 class="font-bold text-xl mb-3 text-[#457B9D]">
                            <span class="lang-en">Linux</span>
                            <span class="lang-zh">Linux</span>
                        </h3>
                        <p class="text-sm text-[#4A5568] mb-4">
                            <span class="lang-en">This foundation course introduces the basics of Linux system administration and security.</span>
                            <span class="lang-zh">本基础课程介绍 Linux 系统管理和安全的基础知识。</span>
                        </p>
                        <ul class="list-disc list-inside text-[#4A5568] space-y-2 text-sm">
                            <li><span class="lang-en">Shell commands and processes</span><span class="lang-zh">Shell 命令和进程</span></li>
                            <li><span class="lang-en">Files and directory structure</span><span class="lang-zh">文件和目录结构</span></li>
                            <li><span class="lang-en">User and group management</span><span class="lang-zh">用户和组管理</span></li>
                            <li><span class="lang-en">Networking</span><span class="lang-zh">网络</span></li>
                            <li><span class="lang-en">Shell scripting</span><span class="lang-zh">Shell 脚本</span></li>
                            <li><span class="lang-en">Vulnerability analysis</span><span class="lang-zh">漏洞分析</span></li>
                            <li><span class="lang-en">Intrusion detection</span><span class="lang-zh">入侵检测</span></li>
                            <li><span class="lang-en">Firewall</span><span class="lang-zh">防火墙</span></li>
                            <li><span class="lang-en">File system encryption</span><span class="lang-zh">文件系统加密</span></li>
                        </ul>
                    </div>
                    <div class="bg-white rounded-lg shadow-md p-6">
                        <h3 class="font-bold text-xl mb-3 text-[#457B9D]">
                            <span class="lang-en">Introduction to Database Systems</span>
                            <span class="lang-zh">数据库系统导论</span>
                        </h3>
                        <p class="text-sm text-[#4A5568] mb-4">
                            <span class="lang-en">This course introduces Database Management Systems (DBMS), contrasting them with flat file processing, and covers data abstraction, models, and DML/DDL languages, focusing on relational databases, SQL, and relational algebra (schemas, table keys, operations). Students learn SQL for table creation and queries (joins, aggregation, union), ER modeling with entity sets and relationships (using a university example), database design to avoid redundancy via normalization (BCNF, 3NF), and indexing/hashing (primary/secondary indices, static/dynamic hashing) to optimize data retrieval, enabling them to design and manage efficient database systems.</span>
                            <span class="lang-zh">本课程介绍数据库管理系统 (DBMS)，将其与平面文件处理进行对比，并涵盖数据抽象、模型和 DML/DDL 语言，重点是关系数据库、SQL 和关系代数（模式、表键、操作）。学生将学习用于表创建和查询的 SQL（连接、聚合、联合）、带有实体集和关系的 ER 建模（使用大学示例）、通过规范化（BCNF、3NF）进行数据库设计以避免冗余，以及索引/哈希（主/次级索引、静态/动态哈希）以优化数据检索，使他们能够设计和管理高效的数据库系统。</span>
                        </p>
                    </div>
                </div>
            </section>

            <section id="ap-courses" class="mb-12">
                <div class="relative text-center mb-6 flow-line">
                    <div class="w-12 h-12 rounded-full inline-flex items-center justify-center text-2xl timeline-icon">📚</div>
                </div>
                <h2 class="text-center text-3xl font-bold text-[#2D3748] mb-4">
                    <span class="lang-en">AP Computer Science Courses</span>
                    <span class="lang-zh">AP 计算机科学课程</span>
                </h2>
                <p class="text-center text-md text-[#4A5568] max-w-3xl mx-auto mb-8">
                    <span class="lang-en">Prepare for AP exams with these comprehensive courses covering computer science principles and Java programming fundamentals.</span>
                    <span class="lang-zh">通过这些涵盖计算机科学原理和 Java 编程基础知识的综合课程为 AP 考试做准备。</span>
                </p>
                <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                    <div class="bg-white rounded-lg shadow-md p-6">
                        <h3 class="font-bold text-xl mb-3 text-[#457B9D]">
                            <span class="lang-en">AP Computer Science Principles</span>
                            <span class="lang-zh">AP 计算机科学原理</span>
                        </h3>
                        <p class="text-sm text-[#4A5568] mb-4">
                            <span class="lang-en">Dive into the exciting world of computing with AP Computer Science Principles, a dynamic course crafted for high school students to explore the foundations of computer science while preparing for the AP CSP exam! This course introduces you to the big ideas of computing through 19 engaging topics, including lists, binary numbers, variables, data compression, the digital divide, the Internet, fault-tolerant systems, crowdsourcing, legal and ethical issues, collaboration, algorithmic efficiency, data abstraction, simulations, program design, data analysis, Boolean expressions, iteration, binary search, procedures, computing impacts, and safe computing practices. Using languages like Python or JavaScript, you’ll tackle hands-on projects such as designing simulations, analyzing datasets, or building collaborative programs, all while developing critical thinking and problem-solving skills.</span>
                            <span class="lang-zh">通过 AP 计算机科学原理课程，深入探索令人兴奋的计算世界。这是一门为高中生量身定制的动态课程，旨在探索计算机科学的基础知识，同时为 AP CSP 考试做准备！本课程通过 19 个引人入胜的主题向您介绍计算的核心思想，包括列表、二进制数、变量、数据压缩、数字鸿沟、互联网、容错系统、众包、法律和道德问题、协作、算法效率、数据抽象、模拟、程序设计、数据分析、布尔表达式、迭代、二分搜索、过程、计算影响和安全计算实践。您将使用 Python 或 JavaScript 等语言，完成诸如设计模拟、分析数据集或构建协作程序等实践项目，同时培养批判性思维和解决问题的能力。</span>
                        </p>
                    </div>
                    <div class="bg-white rounded-lg shadow-md p-6">
                        <h3 class="font-bold text-xl mb-3 text-[#457B9D]">
                            <span class="lang-en">Introduction to Java Programming (AP Computer Science A)</span>
                            <span class="lang-zh">Java 编程导论（AP 计算机科学 A）</span>
                        </h3>
                        <p class="text-sm text-[#4A5568] mb-4">
                            <span class="lang-en">This course uses Java to teach essential computer science concepts through hands-on coding, problem-solving, and project-based learning, equipping you with the skills to build robust applications and tackle real-world challenges. Tailored to meet the College Board’s AP CS A curriculum, it covers 17 key topics, including console I/O, strings, variables, expressions, branching, loops, functions, recursion, arrays, object-oriented programming (classes, inheritance, polymorphism), data structures (ArrayList, LinkedList, Map, Set), exception handling, file I/O, GUI development with AWT/Swing, and search/sort algorithms. Perfect for beginners and intermediate coders, you’ll develop a strong foundation in Java programming, logical thinking, and algorithm design, culminating in the ability to create interactive applications and games.</span>
                            <span class="lang-zh">本课程使用 Java 通过动手编码、解决问题和基于项目的学习来教授基本的计算机科学概念，为您提供构建健壮应用程序和应对现实世界挑战的技能。本课程根据 College Board 的 AP CS A 课程量身定制，涵盖 17 个关键主题，包括控制台 I/O、字符串、变量、表达式、分支、循环、函数、递归、数组、面向对象编程（类、继承、多态）、数据结构（ArrayList、LinkedList、Map、Set）、异常处理、文件 I/O、使用 AWT/Swing 进行 GUI 开发以及搜索/排序算法。本课程非常适合初学者和中级编码人员，您将打下坚实的 Java 编程、逻辑思维和算法设计基础，最终能够创建交互式应用程序和游戏。</span>
                        </p>
                    </div>
                </div>
            </section>

            <section id="usaco-arena" class="mb-12">
                <div class="relative text-center mb-6 flow-line">
                    <div class="w-12 h-12 rounded-full inline-flex items-center justify-center text-2xl timeline-icon">🏆</div>
                </div>
                <h2 class="text-center text-3xl font-bold text-[#2D3748] mb-4">
                    <span class="lang-en">The Competitive Arena: USACO Tiers</span>
                    <span class="lang-zh">竞技场：USACO 等级</span>
                </h2>
                <p class="text-center text-md text-[#4A5568] max-w-3xl mx-auto mb-8">
                    <span class="lang-en">The USA Computing Olympiad (USACO) is the premier competition for high school programmers. The journey is divided into four tiers, each demanding a deeper understanding of algorithms and data structures, as shown in the skills radar chart.</span>
                    <span class="lang-zh">美国计算机奥林匹克竞赛（USACO）是高中程序员的首要竞赛。旅程分为四个等级，每个等级都需要对算法和数据结构有更深入的理解，如技能雷达图所示。</span>
                </p>
                <div class="bg-white rounded-lg shadow-md p-6 mb-8">
                    <div class="chart-container h-[400px] md:h-[450px]">
                        <canvas id="usacoSkillsRadar"></canvas>
                    </div>
                </div>
                <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                    <div class="bg-white rounded-lg shadow-md p-6 border-l-4 border-[#A8DADC]">
                        <h3 class="font-bold text-xl mb-3 text-[#1D3557]">
                            <span class="lang-en">USACO Bronze</span>
                            <span class="lang-zh">USACO 青铜级</span>
                        </h3>
                        <p class="text-sm text-[#4A5568] mb-4">
                            <span class="lang-en">Focuses on direct translation of problem statements into code. Implementation skills are paramount.</span>
                            <span class="lang-zh">专注于将问题陈述直接转换为代码。实现技能至关重要。</span>
                        </p>
                        <ul class="list-disc list-inside text-[#4A5568] space-y-2 text-sm">
                            <li><span class="lang-en">Complete Search / Brute-force</span><span class="lang-zh">完全搜索/暴力破解</span></li>
                            <li><span class="lang-en">Simulation of rules</span><span class="lang-zh">规则模拟</span></li>
                            <li><span class="lang-en">Basic data structures & sorting</span><span class="lang-zh">基本数据结构和排序</span></li>
                        </ul>
                    </div>
                    <div class="bg-white rounded-lg shadow-md p-6 border-l-4 border-[#457B9D]">
                        <h3 class="font-bold text-xl mb-3 text-[#1D3557]">
                            <span class="lang-en">USACO Silver</span>
                            <span class="lang-zh">USACO 白银级</span>
                        </h3>
                        <p class="text-sm text-[#4A5568] mb-4">
                            <span class="lang-en">Requires knowledge of standard, efficient algorithms to pass time limits where brute-force fails.</span>
                            <span class="lang-zh">需要掌握标准的、高效的算法，以在暴力破解失败时通过时间限制。</span>
                        </p>
                        <ul class="list-disc list-inside text-[#4A5568] space-y-2 text-sm">
                            <li><span class="lang-en">Binary Search</span><span class="lang-zh">二分搜索</span></li>
                            <li><span class="lang-en">Greedy Algorithms</span><span class="lang-zh">贪心算法</span></li>
                            <li><span class="lang-en">Graph Traversal (DFS, BFS)</span><span class="lang-zh">图遍历（DFS、BFS）</span></li>
                            <li><span class="lang-en">Prefix Sums / Two Pointers</span><span class="lang-zh">前缀和/双指针</span></li>
                        </ul>
                    </div>
                    <div class="bg-white rounded-lg shadow-md p-6 border-l-4 border-[#1D3557]">
                        <h3 class="font-bold text-xl mb-3 text-[#1D3557]">
                            <span class="lang-en">USACO Gold</span>
                            <span class="lang-zh">USACO 黄金级</span>
                        </h3>
                        <p class="text-sm text-[#4A5568] mb-4">
                            <span class="lang-en">Demands mastery of advanced algorithms and data structures to solve complex, multi-step problems.</span>
                            <span class="lang-zh">需要掌握高级算法和数据结构来解决复杂的、多步骤的问题。</span>
                        </p>
                        <ul class="list-disc list-inside text-[#4A5568] space-y-2 text-sm">
                            <li><span class="lang-en">Dynamic Programming (DP)</span><span class="lang-zh">动态规划（DP）</span></li>
                            <li><span class="lang-en">Advanced Graph Algorithms (Dijkstra's)</span><span class="lang-zh">高级图算法（Dijkstra's）</span></li>
                            <li><span class="lang-en">Union-Find (DSU)</span><span class="lang-zh">并查集（DSU）</span></li>
                            <li><span class="lang-en">Introductory Segment Trees</span><span class="lang-zh">线段树入门</span></li>
                        </ul>
                    </div>
                    <div class="bg-white rounded-lg shadow-md p-6 border-l-4 border-[#E63946]">
                        <h3 class="font-bold text-xl mb-3 text-[#1D3557]">
                            <span class="lang-en">USACO Platinum</span>
                            <span class="lang-zh">USACO 白金级</span>
                        </h3>
                        <p class="text-sm text-[#4A5568] mb-4">
                            <span class="lang-en">The elite level, featuring problems that often require novel insights or modifications of known algorithms.</span>
                            <span class="lang-zh">精英级别，其问题通常需要新颖的见解或对已知算法的修改。</span>
                        </p>
                        <ul class="list-disc list-inside text-[#4A5568] space-y-2 text-sm">
                            <li><span class="lang-en">Advanced DP Optimizations</span><span class="lang-zh">高级动态规划优化</span></li>
                            <li><span class="lang-en">Complex Data Structures</span><span class="lang-zh">复杂数据结构</span></li>
                            <li><span class="lang-en">Network Flow Algorithms</span><span class="lang-zh">网络流算法</span></li>
                            <li><span class="lang-en">Computational Geometry</span><span class="lang-zh">计算几何</span></li>
                        </ul>
                    </div>
                </div>
            </section>

            <section id="ai-research" class="mb-12">
                <div class="relative text-center mb-6 flow-line">
                    <div class="w-12 h-12 rounded-full inline-flex items-center justify-center text-2xl timeline-icon">🤖</div>
                </div>
                <h2 class="text-center text-3xl font-bold text-[#2D3748] mb-4">
                    <span class="lang-en">AI Research Specialization</span>
                    <span class="lang-zh">AI 研究专业化</span>
                </h2>
                <p class="text-center text-md text-[#4A5568] max-w-3xl mx-auto mb-8">
                    <span class="lang-en">Advanced AI courses for students who have completed USACO Bronze and advanced to Silver level. These specialized courses prepare students for the USA Artificial Intelligence Olympiad (USAAIO) and focus on cutting-edge AI research and applications.</span>
                    <span class="lang-zh">面向已完成 USACO 青铜级并晋升到白银级的学生的高级 AI 课程。这些专业课程为学生准备美国人工智能奥林匹克竞赛（USAAIO），并专注于前沿的 AI 研究和应用。</span>
                </p>
                <p class="text-center text-xs text-red-600 font-semibold mb-4">
                    <span class="lang-en">(Prerequisite: Completion of USACO Bronze and promotion to Silver level)</span>
                    <span class="lang-zh">（先决条件：完成 USACO 青铜级并晋升到白银级）</span>
                </p>
                <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                    <div class="bg-white rounded-lg shadow-md p-6">
                        <h3 class="font-bold text-xl mb-3 text-[#1D3557]">
                            <span class="lang-en">Machine Learning</span>
                            <span class="lang-zh">机器学习</span>
                        </h3>
                        <p class="text-sm text-[#4A5568] mb-4">
                            <span class="lang-en">This course provides a broad introduction to machine learning and statistical pattern recognition. Topics include supervised learning, unsupervised learning, learning theory, reinforcement learning, and adaptive control. Students will examine the purpose of machine learning and how it applies to solving real-world problems. A general overview of machine learning topics, including classification, regression, clustering, and various machine learning algorithms, will be covered. The course will also explore recent applications of machine learning. Students will apply machine learning concepts to practical examples using various AI tools.</span>
                            <span class="lang-zh">本课程广泛介绍机器学习和统计模式识别。主题包括监督学习、无监督学习、学习理论、强化学习和自适应控制。学生将研究机器学习的目的以及它如何应用于解决现实世界问题。将涵盖机器学习主题的总体概述，包括分类、回归、聚类和各种机器学习算法。课程还将探讨机器学习的最新应用。学生将使用各种 AI 工具将机器学习概念应用于实际示例。</span>
                        </p>
                    </div>
                    <div class="bg-white rounded-lg shadow-md p-6">
                        <h3 class="font-bold text-xl mb-3 text-[#1D3557]">
                            <span class="lang-en">Natural Language Processing</span>
                            <span class="lang-zh">自然语言处理</span>
                        </h3>
                        <p class="text-sm text-[#4A5568] mb-4">
                            <span class="lang-en">This course provides a comprehensive introduction to Natural Language Processing (NLP), a core area of Artificial Intelligence focused on enabling computers to process, understand, and generate human language, covering fundamental linguistic concepts, statistical methods, and deep learning approaches like RNNs, LSTMs, and Transformers, with hands-on programming assignments using popular NLP libraries to explore topics such as language models, word representations, text preprocessing, feature extraction, part-of-speech tagging, parsing, syntax, information retrieval, text classification, sentiment analysis, opinion mining, sequence models (HMMs, CRFs), pretrained models like BERT and GPT, and applications in machine translation, question answering, and chatbots, equipping students with practical skills to design, implement, and evaluate NLP systems while addressing challenges like ambiguity, bias, and fairness in language technologies.</span>
                            <span class="lang-zh">本课程全面介绍自然语言处理（NLP），这是人工智能的一个核心领域，专注于使计算机能够处理、理解和生成人类语言。课程涵盖基本的语言学概念、统计方法和深度学习方法，如 RNN、LSTM 和 Transformer，并通过使用流行的 NLP 库的动手编程作业来探索语言模型、词表示、文本预处理、特征提取、词性标注、解析、语法、信息检索、文本分类、情感分析、意见挖掘、序列模型（HMM、CRF）、BERT 和 GPT 等预训练模型以及在机器翻译、问答和聊天机器人中的应用等主题，使学生具备设计、实施和评估 NLP 系统的实用技能，同时解决语言技术中的歧义、偏见和公平等挑战。</span>
                        </p>
                    </div>
                    <div class="bg-white rounded-lg shadow-md p-6">
                        <h3 class="font-bold text-xl mb-3 text-[#1D3557]">
                            <span class="lang-en">Computer Vision</span>
                            <span class="lang-zh">计算机视觉</span>
                        </h3>
                        <p class="text-sm text-[#4A5568] mb-4">
                            <span class="lang-en">This course offers an in-depth introduction to Computer Vision, a rapidly growing field within Artificial Intelligence that enables machines to interpret, analyze, and understand visual information, combining fundamental principles, mathematical foundations, and state-of-the-art techniques with practical programming using libraries like OpenCV, TensorFlow, and PyTorch to cover topics such as image formation, representation, filtering, feature extraction, segmentation, object detection, recognition, motion analysis, 3D vision, convolutional neural networks (CNNs), transfer learning, and vision transformers for tasks like image classification, object detection, and semantic segmentation, with hands-on projects exploring applications in autonomous vehicles, facial recognition, medical imaging, augmented reality, and video analytics, enabling students to bridge classical and deep learning methods and develop real-world vision systems.</span>
                            <span class="lang-zh">本课程深入介绍计算机视觉，这是人工智能中一个快速发展的领域，使机器能够解释、分析和理解视觉信息。课程将基本原理、数学基础和最先进的技术与使用 OpenCV、TensorFlow 和 PyTorch 等库的实践编程相结合，涵盖图像形成、表示、过滤、特征提取、分割、对象检测、识别、运动分析、3D 视觉、卷积神经网络（CNN）、迁移学习和视觉转换器等主题，用于图像分类、对象检测和语义分割等任务。通过实践项目，学生将探索在自动驾驶汽车、人脸识别、医学成像、增强现实和视频分析中的应用，从而能够弥合经典方法和深度学习方法之间的差距，并开发现实世界的视觉系统。</span>
                        </p>
                    </div>
                </div>
            </section>

        </main>
        <section id="contact-us" class="mb-12 text-center">
            <h2 class="text-3xl font-bold text-[#2D3748] mb-4">
                <span class="lang-en">Contact Us</span>
                <span class="lang-zh">联系我们</span>
            </h2>
            <p class="text-md text-[#4A5568] mb-2">
                <span class="lang-en">378 Great Neck Rd, Great Neck, NY</span>
                <span class="lang-zh">纽约州大颈路 378 号</span>
            </p>
            <p class="text-md text-[#4A5568]">
                <span class="lang-en">Phone: </span>
                <span class="lang-zh">电话：</span>
                <a href="tel:(929)-728-3344" class="text-blue-600 hover:underline">(929)-728-3344</a>
            </p>
        </section>
    </div>
    <script>
        document.addEventListener('DOMContentLoaded', () => {
            const html = document.documentElement;
            const switcher = document.getElementById('language-switcher');
            const performanceColors = ['#A8DADC', '#E63946'];
            const usacoColors = ['#A8DADC', '#457B9D', '#1D3557', '#E63946'];

            switcher.addEventListener('click', () => {
                const currentLang = html.getAttribute('lang');
                if (currentLang === 'en') {
                    html.setAttribute('lang', 'zh');
                    switcher.textContent = 'English';
                    performanceChart.data.datasets[0].label = 'Python';
                    performanceChart.data.datasets[1].label = 'C++';
                    performanceChart.options.plugins.title.text = '概念性语言权衡';
                    usacoSkillsRadar.data.labels = processLabels(['实现', '基础算法', '高级算法与数据结构', '解决问题的创造力']);
                    usacoSkillsRadar.data.datasets[0].label = '青铜级';
                    usacoSkillsRadar.data.datasets[1].label = '白银级';
                    usacoSkillsRadar.data.datasets[2].label = '黄金级';
                    usacoSkillsRadar.data.datasets[3].label = '白金级';
                    usacoSkillsRadar.options.plugins.title.text = 'USACO 技能进展雷达图';
                } else {
                    html.setAttribute('lang', 'en');
                    switcher.textContent = '中文';
                    performanceChart.data.datasets[0].label = 'Python';
                    performanceChart.data.datasets[1].label = 'C++';
                    performanceChart.options.plugins.title.text = 'Conceptual Language Trade-offs';
                    usacoSkillsRadar.data.labels = processLabels(['Implementation', 'Basic Algorithms', 'Advanced Algorithms & DS', 'Problem Solving Creativity']);
                    usacoSkillsRadar.data.datasets[0].label = 'Bronze';
                    usacoSkillsRadar.data.datasets[1].label = 'Silver';
                    usacoSkillsRadar.data.datasets[2].label = 'Gold';
                    usacoSkillsRadar.data.datasets[3].label = 'Platinum';
                    usacoSkillsRadar.options.plugins.title.text = 'USACO Skills Progression Radar';
                }
                performanceChart.update();
                usacoSkillsRadar.update();
            });

            const tooltipTitleCallback = (tooltipItems) => {
                const item = tooltipItems[0];
                let label = item.chart.data.labels[item.dataIndex];
                if (Array.isArray(label)) { return label.join(' '); }
                return label;
            };

            const processLabels = (labels) => {
                return labels.map(label => {
                    if (label.length > 16) {
                        const words = label.split(' ');
                        const lines = [];
                        let currentLine = '';
                        for (const word of words) {
                            if ((currentLine + ' ' + word).trim().length > 16 && currentLine.length > 0) {
                                lines.push(currentLine);
                                currentLine = word;
                            } else {
                                currentLine = (currentLine + ' ' + word).trim();
                            }
                        }
                        if (currentLine) { lines.push(currentLine); }
                        return lines;
                    }
                    return label;
                });
            };

            const performanceCtx = document.getElementById('performanceChart').getContext('2d');
            const performanceChart = new Chart(performanceCtx, {
                type: 'bar',
                data: {
                    labels: ['Ease of Learning & Prototyping', 'Execution Speed'],
                    datasets: [
                        { label: 'Python', data: [90, 30], backgroundColor: performanceColors[0], borderColor: performanceColors[0], borderWidth: 1 },
                        { label: 'C++', data: [50, 95], backgroundColor: performanceColors[1], borderColor: performanceColors[1], borderWidth: 1 }
                    ]
                },
                options: {
                    maintainAspectRatio: false,
                    responsive: true,
                    indexAxis: 'y',
                    scales: {
                        x: { beginAtZero: true, max: 100, ticks: { display: false }, grid: { display: false } },
                        y: { grid: { display: false } }
                    },
                    plugins: {
                        legend: { position: 'top' },
                        title: { display: true, text: 'Conceptual Language Trade-offs' },
                        tooltip: { callbacks: { title: tooltipTitleCallback } }
                    }
                }
            });

            const usacoSkillsCtx = document.getElementById('usacoSkillsRadar').getContext('2d');
            const usacoSkillsRadar = new Chart(usacoSkillsCtx, {
                type: 'radar',
                data: {
                    labels: processLabels(['Implementation', 'Basic Algorithms', 'Advanced Algorithms & DS', 'Problem Solving Creativity']),
                    datasets: [
                        { label: 'Bronze', data: [9, 3, 1, 2], borderColor: usacoColors[0], backgroundColor: 'rgba(168, 218, 220, 0.2)' },
                        { label: 'Silver', data: [7, 8, 3, 5], borderColor: usacoColors[1], backgroundColor: 'rgba(69, 123, 157, 0.2)' },
                        { label: 'Gold', data: [6, 7, 8, 8], borderColor: usacoColors[2], backgroundColor: 'rgba(29, 53, 87, 0.2)' },
                        { label: 'Platinum', data: [5, 6, 9, 10], borderColor: usacoColors[3], backgroundColor: 'rgba(230, 57, 70, 0.2)' }
                    ]
                },
                options: {
                    maintainAspectRatio: false,
                    responsive: true,
                    scales: {
                        r: {
                            angleLines: { display: true },
                            suggestedMin: 0,
                            suggestedMax: 10,
                            ticks: { display: false },
                            pointLabels: { font: { size: 14 } }
                        }
                    },
                    plugins: {
                        legend: { position: 'top' },
                        title: { display: true, text: 'USACO Skills Progression Radar' }
                    }
                }
            });
        });
    </script>
</body>
</html>
