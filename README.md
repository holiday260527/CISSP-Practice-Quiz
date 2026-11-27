# CISSP-Practice-Quiz
official practice test-version 3


<img width="937" height="499" alt="image" src="https://github.com/user-attachments/assets/ec943ee8-aca6-48b5-9654-9810b6b0dbf5" />


离线与多端

电脑：双击打开即可，不需要联网

手机：把文件用微信/网盘发给自己，在手机浏览器里打开（iOS 用「文件」App → 共享 → 用浏览器打开）

进度：平时存在本机浏览器里；换设备时点右上角 导出 生成一个小 JSON（如 CISSP刷题进度_20261126_1030.json），发到另一台设备后点 导入，作答记录和错题会合并过去。经过实际测试，导出下载、导入合并、刷新后进度都在
---

CISSP Quiz Platform
Delivery Notes & User Guide
1,168 questions · EN / 中文 · Single HTML file · Works offline
2026年11月 
CISSP Quiz Platform	1
Part I · English	2
1. Overview	2
2. Question Bank Composition	2
3. Features	3
4. How to Use — Desktop	4
5. How to Use — Mobile	4
6. Saving and Moving Progress Between Devices	4
7. Data Quality and Verification	5
8. What Is Not Included, and Why	5
9. Frequently Asked Questions	6
10. Sharing This With Others	7
11. Source and Usage Notice	7
Part II · 中文说明	8
一、文档概述	8
二、题库构成	8
三、功能说明	9
四、电脑端使用	9
五、手机端使用	10
六、进度保存与跨设备搬运	10
七、数据质量与校验	10
八、未收录的题目及原因	11
九、常见问题	11
十、分享给他人	11
十一、来源与使用声明	11
Part I · English
1. Overview
This document describes the practice app delivered together with it: a single self-contained HTML file that turns the CISSP Official (ISC)² Practice Tests (3rd Edition) question bank into an offline practice tool.
In one sentence: open one file, answer 1,168 questions, get instant scoring and explanations, and carry your progress between devices with a small backup file.
Item	Detail
Deliverable	CISSP刷题系统_官方练习题库.html (single file, ~0.93 MB)
What it needs	Any modern browser. No installation, no account, no internet
Platform	Windows / macOS desktop, Android and iOS phones
Data inside	1,168 questions with answers and official explanations
Progress	Stored locally in the browser; exportable and importable
2. Question Bank Composition
The source book contains 1,301 questions. 1,168 of them are included here.
Chapter group	Questions
Domain 1 — Security and Risk Management	92
Domain 2 — Asset Security	91
Domain 3 — Security Architecture and Engineering	95
Domain 4 — Communication and Network Security	87
Domain 5 — Identity and Access Management	83
Domain 6 — Security Assessment and Testing	90
Domain 7 — Security Operations	94
Domain 8 — Software Development Security	85
Practice Test 1	107
Practice Test 2	118
Practice Test 3	113
Practice Test 4	113
•	By question type: 1,122 single-choice, 46 multiple-choice.
•	Multiple-choice scoring: all correct options must be selected; partial selections score zero, matching the real exam's "select all that apply" style.
•	99 questions share a scenario passage (e.g. a risk assessment or network design story). The scenario is shown in a collapsible box above the question stem.
•	Every question carries the official answer and the original English explanation; explanations are shown after submission.
3. Features
•	Practice scopes: full bank, any single chapter, single-choice only, multiple-choice only, and a dedicated wrong-answer retry pool (red badge shows the current count).
•	Instant grading: correct options turn green, wrong picks turn red, the correct answer and the explanation expand in place.
•	Statistics: answered / correct / wrong / accuracy, plus per-chapter progress in the sidebar.
•	Result page: accuracy ring, summary counts, and a question grid (green = correct, red = wrong, grey = unanswered). Click any number to jump back to that question.
•	Study aids: shuffled order, auto-advance after a correct answer (1.2 s; manual navigation cancels it), three font sizes, light and dark themes.
•	Keyboard shortcuts (desktop): 1–6 select options, Enter submit, ← / → previous / next.
•	Mobile layout: single column, a sticky bottom bar with Previous / Submit / Next, and a chapter drop-down at the top.
4. How to Use — Desktop
1.	Save the HTML file anywhere on your computer.
2.	Double-click it. It opens in your default browser; no server is required.
3.	Pick a chapter on the left (or use "综合练习（全库）" for the whole bank).
4.	Click an option, then Submit. Read the explanation before moving on.
5.	Switch modes with the buttons above the question: current chapter / single-choice only / multiple-choice only / wrong-answer retry.
Tip: keep the file where you can find it. You can rename it or move it; the question data is inside the file, so nothing else needs to travel with it.
5. How to Use — Mobile
1.	Send the file to your phone (WeChat "File Transfer", a cloud drive, or email).
2.	Save it to a local folder, e.g. iOS Files or Android Downloads.
3.	Open it with a real browser (Safari, Chrome, Edge). On iOS: Files → long-press the file → Share → open in Safari.
4.	Do not open it inside the WeChat in-app viewer; that viewer restricts the page and some features may not work.
The layout adapts automatically: one column, larger tap targets, and a fixed bottom action bar.
6. Saving and Moving Progress Between Devices
Progress is stored by the browser on each device. Nothing is uploaded anywhere.
•	Automatic saving: every answer is saved as you go. Closing the file and reopening it later restores your position and statistics.
•	Export: top-right 导出 button creates a small JSON file, named like CISSP刷题进度_20261126_1030.json.
•	Import: on the other device, click 导入 and select that JSON file. Records are merged; for a question that exists in both, the imported record replaces the local one.
•	Reset: 清空全部进度 wipes answers and the wrong-answer pool on that device (it asks for confirmation first).
Recommended habit: export a backup before switching devices, and again before clearing browser data — clearing website data also clears this progress.
7. Data Quality and Verification
•	The question text, options and answers were extracted from the supplied Word file, then cross-checked question by question against the supplied PDF.
•	1,150 of the 1,168 answers matched the PDF exactly. The remaining 18 discrepancies were inspected individually; all were artifacts of page-break parsing in the PDF (e.g. an answer number captured on the previous page), not real answer differences.
•	The extraction was validated for: complete answer coverage, no missing options, no answer letter outside the option range, and no duplicated option text.
8. What Is Not Included, and Why
133 of the 1,301 source questions are intentionally excluded:
Excluded type	Count	Reason
Figure-dependent questions	112	The images in the Word file are assembled from dozens of floating fragments; extracted images come out broken, so the question would be unanswerable
Matching / drag-and-drop questions	21	They require ordering or pairing items; a single/multiple-choice engine cannot grade them fairly
For those two categories, use the original PDF. Everything else in the bank is complete and self-contained.
9. Frequently Asked Questions
The page is blank when I open the file. You probably opened it with an editor or Word. Right-click → Open with → your browser.
Nothing happens on mobile. Open it from the system file manager with a browser, not inside the WeChat viewer.
My progress disappeared. Browser data was cleared, or a different browser/profile was used. Import your latest backup file to restore it.
Can two people share one file? Yes. Each person's progress is stored in their own browser. Copy the file, and each user starts from zero.
Can I edit the questions? The bank is a BANK array inside the <script> block at the end of the file. It is editable if you are comfortable with JSON, but back up the file first.
Does it work without internet? Yes, completely. No fonts, scripts or images are loaded from anywhere.
10. Sharing This With Others
•	Send the single HTML file. The recipient needs nothing else — no install, no account, no server.
•	Some corporate mail gateways block .html attachments. If that happens, zip the file first or share it via a cloud drive.
•	Renaming the file is harmless; the content is unaffected.
•	Each recipient keeps their own progress; nothing is shared or synced automatically.
11. Source and Usage Notice
Question content originates from (ISC)² CISSP Certified Information Systems Security Professional Official Practice Tests, Third Edition by Mike Chapple and David Seidl, © 2021 John Wiley & Sons, Inc. The app only reorganises that content for personal study purposes; it is not affiliated with or endorsed by (ISC)² or Wiley. Please do not redistribute it commercially.
Part II · 中文说明
一、文档概述
本文档说明随附的刷题应用：一个自包含的 HTML 文件，把《CISSP 官方练习题库（第 3 版）》的题目做成可离线使用的刷题工具。
一句话： 打开一个文件，刷 1168 道题，即时判分并给出官方解析，靠一个小备份文件在设备之间搬进度。
项目	说明
交付文件	CISSP刷题系统_官方练习题库.html（单文件，约 0.93 MB）
运行要求	任意现代浏览器；无需安装、无需账号、无需联网
适用平台	Windows / macOS 电脑，Android 与 iOS 手机
内含数据	1168 道题，含答案与官方解析
进度	保存在本机浏览器，可导出与导入
二、题库构成
原书共 1301 题，本应用收录 1168 题。
分组	题量
域1 安全与风险管理	92
域2 资产安全	91
域3 安全架构与工程	95
域4 通信与网络安全	87
域5 身份与访问管理	83
域6 安全评估与测试	90
域7 安全运营	94
域8 软件开发安全	85
模拟卷 1	107
模拟卷 2	118
模拟卷 3	113
模拟卷 4	113
•	按题型： 单选 1122 道，多选 46 道。
•	多选判分： 必须全部选对才得分，少选或错选均为 0 分，与原考试 "select all that apply" 的口径一致。
•	99 道题带共用场景材料（如风险评估、网络设计情境），场景以折叠框形式显示在题干上方。
•	每道题都带官方答案与英文原版解析，提交后展开显示。
三、功能说明
•	练习范围： 全库、按章节、只练单选、只练多选，以及独立的错题重练池（侧栏红色角标显示当前错题数）。
•	即时判分： 正确项标绿、错选项标红，同时展开正确答案与解析。
•	统计： 已答 / 答对 / 答错 / 正确率，侧栏按章节显示完成度。
•	成绩页： 正确率圆环、汇总数字、题号网格（绿=对、红=错、灰=未答），点数字可直接跳回该题。
•	辅助功能： 随机顺序、答对自动跳下一题（1.2 秒，手动翻页会自动取消）、字号三档、深浅色主题。
•	快捷键（电脑）： 1–6 选项、Enter 提交、← / → 翻题。
•	手机布局： 单列显示，底部固定「上一题 / 提交 / 下一题」，顶部有题库下拉选择。
四、电脑端使用
1.	把 HTML 文件保存到电脑任意位置。
2.	双击打开，会在默认浏览器中运行，不需要启动服务器。
3.	左侧选择章节（或选「综合练习（全库）」做整套题库）。
4.	点选项后点提交，读完解析再进入下一题。
5.	题目上方的按钮可切换：当前题库 / 只练单选 / 只练多选 / 错题重练。
提示：文件可以改名或移动，题目数据都在文件内部，不需要附带其他文件。
五、手机端使用
1.	把文件传到手机（微信「文件传输助手」、网盘或邮件均可）。
2.	保存到本地文件夹，如 iOS 的「文件」或安卓的「下载」。
3.	用系统浏览器打开（Safari、Chrome、Edge）。iOS：文件 App → 长按文件 → 共享 → 用 Safari 打开。
4.	不要在微信内置浏览器里直接预览，那里会限制页面功能，可能无法正常刷题。
页面会自动适配：单列布局、更大的点击区域、底部固定操作栏。
六、进度保存与跨设备搬运
进度保存在各设备自己的浏览器里，不会上传到任何地方。
•	自动保存： 每答一题即写入本机；关闭文件后再次打开，进度与位置都还在。
•	导出： 右上角「导出」生成一个小 JSON 文件，文件名形如 CISSP刷题进度_20261126_1030.json。
•	导入： 在另一台设备点「导入」选择该 JSON，记录会合并；同一道题以导入的记录为准。
•	清空： 「清空全部进度」会删除本机的作答与错题（执行前会二次确认）。
建议习惯：换设备前先导出一次备份；清理浏览器数据前也先导出——清除网站数据会一并清掉这份进度。
七、数据质量与校验
•	题干、选项与答案从你提供的 Word 文件提取，再与提供的 PDF 逐题交叉核对。
•	1168 题中有 1150 题的答案与 PDF 完全一致。 其余 18 处逐一核查，均为 PDF 跨页解析造成的取值错位（例如答案编号被解析到上一页），并非真实答案差异。
•	提取过程做了完整性校验：答案不缺、选项不丢、答案字母不越界、选项无重复文本。
八、未收录的题目及原因
原书 1301 题中有 133 题未收录：
类型	数量	原因
依赖插图的题	112	Word 中的插图由数十个浮动碎片拼合，单独导出会残缺，题目将无法作答
连线 / 拖拽排序题	21	需要排序或配对，选择题判分逻辑无法公平评分
这两类建议直接翻原版 PDF 复习。题库其余部分是完整且自洽的。
九、常见问题
打开是白屏。 可能用编辑器或 Word 打开了。右键 → 打开方式 → 选择浏览器。
手机上点了没反应。 请从文件管理器用浏览器打开，不要在微信内置浏览器里预览。
进度不见了。 浏览器数据被清理，或换了浏览器 / 用户配置。导入最近的备份即可恢复。
同一个文件能给两个人用吗？ 可以。进度各自存在各自浏览器里；复制文件后，每个人从零开始。
能改题目吗？ 题库是文件末尾 <script> 中的 BANK 数组，懂 JSON 就可以改，改前先备份。
完全断网能用吗？ 能。不加载任何在线字体、脚本或图片。
十、分享给他人
•	直接发这一个 HTML 文件即可，对方不需要安装、注册或服务器。
•	部分企业邮箱会拦截 .html 附件，遇到这种情况先压缩成 zip，或走网盘分享。
•	改名不影响使用，内容与文件内部数据无关。
•	每人进度各自独立，不会自动同步或互相干扰。
十一、来源与使用声明
题目内容来自 Mike Chapple、David Seidl 所著《(ISC)² CISSP Certified Information Systems Security Professional Official Practice Tests, Third Edition》，© 2021 John Wiley & Sons, Inc. 本应用仅对该内容做学习用途的重新组织，与 (ISC)² 及 Wiley 无隶属关系，亦未获其背书。请勿用于商业分发。
