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
        body { font-family: 'Inter', sans-serif; }
        .chart-container { position: relative; width: 100%; max-width: 600px; margin-left: auto; margin-right: auto; height: 300px; max-height: 400px; }
        @media (min-width: 768px) { .chart-container { height: 350px; } }
        .flow-line::after { content: ''; position: absolute; left: 50%; transform: translateX(-50%); top: 100%; height: 3rem; width: 2px; background-color: #4A5568; }
        .timeline-icon { background-color: #FFFFFF; border: 2px solid #4A5568; }
    </style>
</head>
<body class="bg-[#F0F4F8]">
    <div class="container mx-auto p-4 md:p-8 max-w-5xl">
        <header class="text-center mb-12 relative">
            <div class="absolute top-0 right-0 flex flex-col items-end space-y-2">
                <a href="index.zh.html" id="language-switcher" class="p-2 bg-[#1D3557] text-white rounded-lg hover:bg-opacity-80 transition-colors">中文</a>
                <a href="index.ko.html" id="language-switcher-ko" class="p-2 bg-[#1D3557] text-white rounded-lg hover:bg-opacity-80 transition-colors">한국어</a>
            </div>
            <h1 class="text-4xl md:text-5xl font-bold text-[#1A202C] mb-2">
                The Competitive Programmer's Journey
            </h1>
            <p class="text-lg text-[#4A5568]">
                From visual blocks to elite algorithms, this is the path to mastery.
            </p>
        </header>
        <main class="relative">

            <!-- Foundation -->
            <section id="foundation" class="mb-12">
                <div class="relative text-center mb-6 flow-line">
                    <div class="w-12 h-12 rounded-full inline-flex items-center justify-center text-2xl timeline-icon">🧩</div>
                </div>
                <h2 class="text-center text-3xl font-bold text-[#2D3748] mb-4">The Foundation: Visual Logic</h2>
                <p class="text-center text-md text-[#4A5568] max-w-3xl mx-auto mb-8">The journey starts by building a strong foundation in computational thinking and problem-solving using visual, block-based programming.</p>
                <div class="grid grid-cols-1 gap-8">
                    <div class="bg-white rounded-lg shadow-md p-6">
                        <h3 class="font-bold text-xl mb-3 text-[#E63946]">Stage 1: Scratch</h3>
                        <p class="text-sm text-[#4A5568] mb-4">Learn programming fundamentals without complex syntax using a visual, block-based system.</p>
                        <ul class="list-disc list-inside text-[#4A5568] space-y-2 text-sm">
                            <li>Variables, Loops & Conditionals</li>
                            <li>Event-driven programming</li>
                            <li>Develop a problem-solving mindset</li>
                        </ul>
                    </div>
                </div>
            </section>

            <!-- Python Path -->
            <section id="python-path" class="mb-12">
                <div class="relative text-center mb-6 flow-line">
                    <div class="w-12 h-12 rounded-full inline-flex items-center justify-center text-2xl timeline-icon">🐍</div>
                </div>
                <h2 class="text-center text-3xl font-bold text-[#2D3748] mb-4">The Python Path: From Basics to Advanced Applications</h2>
                <p class="text-center text-md text-[#4A5568] max-w-3xl mx-auto mb-8">Progress from fundamental syntax to building complex applications, mastering data structures, object-oriented principles, and powerful libraries along the way.</p>
                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                    <div class="bg-white rounded-lg shadow-md p-6">
                        <h3 class="font-bold text-xl mb-3 text-[#E63946]">Python 1: Core Fundamentals</h3>
                        <p class="text-sm text-[#4A5568]">Introduces the basics of Python language, variables, operators, conditional statements, loop statements, lists, and basic applications of functions.</p>
                    </div>
                    <div class="bg-white rounded-lg shadow-md p-6">
                        <h3 class="font-bold text-xl mb-3 text-[#E63946]">Python 2: Data Structures & OOP</h3>
                        <p class="text-sm text-[#4A5568]">Explain advanced data structures, such as tuple, set, dictionary, advanced application of functions, and introduce object-oriented programming.</p>
                    </div>
                    <div class="bg-white rounded-lg shadow-md p-6">
                        <h3 class="font-bold text-xl mb-3 text-[#E63946]">Python 3: Advanced Techniques</h3>
                        <p class="text-sm text-[#4A5568]">Explain multidimensional list, nested loops, recursive functions, advanced object-oriented programming, and introduce the use of basic Python libraries.</p>
                    </div>
                    <div class="bg-white rounded-lg shadow-md p-6">
                        <h3 class="font-bold text-xl mb-3 text-[#457B9D]">Python 4: Libraries & Visualization</h3>
                        <p class="text-sm text-[#4A5568]">Explain the use of various Python standard libraries and third-party libraries, including the creation of various applications such as drawing, painting, graph, graphical user interface, animations, etc.</p>
                    </div>
                    <div class="bg-white rounded-lg shadow-md p-6">
                        <h3 class="font-bold text-xl mb-3 text-[#457B9D]">Python 5: Application Design</h3>
                        <p class="text-sm text-[#4A5568]">Explain game design and data analysis. Game design is the main content of the lecture, and the focus will be on design and developing four simple games. Finally, a brief introduction to data analysis will be given.</p>
                    </div>
                    <div class="bg-white rounded-lg shadow-md p-6">
                        <h3 class="font-bold text-xl mb-3 text-[#1D3557]">Python 6: Specializations</h3>
                        <p class="text-sm text-[#4A5568] mb-4">This course covers website backend development, data analysis, and traditional machine learning methods. Interested students can continue with the later Python data analysis courses, large language models, image recognition, and Python full-stack development courses.</p>
                        <p class="text-xs text-red-600 mt-2 font-semibold">(This course is limited to students who have taken AP Calculus.)</p>
                    </div>
                </div>
            </section>

            <!-- Performance Leap -->
            <section id="performance-leap" class="mb-12">
                <div class="relative text-center mb-6 flow-line">
                    <div class="w-12 h-12 rounded-full inline-flex items-center justify-center text-2xl timeline-icon">🚀</div>
                </div>
                <h2 class="text-center text-3xl font-bold text-[#2D3748] mb-4">The Performance Leap: Transition to C++</h2>
                <p class="text-center text-md text-[#4A5568] max-w-3xl mx-auto mb-8">While Python is excellent for learning, competitive programming demands maximum performance. C++ offers the speed and low-level control necessary to solve complex problems within tight time limits. This section highlights the importance of this transition.</p>
                <div class="grid grid-cols-1 md:grid-cols-2 gap-8 items-center">
                    <div class="bg-white rounded-lg shadow-md p-6">
                        <h3 class="font-bold text-xl mb-3 text-[#457B9D]">Why C++? Speed & Efficiency</h3>
                        <p class="text-sm text-[#4A5568] mb-4">C++ is a compiled language, which runs significantly faster than interpreted languages like Python. The chart illustrates the conceptual performance gap that makes C++ the standard for competitions.</p>
                        <ul class="list-disc list-inside text-[#4A5568] space-y-2 text-sm">
                            <li>Static typing for error prevention</li>
                            <li>Mastery of the Standard Template Library (STL)</li>
                            <li>Essential containers: vector, set, map</li>
                            <li>Key algorithms: sort, binary_search</li>
                        </ul>
                    </div>
                    <div class="bg-white rounded-lg shadow-md p-6">
                        <div class="chart-container">
                            <canvas id="performanceChart"></canvas>
                        </div>
                    </div>
                </div>
            </section>

            <!-- C++ Courses -->
            <section id="cpp-courses" class="mb-12">
                <div class="relative text-center mb-6 flow-line">
                    <div class="w-12 h-12 rounded-full inline-flex items-center justify-center text-2xl timeline-icon">💻</div>
                </div>
                <h2 class="text-center text-3xl font-bold text-[#2D3748] mb-4">C++ Mastery Series</h2>
                <p class="text-center text-md text-[#4A5568] max-w-3xl mx-auto mb-8">The C++ sequence is designed to systematically build your proficiency from syntax basics, through object-oriented programming, and finally to advanced algorithms and classic problems.</p>
                <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                    <div class="bg-white rounded-lg shadow-md p-6">
                        <h3 class="font-bold text-xl mb-3 text-[#457B9D]">C++ 1: Syntax & Fundamentals</h3>
                        <p class="text-sm text-[#4A5568] mb-4">This course introduces basic C++ syntax, topics include the analysis and use of concepts such as: primitive data types and their operators, basic I/O, control statements, decision making, looping, function, arrays, strings and file I/O.</p>
                        <ul class="list-disc list-inside text-[#4A5568] space-y-2 text-sm">
                            <li>Primitive data types & operators</li>
                            <li>Basic input/output</li>
                            <li>Control flow (if, switch, loops)</li>
                            <li>Functions, arrays, strings</li>
                            <li>Basic file input/output</li>
                        </ul>
                    </div>
                    <div class="bg-white rounded-lg shadow-md p-6">
                        <h3 class="font-bold text-xl mb-3 text-[#457B9D]">C++ 2: Object-Oriented Programming</h3>
                        <p class="text-sm text-[#4A5568] mb-4">This course covers object-oriented programming principles and techniques using C++. Topics include pointers, classes, overloading, data abstraction, information hiding, encapsulation, inheritance, polymorphism, file processing, templates, exceptions, container classes, and low-level language features.</p>
                        <ul class="list-disc list-inside text-[#4A5568] space-y-2 text-sm">
                            <li>Pointers & memory management</li>
                            <li>Classes & overloading</li>
                            <li>Abstraction, encapsulation, inheritance</li>
                            <li>Polymorphism & templates</li>
                            <li>Exceptions & file processing</li>
                            <li>Container classes & STL</li>
                        </ul>
                    </div>
                    <div class="bg-white rounded-lg shadow-md p-6">
                        <h3 class="font-bold text-xl mb-3 text-[#457B9D]">C++ 3: Classic Algorithms & Problems</h3>
                        <p class="text-sm text-[#4A5568] mb-4">This course introduces advanced algorithm use various classic problem include eight queens problem, eight number, Hanoi tower, Shortest path, Stale marriage, pretty print eight queens, subset sum, and Bishop.</p>
                        <ul class="list-disc list-inside text-[#4A5568] space-y-2 text-sm">
                            <li>Eight queens problem</li>
                            <li>Eight number puzzle</li>
                            <li>Hanoi tower</li>
                            <li>Shortest path algorithms</li>
                            <li>Stable marriage problem</li>
                            <li>Pretty print eight queens</li>
                            <li>Subset sum problem</li>
                            <li>Bishop placement problem</li>
                        </ul>
                    </div>
                </div>
            </section>

            <!-- Web Development Branch -->
            <section id="web-technology-branch" class="mb-12">
                <div class="relative text-center mb-6 flow-line">
                    <div class="w-12 h-12 rounded-full inline-flex items-center justify-center text-2xl timeline-icon">🌐</div>
                </div>
                <h2 class="text-center text-3xl font-bold text-[#2D3748] mb-4">Web Development Branch</h2>
                <p class="text-center text-md text-[#4A5568] max-w-3xl mx-auto mb-8">Explore front-end web technologies and browser-based game design, building interactive applications and games using modern web standards.</p>
                <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                    <div class="bg-white rounded-lg shadow-md p-6">
                        <h3 class="font-bold text-xl mb-3 text-[#457B9D]">Web Technology I - Front End</h3>
                        <p class="text-sm text-[#4A5568] mb-4">This course focuses on students developing competency in coding the user experience and user interaction (UI/UX) for front-end, browser-based web applications using HTML, CSS, JavaScript & CSS Frameworks. The student will publish static websites to the internet using traditional web servers and modern object storage while learning current best practices and design patterns for UI/UX website implementation.</p>
                        <ul class="list-disc list-inside text-[#4A5568] space-y-2 text-sm">
                            <li>HTML & CSS languages</li>
                            <li>CSS & JavaScript frameworks</li>
                            <li>Responsive web design</li>
                            <li>Source code/version control</li>
                            <li>UI/UX best practices & design patterns</li>
                            <li>Publish websites to the internet (web servers & object storage)</li>
                        </ul>
                    </div>
                    <div class="bg-white rounded-lg shadow-md p-6">
                        <h3 class="font-bold text-xl mb-3 text-[#457B9D]">Web Based Game Design</h3>
                        <p class="text-sm text-[#4A5568] mb-4">This course is about creating Interactive Webpage Games, a hands-on course designed for aspiring developers and enthusiasts eager to build classic arcade-style games using vanilla JavaScript and HTML5 Canvas! Perfect for beginners with basic HTML, CSS, and JavaScript knowledge, this course guides you through creating five iconic browser-based games—Snake, Pong, Space Shooter, Tetris, and Ink Spill (a Flood It clone)—step by step, covering game loops, collision detection, animations, scoring, and more. With no game engines required, you’ll master practical skills like physics, user input, and array manipulation while building a portfolio of playable games that run in any modern browser.</p>
                        <ul class="list-disc list-inside text-[#4A5568] space-y-2 text-sm">
                            <li>Snake</li>
                            <li>Pong</li>
                            <li>Space Shooter</li>
                            <li>Tetris</li>
                            <li>Ink Spill (Flood It)</li>
                            <li>Game loop & animation basics</li>
                            <li>Collision detection</li>
                            <li>Scoring systems</li>
                            <li>User input & event handling</li>
                            <li>Physics & array manipulation</li>
                            <li>Building a playable game portfolio for browsers</li>
                        </ul>
                    </div>
                    <div class="bg-white rounded-lg shadow-md p-6">
                        <h3 class="font-bold text-xl mb-3 text-[#457B9D]">Linux</h3>
                        <p class="text-sm text-[#4A5568] mb-4">This foundation course introduces the basics of Linux system administration and security.</p>
                        <ul class="list-disc list-inside text-[#4A5568] space-y-2 text-sm">
                            <li>Shell commands and processes</li>
                            <li>Files and directory structure</li>
                            <li>User and group management</li>
                            <li>Networking</li>
                            <li>Shell scripting</li>
                            <li>Vulnerability analysis</li>
                            <li>Intrusion detection</li>
                            <li>Firewall</li>
                            <li>File system encryption</li>
                        </ul>
                    </div>
                    <div class="bg-white rounded-lg shadow-md p-6">
                        <h3 class="font-bold text-xl mb-3 text-[#457B9D]">Introduction to Database Systems</h3>
                        <p class="text-sm text-[#4A5568] mb-4">This course introduces Database Management Systems (DBMS), contrasting them with flat file processing, and covers data abstraction, models, and DML/DDL languages, focusing on relational databases, SQL, and relational algebra (schemas, table keys, operations). Students learn SQL for table creation and queries (joins, aggregation, union), ER modeling with entity sets and relationships (using a university example), database design to avoid redundancy via normalization (BCNF, 3NF), and indexing/hashing (primary/secondary indices, static/dynamic hashing) to optimize data retrieval, enabling them to design and manage efficient database systems.</p>
                    </div>
                </div>
            </section>

            <!-- AP Courses -->
            <section id="ap-courses" class="mb-12">
                <div class="relative text-center mb-6 flow-line">
                    <div class="w-12 h-12 rounded-full inline-flex items-center justify-center text-2xl timeline-icon">📚</div>
                </div>
                <h2 class="text-center text-3xl font-bold text-[#2D3748] mb-4">AP Computer Science Courses</h2>
                <p class="text-center text-md text-[#4A5568] max-w-3xl mx-auto mb-8">Prepare for AP exams with these comprehensive courses covering computer science principles and Java programming fundamentals.</p>
                <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                    <div class="bg-white rounded-lg shadow-md p-6">
                        <h3 class="font-bold text-xl mb-3 text-[#457B9D]">AP Computer Science Principles</h3>
                        <p class="text-sm text-[#4A5568] mb-4">Dive into the exciting world of computing with AP Computer Science Principles, a dynamic course crafted for high school students to explore the foundations of computer science while preparing for the AP CSP exam! This course introduces you to the big ideas of computing through 19 engaging topics, including lists, binary numbers, variables, data compression, the digital divide, the Internet, fault-tolerant systems, crowdsourcing, legal and ethical issues, collaboration, algorithmic efficiency, data abstraction, simulations, program design, data analysis, Boolean expressions, iteration, binary search, procedures, computing impacts, and safe computing practices. Using languages like Python or JavaScript, you’ll tackle hands-on projects such as designing simulations, analyzing datasets, or building collaborative programs, all while developing critical thinking and problem-solving skills.</p>
                    </div>
                    <div class="bg-white rounded-lg shadow-md p-6">
                        <h3 class="font-bold text-xl mb-3 text-[#457B9D]">Introduction to Java Programming (AP Computer Science A)</h3>
                        <p class="text-sm text-[#4A5568] mb-4">This course uses Java to teach essential computer science concepts through hands-on coding, problem-solving, and project-based learning, equipping you with the skills to build robust applications and tackle real-world challenges. Tailored to meet the College Board’s AP CS A curriculum, it covers 17 key topics, including console I/O, strings, variables, expressions, branching, loops, functions, recursion, arrays, object-oriented programming (classes, inheritance, polymorphism), data structures (ArrayList, LinkedList, Map, Set), exception handling, file I/O, GUI development with AWT/Swing, and search/sort algorithms. Perfect for beginners and intermediate coders, you’ll develop a strong foundation in Java programming, logical thinking, and algorithm design, culminating in the ability to create interactive applications and games.</p>
                    </div>
                </div>
            </section>

            <!-- USACO Arena -->
            <section id="usaco-arena" class="mb-12">
                <div class="relative text-center mb-6 flow-line">
                    <div class="w-12 h-12 rounded-full inline-flex items-center justify-center text-2xl timeline-icon">🏆</div>
                </div>
                <h2 class="text-center text-3xl font-bold text-[#2D3748] mb-4">The Competitive Arena: USACO Tiers</h2>
                <p class="text-center text-md text-[#4A5568] max-w-3xl mx-auto mb-8">The USA Computing Olympiad (USACO) is the premier competition for high school programmers. The journey is divided into four tiers, each demanding a deeper understanding of algorithms and data structures, as shown in the skills radar chart.</p>
                <div class="bg-white rounded-lg shadow-md p-6 mb-8">
                    <div class="chart-container h-[400px] md:h-[450px]">
                        <canvas id="usacoSkillsRadar"></canvas>
                    </div>
                </div>
                <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                    <div class="bg-white rounded-lg shadow-md p-6 border-l-4 border-[#A8DADC]">
                        <h3 class="font-bold text-xl mb-3 text-[#1D3557]">USACO Bronze</h3>
                        <p class="text-sm text-[#4A5568] mb-4">Focuses on direct translation of problem statements into code. Implementation skills are paramount.</p>
                        <ul class="list-disc list-inside text-[#4A5568] space-y-2 text-sm">
                            <li>Complete Search / Brute-force</li>
                            <li>Simulation of rules</li>
                            <li>Basic data structures & sorting</li>
                        </ul>
                    </div>
                    <div class="bg-white rounded-lg shadow-md p-6 border-l-4 border-[#457B9D]">
                        <h3 class="font-bold text-xl mb-3 text-[#1D3557]">USACO Silver</h3>
                        <p class="text-sm text-[#4A5568] mb-4">Requires knowledge of standard, efficient algorithms to pass time limits where brute-force fails.</p>
                        <ul class="list-disc list-inside text-[#4A5568] space-y-2 text-sm">
                            <li>Binary Search</li>
                            <li>Greedy Algorithms</li>
                            <li>Graph Traversal (DFS, BFS)</li>
                            <li>Prefix Sums / Two Pointers</li>
                        </ul>
                    </div>
                    <div class="bg-white rounded-lg shadow-md p-6 border-l-4 border-[#1D3557]">
                        <h3 class="font-bold text-xl mb-3 text-[#1D3557]">USACO Gold</h3>
                        <p class="text-sm text-[#4A5568] mb-4">Demands mastery of advanced algorithms and data structures to solve complex, multi-step problems.</p>
                        <ul class="list-disc list-inside text-[#4A5568] space-y-2 text-sm">
                            <li>Dynamic Programming (DP)</li>
                            <li>Advanced Graph Algorithms (Dijkstra's)</li>
                            <li>Union-Find (DSU)</li>
                            <li>Introductory Segment Trees</li>
                        </ul>
                    </div>
                    <div class="bg-white rounded-lg shadow-md p-6 border-l-4 border-[#E63946]">
                        <h3 class="font-bold text-xl mb-3 text-[#1D3557]">USACO Platinum</h3>
                        <p class="text-sm text-[#4A5568] mb-4">The elite level, featuring problems that often require novel insights or modifications of known algorithms.</p>
                        <ul class="list-disc list-inside text-[#4A5568] space-y-2 text-sm">
                            <li>Advanced DP Optimizations</li>
                            <li>Complex Data Structures</li>
                            <li>Network Flow Algorithms</li>
                            <li>Computational Geometry</li>
                        </ul>
                    </div>
                </div>
            </section>

            <!-- AI Research Specialization -->
            <section id="ai-research" class="mb-12">
                <div class="relative text-center mb-6 flow-line">
                    <div class="w-12 h-12 rounded-full inline-flex items-center justify-center text-2xl timeline-icon">🤖</div>
                </div>
                <h2 class="text-center text-3xl font-bold text-[#2D3748] mb-4">AI Research Specialization</h2>
                <p class="text-center text-md text-[#4A5568] max-w-3xl mx-auto mb-8">Advanced AI courses for students who have completed USACO Bronze and advanced to Silver level. These specialized courses prepare students for the USA Artificial Intelligence Olympiad (USAAIO) and focus on cutting-edge AI research and applications.</p>
                <p class="text-center text-xs text-red-600 font-semibold mb-4">(Prerequisite: Completion of USACO Bronze and promotion to Silver level)</p>
                <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                    <div class="bg-white rounded-lg shadow-md p-6">
                        <h3 class="font-bold text-xl mb-3 text-[#1D3557]">Machine Learning</h3>
                        <p class="text-sm text-[#4A5568] mb-4">This course provides a broad introduction to machine learning and statistical pattern recognition. Topics include supervised learning, unsupervised learning, learning theory, reinforcement learning, and adaptive control. Students will examine the purpose of machine learning and how it applies to solving real-world problems. A general overview of machine learning topics, including classification, regression, clustering, and various machine learning algorithms, will be covered. The course will also explore recent applications of machine learning. Students will apply machine learning concepts to practical examples using various AI tools.</p>
                    </div>
                    <div class="bg-white rounded-lg shadow-md p-6">
                        <h3 class="font-bold text-xl mb-3 text-[#1D3557]">Natural Language Processing</h3>
                        <p class="text-sm text-[#4A5568] mb-4">This course provides a comprehensive introduction to Natural Language Processing (NLP), a core area of Artificial Intelligence focused on enabling computers to process, understand, and generate human language, covering fundamental linguistic concepts, statistical methods, and deep learning approaches like RNNs, LSTMs, and Transformers, with hands-on programming assignments using popular NLP libraries to explore topics such as language models, word representations, text preprocessing, feature extraction, part-of-speech tagging, parsing, syntax, information retrieval, text classification, sentiment analysis, opinion mining, sequence models (HMMs, CRFs), pretrained models like BERT and GPT, and applications in machine translation, question answering, and chatbots, equipping students with practical skills to design, implement, and evaluate NLP systems while addressing challenges like ambiguity, bias, and fairness in language technologies.</p>
                    </div>
                    <div class="bg-white rounded-lg shadow-md p-6">
                        <h3 class="font-bold text-xl mb-3 text-[#1D3557]">Computer Vision</h3>
                        <p class="text-sm text-[#4A5568] mb-4">This course offers an in-depth introduction to Computer Vision, a rapidly growing field within Artificial Intelligence that enables machines to interpret, analyze, and understand visual information, combining fundamental principles, mathematical foundations, and state-of-the-art techniques with practical programming using libraries like OpenCV, TensorFlow, and PyTorch to cover topics such as image formation, representation, filtering, feature extraction, segmentation, object detection, recognition, motion analysis, 3D vision, convolutional neural networks (CNNs), transfer learning, and vision transformers for tasks like image classification, object detection, and semantic segmentation, with hands-on projects exploring applications in autonomous vehicles, facial recognition, medical imaging, augmented reality, and video analytics, enabling students to bridge classical and deep learning methods and develop real-world vision systems..</p>
                    </div>
                </div>
            </section>

        </main>
        <section id="contact-us" class="mb-12 text-center">
            <h2 class="text-3xl font-bold text-[#2D3748] mb-4">Contact Us</h2>
            <p class="text-md text-[#4A5568] mb-2">378 Great Neck Rd, Great Neck, NY</p>
            <p class="text-md text-[#4A5568]">Phone: <a href="tel:(929)-728-3344" class="text-blue-600 hover:underline">(929)-728-3344</a></p>
        </section>
    </div>
    <script>
        // Chart.js scripts remain unchanged
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
        const performanceColors = ['#A8DADC', '#E63946'];
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
                    legend: { position: 'top', },
                    title: { display: true, text: 'Conceptual Language Trade-offs' },
                    tooltip: { callbacks: { title: tooltipTitleCallback } }
                }
            }
        });
        const usacoColors = ['#A8DADC', '#457B9D', '#1D3557', '#E63946'];
        const usacoSkillsCtx = document.getElementById('usacoSkillsRadar').getContext('2d');
        const usacoSkillsRadar = new Chart(usacoSkillsCtx, {
            type: 'radar',
            data: {
                labels: processLabels(['Implementation', 'Basic Algorithms', 'Advanced Algorithms & DS', 'Problem Solving Creativity']),
                datasets: [
                    { label: 'Bronze', data: [9, 3, 1, 2], borderColor: usacoColors[0], backgroundColor: 'rgba(168, 218, 220, 0.2)', },
                    { label: 'Silver', data: [7, 8, 3, 5], borderColor: usacoColors[1], backgroundColor: 'rgba(69, 123, 157, 0.2)', },
                    { label: 'Gold', data: [6, 7, 8, 8], borderColor: usacoColors[2], backgroundColor: 'rgba(29, 53, 87, 0.2)', },
                    { label: 'Platinum', data: [5, 6, 9, 10], borderColor: usacoColors[3], backgroundColor: 'rgba(230, 57, 70, 0.2)', }
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
                        pointLabels: { font: { size: 12 } }
                    }
                },
                plugins: {
                    legend: { position: 'top', },
                    title: { display: true, text: 'Skill Requirements by USACO Tier', font: { size: 16 } },
                    tooltip: { callbacks: { title: tooltipTitleCallback } }
                }
            }
        });
    </script>
</body>
</html>
