# 一阶逻辑：简明导论

## 序言（第一版）

为什么又要出一本逻辑教科书？确实，为什么呢。市面上已经充满了教科书，每一本都声称填补了某个特定的市场需求。奇怪的是，尽管（或者也许正是因为）有大量教科书可供选择，许多逻辑教师却不采用商业教材，选择用讲义来教学。这表明虽然逻辑教科书很多，但优质的逻辑教科书并不多。

逻辑教材可分为两类。一类像S. C. Kleene的《数理逻辑》（纽约：John Wiley and Sons出版社，1967年）和Benson Mates的《基础逻辑》（纽约：牛津大学出版社，1972年），强调逻辑作为一门独特的学科，通过尽可能优雅地阐述该学科所依据的理论来加以解释。另一类则数不胜数，侧重于逻辑的应用，将逻辑视为一种需要掌握、提炼并运用于政治家、社论作者和脱口秀主持人论证中的技能。少数作者提供了一个中间立场，尤其是E. J. Lemmon的《逻辑入门》（最初于1965年出版，1978年由Hackett重印）和Paul Teller的两卷本《现代形式逻辑入门》（新泽西恩格尔伍德克利夫斯：普伦蒂斯霍尔出版社，1989年）。Lemmon和Teller将理论讨论融入鼓励发展逻辑技能的语境中。

在接下来的内容中，我选择了这条中间道路。我专注于翻译和推导的构建，但将其置于更广泛的理论框架之中。本书不要求读者事先接触过形式逻辑或对其有热情。我的目标是尽可能清晰地以小步骤逐步介绍一阶逻辑的基本要素。我试图以一种适合那些在符号领域可能感到不适的学生（和教师）的方式来写作。我对逻辑的方法并非出自一个专业逻辑学家的角度。我认为这使我在理解非逻辑学家和对符号感到恐惧的人觉得困难或不直观的地方时具有某种优势。因此，我比其他作者花更多时间解释基本概念。在我看来，这样的投入从长远来看是会有回报的。

本书涵盖带有同一性的基础一阶逻辑。我没有试图为所介绍系统的可靠性和完备性提供证明。不过，我提供了这些证明所涉及内容的概述。这些内容与系统的语法和语义材料一起，被收录在第2至5章末尾的元逻辑部分中。这些部分可以跳过而不影响连续性。它们被作为更深入课堂讨论的跳板。就我个人而言，我认为在入门课程中加入一些元逻辑内容很重要。元逻辑使那些原本可能显得临时拼凑和随意的材料变得系统化。不那么明显的是，对形式系统的语法、语义和元理论的研究告诉我们一些关于我们自身的东西。在掌握形式系统的过程中，我们要接受一个可以被精确和优雅地描述的领域。因此，任何对我们心理的解释都必须考虑到我们理解和运用具有这些形式特征的系统的能力。

这本书始于1972年夏天。我获得了国家人文基金会的资助，用以撰写一本将逻辑与语言学理论相结合的教材。我认为这是一个案例，两门学科一起学习比单独学习任何一门都更容易、更有效率且更有启发性。该项目最终以影印文本的形式呈现在一代又一代学生面前。接下来的几年里，语言学家们从转换语法出发，经历生成语义学，最终发展到管辖约束理论。与此同时，我对语言学理论的兴趣逐渐减退，对将逻辑与语言学结合成一体的热情也随之消减。与此同时，手稿经过了一系列影印本的版本变迁。尽管每个版本之间的变化微小，累积起来却带来了巨大的差异。

在此过程中，我得到了许多人的帮助。最初的项目灵感来自约翰·科克伦（John Corcoran），我毫不客气地借用了他的许多想法。我同样深深感激戴维·扎雷特（David Zaret），他善意地阅读并就元逻辑部分提供了建议。约瑟夫·德马科（Joseph DeMarco）、罗伯特·金斯伯格（Robert Ginsburg）、凯瑟琳·史密斯（Kathleen Smith）以及两位匿名审稿人阅读了早期版本的全部内容，提出了大量宝贵的意见和建议，这些都改进了最终成品。我的许多学生也提供了建议、修正和意见。我特别感谢苏珊·佩珀斯（Susan Peppers）阅读并评论了最终稿的大部分内容。芭芭拉·汉南（Barbara Hannan）和苏珊·摩尔（Susan Moore）发现了在兰道夫-梅肯女子学院使用的早期版本中的众多错误和不当之处。

安吉拉·柯伦（Angela Curran）和罗伯特·斯塔宾斯（Robert Stubbings）在项目不同阶段为解决技术难题提供了不可或缺的帮助，我将永远铭记皮尔斯·罗林（Piers Rawling）耐心指导我完成量词规则的重新表述。我的院长罗伯特·C·威廉姆斯（Robert C. Williams）慷慨地提供了一台计算机，加里·杰森（Gary Jason）则设计了配套的学习指南。我最大的感激要献给哈里森·哈根·海尔（Harrison Hagan Heil），是他让我认识到将能说清的事情说清楚的重要性。

伯克利，1994年1月

## 序言（第二版）

本书第一版出版后不久就绝版了。出版商琼斯-巴特利特（Jones & Bartlett）将其哲学书目出售给约翰·威利-逊斯（John Wiley & Sons）公司，这本书最终落户到圣智教育（Cengage Learning）。约翰·威利-逊斯和圣智教育都对继续出版本书没有兴趣。因此，我一直在使用PDF版本来教授逻辑课程，最初是在戴维森学院，后来是在圣路易斯的华盛顿大学。

这些PDF文件创建于很久以前，以至于它们已无法编辑。在此期间，我能够进行一些小的修正，但需要进行更广泛的改动，这些改动远不是简单修改PDF文件所能完成的。当我有幸获得黑克特出版公司资深编辑里克·托德亨特（Rick Todhunter）提供的机会出版新版本时，这个问题得到了解决。结果就是您现在手中或屏幕上看到的这本书。

与第一版一样，我特别重视可读性。在你能够向不熟悉某个主题的人解释之前，你并不能真正理解这个主题。就我而言，这意味着首先要让自己理解逻辑，然后将我的理解付诸实践，向学生阐明逻辑的原理。根据我的经验，当你能看到某事物的意义时，学习起来会更容易。考虑到这一点，我试图解释和阐明那些逻辑学家们通常认为理所当然的主题。

第二章中关于条件句的讨论就是一个例子。学生们经常留下这样的印象：逻辑学家使用的条件句的真值条件与我们在日常用语中使用的条件句存在显著差异。但仔细观察就会发现，逻辑学家的条件句在捕捉日常条件句的逻辑核心方面表现得相当准确。

本书首先阐述$\mathcal{L}_{\mathcal{s}}$（命题逻辑），然后介绍$\mathcal{L}_{\mathcal{p}}$（谓词逻辑）。这两种逻辑系统都是自然演绎系统，旨在模拟日常演绎推理。本书与许多入门教材的不同之处在于，它包含了$\mathcal{L}_{\mathcal{s}}$和$\mathcal{L}_{\mathcal{p}}$的语法和语义说明，以及关于可靠性和完备性的讨论。有些教师可能倾向于省略这些内容，但学生们通常会觉得这些内容很有趣，至少在概述层面上是这样。

除了大量的修改之外，我在这一版中还加入了关于前束范式（Prenex Normal Form）的章节，这是另一个学生们觉得有趣且实用的主题。与可靠性和完备性的内容一样，这部分内容也可以省略，而不会影响一阶逻辑基本要素的讲解：即将自然语言转换成$\mathcal{L}_{\mathcal{s}}$和$\mathcal{L}_{\mathcal{p}}$，以及在两种系统中进行推导。

在整个过程中，我一直试图保持这样一个理念：一阶逻辑能够揭示我们日常用语和思维方式的本质。虽然逻辑在许多形式化领域都有重要应用，但我选择强调逻辑与自然语言之间的联系。这种讲解方式特别容易引起初学者的共鸣。

了解我对哲学依赖可能世界理论的反感的读者，可能会对我用可能世界来解释$\mathcal{L}_{\mathcal{s}}$和$\mathcal{L}_{\mathcal{p}}$的语义特征感到惊讶。我这样做有两个原因。首先，对许多学生来说，谈论平行宇宙能够激发他们的想象力，因为这类想法对他们来说完全自然。其次，继续深造哲学的学生不可避免地会遇到大量关于可能世界的引用。在一个相对温和的环境中接触这些术语对这些学生是有益的。

这本书的新版本得益于数百名学习原版的学生提出的问题和建议，也得益于本科生和研究生助教们的帮助，他们在将教材内容传授给本科生方面发挥了极其重要的作用。我从未失去过教授这门学科的热情。我希望这种热情能够通过这本书传达出来。

有些读者可能会想知道我是如何在课堂上使用这本书的。我只教过北美的学生，所以我这里的评论是针对北美模式的。同样，这些评论也适用于面对面教学。现在，我正准备第一次进行远程教学，所以在可预见的未来，我需要调整常规教学方式来适应这个正在逐步形成的后疫情时代新常态。

我发现学生一旦跟不上进度或不积极投入学习就会遇到困难。能够在他人讲解时理解翻译或推导过程是一回事，而能够独立完成句子翻译并从前提推导出结论则是另一回事。学习逻辑与学习任何技能性活动并无不同，成功需要练习和重复。本书中穿插了许多练习题，旨在鼓励学生运用所学知识。我在课堂上讨论这些练习，并让自愿的学生到黑板前（是的，我们学校仍在使用黑板）写出答案。

我不对这些练习作业进行评分，而是将其与在逻辑教学中心进行的简短的五道题测验配合使用，这些测验通常由学生助教监考。（无论是本科生还是研究生助教，均取得了理想的效果。）

逻辑学实验室传统上每周两个晚上开放两小时，具有两个功能。首先，它为学生提供参加测验的场所。其次，它作为辅导咨询点。学生可以来这里，根据自己的需要在参加当周测验前获得课程辅导，然后离开。（由于学生在一周内的不同时间参加测验，我不会在批改后立即发还测验卷，但学生可以随后在逻辑实验室查看他们的作业）这种测验机制可以防止学生落后，并帮助他们了解自己已经掌握和尚未掌握的内容。

除了学期内的十二次测验外，我还安排两次课堂考试和一次累积性期末考试。第一次考试涉及命题逻辑（sentential logic，$\mathcal{L}_{\mathcal{s}}$），这部分内容在第二章和第三章中讲授。第二次考试涉及第四章和第五章的谓词逻辑（predicate logic，$\mathcal{L}_{\mathcal{p}}$）内容。期末考试包括命题逻辑和谓词逻辑，以及在学期最后三节课中介绍的不确定性推理（和"热手现象"）的内容。

并非所有使用这本书教授本科生逻辑的人都会想按我的方式来做。然而，这本书的编写是自成体系的，完全不依赖于逻辑学实验室模式。事实上，我相信即使是逻辑初学者，仅凭这本书也能掌握形式逻辑。这正是我写作本书的目标所在。

墨尔本，2020年7月

## 致谢

在回顾他人对本书提供的诸多更正、建议和指导时，我实在不知从何谈起。第一版序言中已经感谢了在最初项目中不可或缺的一些学生、同事和其他人。此后，许多人以各种方式为本书的后续发展做出了贡献。前面我提到了Hackett出版社的编辑Rick Todhunter，他在出版过程中以极大的耐心指导我。我也要感谢两位匿名审稿人提供的有益批评和建议。

研究助理Derek Braverman、Xiaoyu Ke和Auke Montessori协助我用本书的一个版本进行首次逻辑课程教学。他们在无数次的 Zoom 会议中帮助学生（该课程远程授课，面向分布广泛的学生群体），并在手稿中发现并纠正了大量文字上的不妥之处，包括排版错误及其他问题。如序言所述，我不得不重新录入大量形式逻辑符号，这个过程不可避免地导致了一些失误。研究员Graham Renz和Derek Braverman在审核习题解答过程中，慷慨地帮我找出了其中最严重的错误。我的文字编辑Lori Rider进行了大量修改，并提出了极大改善本书的建议。

多年来的学生们帮助我找到更好的方法来完成本书所要做的事。我特别感谢圣路易斯华盛顿大学2020年秋季逻辑课的85名学生，他们不仅经历了疫情导致的一阶逻辑非同步教学，而且他们的明智、耐心和敏锐的眼光帮助这本书得以完善。感谢Shelly Hykawy和Hykawy家族慷慨允许复制C. B. Martin的画作《一个寻找变元以成为其值的存在》，该画作出现在扉页对面。

最后，我要感谢我的同事Bret Hyde和他的前学生Gus Heil在语言学相关问题上的建议，以及Harrison Hagan Heil，她是在混乱中保持镇定的人，在本《一阶逻辑：简明导论》第二版的每一页都留下了她的印记。

# 1. 引言

## 1.00 逻辑：何乐而不为？

为什么要学习逻辑学？有什么用？逻辑学能带来什么？对这些问题最好的回答是：没有简单的答案。为什么要学习经济学？历史有什么用？生物学能带来什么？学习逻辑学的原因多种多样，从最平凡的——"我需要它来满足学位要求"、"我想轻松拿个B"——到崇高的："逻辑是吸引人的，也很重要，我无法想象没有它的生活"。

逻辑的确让许多人感到天生吸引人，而且它的重要性也再怎么夸张也不为过。幸运的话，在接下来的章节中，这种吸引力和重要性会逐渐显现。但即便逻辑学研究本身没有或几乎没有内在意义，仍然有充分的理由去追求它。

首先，值得注意的是人类具有学习和运用语言的能力。亚里士多德（公元前384-322年）将人类描述为“理性动物”。这种将我们与其他生物区分开的理性，正是与我们所具备的语言能力密不可分的。语言是表达——甚至可以说是形成——思想所必需的，而正是这些思想使得某种协调一致的社会活动成为可能，并赋予了我们生活的意义。你忠实的狗“小斑”似乎也能够对周围发生的事情有所思考——例如，它可以意识到你现在正在前门。但是设想“小斑”现在就在思考你两天后会出现在前门，这有多可信呢？

【对话与思考】 假设在你不在的时候，斑点在周一和周二安静地四处嗅闻，然后在周三在前门附近来回转悠。这是否能让观察小斑行为的人得出结论：在周一和周二，小斑就在想你会在周三回来？或者小斑的行为仅仅表明，在周三时它认为你即将到来？你凭什么认为小斑具有时态化思想，能够思考未来的事，以一句"[你的名字]后天会回来"这样的话来表达呢？

显然，小斑因为没有语言而缺乏表达这种想法的能力。然而，这并不意味着小斑就一定不能产生这种想法。这种说法似乎有道理。但不妨问问自己，你有什么理由将这种想法归于小斑呢？可以说，关于思考者即时环境之外的想法，在某种程度上都依赖于语言背景。关于空间或时间上远离的事物状态的想法，关于抽象实体（例如集合和数字）的想法，而且从表面上看，关于不存在事物（方形的圆、四边三角形）的想法，都需要语言媒介来表达，无论是明显的还是隐含的。

本书的一个目标是让你相信，通过研究逻辑能够洞察自然语言的结构——也就是我们交谈所用的语言。这种语言可能是英语，也可能不是。就此而言，这并不重要。作为研究对象的逻辑形式，体现在所有自然语言底层的抽象形式中。因此，这门学科有望帮助我们洞察语言的特性。鉴于语言在人类事务中的核心地位，逻辑研究可以帮助阐明人类心理。

逻辑史的开端通常被认为始于亚里士多德对论证形式的分类。可以将论证理解为一组有序排列的句子，其中一个句子是结论，由一个或多个前提支持。亚里士多德认识到论证具有一些可重复的模式。这些模式中有些代表有效推理——它们的前提支持或推出其结论——有些则不然。

你稍后将看到如何更准确地描述蕴含的概念。目前，你可以这样理解前提蕴含结论：当前提为相信结论提供理由时，也就是说，如果你接受前提，你就有理由接受结论。亚里士多德专注于简单的三段论推理模式，这种模式通常包含一对前提和一个结论。他认识到哲学家、政治家、科学家和普通人使用的许多论证都可以被理解为这些模式的组合。亚里士多德认为，如果一个论证是有效的，即其前提为结论提供了依据，那么任何具有相同句子模式的论证也必定是有效的。这很好地说明了逻辑的形式特征。除此之外，逻辑还提供了一种研究和分类适用于任何主题的可重复推理形式或模式的方法。

形式逻辑——本书的主题——提供了评估论证有效性和无效性的有力工具。这必然会证明其实用价值，尤其是当你转向考察日常生活中的论证，如社论版面和公共政策辩论中的内容时。在评估关于宇宙和我们在其中地位的理论时，它同样有用。逻辑为展示推理过程的结构提供了框架。当你能够将日常推理转化为标准逻辑形式时，你就规范了这种推理。而在这个过程中，你可能会发现一些你珍视的信念是基于似是而非的推理的——或者它们比你想象的有更好的支持。

一些哲学家认为，你将要接触的基础形式逻辑为追求知识提供了标准化的符号系统。这个想法简单而优雅：任何你能够清晰地说出或思考的关于世界的内容都必须能够用这种特定的表达方式来表达。任何无法如此表达的内容都不能成为真或假的候选者——或者至少不能成为字面意义上的真和假。例如，诗歌和小说虽然不是字面意义上的真实，但对真理具有正当的诉求。

然而，这种思想认为诗歌和小说中产生的真理可以用标准化语言更平实地表达。如果这是对的，那么通过研究逻辑可以学到很多关于我们现实概念结构的东西。即使你对标准化语言的概念持怀疑态度，形式逻辑仍然为我们思考宇宙和我们在其中地位的方式的一个核心方面提供了洞见。

不管逻辑在整体上有什么地位，它与数学和计算机科学都有着深厚的联系。凡是想在这两个领域深造的人都能从对逻辑的理解中受益。其他学科也与形式逻辑有着根本性的联系。量子物理学有时被认为需要一种非标准逻辑来描述量子态。这类说法只有在标准逻辑的背景下才能得到合理的评估。

我至今还没有提到一个广为人知的学习逻辑的理由。通过学习逻辑，你可能期望提高推理能力，从而改善整体认知任务的表现。然而，我并未强调这种所谓的好处，因为我对此持怀疑态度。实证研究对"逻辑训练能提高日常生活中普通推理能力"这一观点提出质疑。形式逻辑，像其他大多数学科一样，难以在不同问题领域之间运用。

以统计学为例。受过统计学训练的人在现实世界中处理不确定性推理任务时，表现通常并不比其他人更好。同样，在逻辑课上获得A的学生在日常推理中仍可能犯错。这个问题不在于逻辑本身，而在于我们的知识割裂倾向。结果就是，我们往往看不到在一个情境中学到的知识在另一个情境中的直接应用。

那么，逻辑在整体推理能力的提升方面就真的毫无帮助吗？这种说法同样值得商榷。你最好调整期望，认识到在学习逻辑时，推理能力的提升（如果有的话）可能是渐进的而非突飞猛进的。不过，在学习逻辑的过程中，你更可能对各类谬误变得敏感。当问题以能够凸显其与形式逻辑领域联系的方式呈现时，你的训练就能发挥作用。

**【典型的三段论推理模式】** 

即：

 所有鲸鱼都是哺乳动物。		 	 所有哲学家都是逻辑学家。

 所有哺乳动物都是温血动物。 	 所有逻辑学家都很聪明。 

------

所有鲸鱼都是温血动物。			   所有哲学家都很聪明。

在这些例子中，横线上面的句子（前提）用来支持横线下面的句子（结论）。这些论证都是有效的：它们的前提导出了结论。有效的论证一定要有真的前提吗？真的结论吗？以下论证又如何？

所有学生都是食肉动物。			所有袋鼠都是有袋类动物。 

所有食肉动物都是有袋类动物。 所有有袋类动物都会跳跃。

------

所有学生都是有袋类动物。 		所有袋鼠都会跳跃。

如果这些论证的前提支持其结论，那么它们就是有效的。这些论证有效吗？

## 1.01 熟能生巧

除了学习逻辑学的各种外在原因之外，你可能会发现这门学科本身既有挑战性又令人满足，甚至令人兴奋。我试图以一种能够吸引你的方式来呈现教材，让你也能体验到这种兴奋感。

学习的成功需要你的配合。掌握形式逻辑意味着要掌握一系列技能。逻辑学不仅包含明确的学科内容，还包括两个方面：一是将自然语言中的句子进行明确而清晰的表达——即将普通句子转换成能揭示其潜在逻辑结构的形式符号；二是构建推导。这两项技能都需要反复练习。就像练习钢琴一样，最初觉得困难甚至陌生的内容，经过时间的积累，终会变得显而易见和熟悉。

本书随处设有练习题，目的是培养你进行翻译和构建推导所需的技能。这些练习题的难度各不相同：大多数很简单，有些较有挑战性，少数会考验你的极限。无论难度如何，练习的关键在于你是否能系统地完成它们。你会发现两种学习方式有着天壤之别：一种是跟随他人的示范来翻译句子或构建推导，另一种是自己独立完成这些工作。要进行翻译和推导构建，光靠识别能力是不够的，而是需要通过练习获得相应的技巧和洞察力。

这种差异与所有需要技巧的活动都有着严格的相似性。你也许能听出一首钢琴曲弹得是否正确，或者看出网球发球动作是否标准。但这并不意味着你就能自己弹奏这首曲子或正确发出网球。要做到这些，你需要不断练习，反复重复动作，直到这些动作变得流畅自然。

用于制定翻译和推导的形式技巧包含重要的感知要素，而不仅仅是认知要素。掌握形式逻辑绝不仅仅是认知或智力上的成就。有人说我们中的一些人，像星际迷航中的斯波克那样，会"逻辑地"思考，而我们其他人（包括作者在内）则以不够逻辑的方式思考。也许有人认为逻辑学家和数学家主要是"左脑型"的，而我们其他人是"右脑型"的。这种看法至少具有误导性，而且很可能是错误的。

在掌握形式逻辑的技巧时，你必须准备重复感知和思维方式，直到它们变得自然而然。为此，重做那些你觉得困难的句子翻译和推导练习，甚至反复练习，都会对你有所帮助。在这个过程中，你可能会觉得自己没有学到什么新东西。从某种意义上说确实如此。就像练习钢琴一样，并非学习新的内容，而是在提升一项技能。翻译和推导也是如此。重复练习可以改进和完善这种相关技能。

你会发现，构建推导所需的各个步骤大多是你在童年时就已掌握的简单操作。在符号中识别模式需要运用感知技能，就像你识别鸟类物种或树木种类时所用的技能一样。比如，你知道如果鸟类都有羽毛，而吸蜜鹦鹉是鸟类，那么就可以推断出吸蜜鹦鹉有羽毛。在逻辑方面取得成功并不需要太多推理上的复杂性。真正的挑战主要在于感知方面。你必须学会在符号组合中发现规律，就像你在说出或思考前面关于吸蜜鹦鹉的句子时听到的那样。一旦你能做到这一点，运用推理策略来构建推导就会变得简单。

让我们设想一个叫亨利的学生，带着《奥杜邦北美树木图鉴》，开始为八年级生物课收集树叶标本。起初，亨利发现通过对比所见的树叶与图鉴中的图片和描述来识别树叶是困难的，甚至是不可能的。图鉴上展示着一片榆树叶的图片。亨利正在查看的这片叶子是否与图片相符？确实，在某些方面是相符的。不过，这片叶子有一个缺口，而图片上的叶子却没有。这个缺口是昆虫造成的损伤，还是天然的？如果是天然的，这对榆树叶来说是不是不典型的特征？或者榆树叶在这种缺口方面可能有变化吗？

经过反复练习，亨利终将掌握识别榆树叶的诀窍。他的成功取决于他能够领会什么是判断一片叶子是否为榆树叶的相关特征，什么是无关特征。这种窍门是亨利难以用语言表达的。（想象一下，试图通过电话向一个从未见过树叶的人解释如何识别某个树叶品种。）

在这方面，亨利所获得的知觉技能类似于你在学习走路、系蝴蝶结、骑自行车或滑雪时掌握的运动技能。你通过实践来学习这些技能，一开始跌跌撞撞，然后随着练习变得更加流畅，最终可以自动完成。起初，你会运用一些简单的经验法则：转弯时，要把重心放在下坡的滑雪板上。后来，你就只是在滑雪。这些运动动作已经形成了无需刻意控制就能自动运行的程序。

翻译和推导的构建也是如此。最初困难的事情通过练习变得流畅。练习是必不可少且无法避免的。有些读者可能已经起步较早。你可能倾向于认为这些人比其他人更聪明或更"有逻辑性"。然而，这些能力与其说是智力的，不如说是知觉的，与其说是思考的问题，不如说是熟练辨识模式的问题。如果模式识别是右脑的功能，那么令人意外的是，成功掌握逻辑所需的技能是右脑技能。

练习和重复使你能够将有意识的过程自动化，这是掌握任何学科的重要组成部分。另一个相辅相成的过程，即将你已经不自觉完成的事情带入意识层面的过程，同样重要。

在说话和理解语言时，你会运用各种语法和词义运用能力。（简单来说，句法是指句子的语法结构，而语义则是指其含义。）当你着手将特定的英语句子转换为形式符号时，你必须首先向自己明确原句的语义。只有这样，你才能确信你找到了一个合理的形式对应物。然而，你的语义知识，就像你对走路、系鞋带和滑雪的知识一样，在很大程度上是隐性的：是程序性知识，而非陈述性知识。你拥有这些知识，但它们并不容易被提取和明确化。

在掌握逻辑的过程中，你被迫将你在说话和理解中不经意依赖的隐性语言知识转化为对原则的明确认识。最终，你会加深对自己和他人语言运用的理解。

## 1.02 $\mathcal{L}_{\mathcal{s}}$和$\mathcal{L}_{\mathcal{p}}$

本书介绍两个形式系统，即两种语言：$\mathcal{L}_{\mathcal{s}}$和$\mathcal{L}_{\mathcal{p}}$。$\mathcal{L}_{\mathcal{s}}$是一个简单的命题逻辑，其系统元素包括"原子命题"和允许构建复合命题的连接词。原子命题类似于简单的英语句子："袋鼠是有袋类动物"、"袋鼠会跳跃"。复合命题可以由这些命题和连接词"和"组成："袋鼠是有袋类动物并且袋鼠会跳跃"，或者用更口语化的说法："袋鼠是有袋类动物且会跳跃"。

相比之下，$\mathcal{L}_{\mathcal{p}}$是一种谓词逻辑，其句子展现出内部的基本成分结构。由于像$\mathcal{L}_{\mathcal{s}}$这样的命题逻辑比谓词逻辑更简单，将首先介绍$\mathcal{L}_{\mathcal{s}}$，为研究本书的主要目标$\mathcal{L}_{\mathcal{p}}$铺平道路。

在整个学习过程中，你应当牢记感知能力的重要性，正如我一直强调的，这对掌握所讨论的材料至关重要。你还应该记住，明确你在某种意义上已经掌握的关于你所说语言的知识也很重要。在此基础上，你就能发现像$\mathcal{L}_{\mathcal{s}}$和$\mathcal{L}_{\mathcal{p}}$这样的形式系统所展现出的简约之美，以及它们作为思想和意义表达媒介的优势与局限性。

# 2. $\mathcal{L}_{\mathcal{s}}$语言

## 2.00 形式语言

本章展示了一种简单的形式语言$\mathcal{L}_{\mathcal{s}}$。尽管与自然语言（英语、德语、乌尔都语）相比，$\mathcal{L}_{\mathcal{s}}$确实很简单，但它展现了每种语言都具有的各种有趣的逻辑特征。你将首先了解$\mathcal{L}_{\mathcal{s}}$的语法和语义，然后在下一章中了解其推导结构。在整个讨论过程中，将把$\mathcal{L}_{\mathcal{s}}$的特征与英语中的特征进行比较。实际上，通过研究这种简化的人造语言，你可以学到很多关于熟悉的自然语言的逻辑特征。

与任何语言一样，$\mathcal{L}_{\mathcal{s}}$包含了用于构建句子的基本词汇。句子可以任意复杂，只要其复杂度保持有限即可。$\mathcal{L}_{\mathcal{s}}$中没有最长的句子，但$\mathcal{L}_{\mathcal{s}}$中的句子（或英语的句子）不能无限长。$\mathcal{L}_{\mathcal{s}}$的句子，如同其自然语言对应物一样，由有限序列的元素组成：句子是有限可构造的。这些要点的重要性将在阐述$\mathcal{L}_{\mathcal{s}}$的语法时变得清晰（§2.20）。

诚然，普通人会对过于复杂或超过一定长度的句子感到困惑。（你可以通过阅读露西·埃尔曼的千页小说《鸭子，纽伯里港》（Ducks, Newburyport）[Bloomsbury出版社]来测试自己，这本书的大部分内容由一个句子组成。）然而，这些问题属于心理学家的研究领域；它们并不影响我们对语言的描述。

数学家们感兴趣的是定义和探索数学系统的特征，但这些系统的用途以及人类在处理它们时可能遇到的认知困难本身并不是数学家关心的问题。这一点同样适用于致力于描述$\mathcal{L}_{\mathcal{s}}$的逻辑学家，或对描述韩语感兴趣的语言学家。在每种情况下，目标都是描述一个抽象对象，即语言。语言学是一回事，心理语言学则完全是另一回事。

## 2.01 语句常项与变项

英语句子由有限的、非空词序列按特定顺序排列组成。每个句子至少由一个词组成，如前所述，没有句子包含无限数量的词。相比之下，$\mathcal{L}_{\mathcal{s}}$语句的基本成分不是词，而是本身作为语句的元素。这些元素，即语句常项，用熟悉的大写字母$A、B、C……Z$来表示。$\mathcal{L}_{\mathcal{s}}$中的语句常项的功能类似于英语中的简单陈述句。它们可以单独出现，也可以与其他语句常项一起构成复合语句。

一个简单的原子语句$S$在$\mathcal{L}_{\mathcal{s}}$中可能扮演类似英语句子「苏格拉底是智慧的」的角色。这两种语句都可以用来表达一个简单命题。$\mathcal{L}_{\mathcal{s}}$语句与其英语对应语句一样，可以与其他简单语句结合来产生表达复杂命题的语句（具体方式将在后文讨论）。

$\mathcal{L}_{\mathcal{s}}$的元素，就像自然语言中的元素一样，并不具有内置含义。我们决定一个给定元素的含义，决定如何解释它。在自然语言中，这种决定可能是有意识和刻意的，比如当科学家创造一个术语来指代新发现的粒子时；也可能是约定俗成的结果。在学习语言时，我们与其他使用该语言的人达成一种隐含的约定，这种约定使我们能够以可靠传达我们意图的方式使用词语。

形式语言具有非常不同的功能。在命题逻辑中，$\mathcal{L}_{\mathcal{s}}$使我们能够明确自然语言中复杂语句的逻辑结构以及语句之间的逻辑关系。因此，可以大幅简化$\mathcal{L}_{\mathcal{s}}$的元素。任何$\mathcal{L}_{\mathcal{s}}$语句都可以由少量简单元素构建，因为我们可以在不同场合对这些简单元素作出不同解释。（通过引入下标可以补充$\mathcal{L}_{\mathcal{s}}$的基本词汇：$A_1…A_2…A_3…A_{519}…$，但这是一个此处无需关注的复杂问题；参见§4.14。）因此，在某一场合你可能使用$\mathcal{L}_{\mathcal{s}}$表达式$S$来表示

苏格拉底是智慧的。

在另一场合，你可能用同一个符号$S$来表示

苏格拉底是快乐的。

通过选择与相应英语语句有联想关系的字母，我们可以使彼此的工作更容易。在上述例子中，S被用来分别表达英语语句「苏格拉底是智慧的」和「苏格拉底是快乐的」所表达的命题。我们也可以用W和H，或者用R和L。字母的选择不是由逻辑约束，而是由常识约束：以便于你记忆和他人理解的方式翻译语句。然而，你不能在同一个复合语句中使用同一个字母来代表两个不同的语句。

假设你要在$\mathcal{L}_{\mathcal{s}}$中表示相当于英语语句

苏格拉底是智慧的且苏格拉底是快乐的。

你不能用一个$S$来表示两个简单构成语句——「苏格拉底是智慧的」和「苏格拉底是快乐的」。相反，你必须使用不同的字母，例如$W$和$H$。

有时我们需要以一般方式谈论$\mathcal{L}_{\mathcal{s}}$中的语句。例如，我们可能想讨论语句的类型或语句结构，而不局限于特定语句。面对类似需求时，数学家会求助于变项。例如，在解释乘法运算时，我可以给出以下描述：

如果$x$和$y$是整数，它们的乘积等于$y$个$x$相加。

在这里，$x$和$y$作为变量可以代表任意数字。在讨论$\mathcal{L}_{\mathcal{s}}$时，我们使用句子变量来表示任意的$\mathcal{L}_{\mathcal{s}}$句子。句子变量由小写字母$p、q、r、s、t$组成。例如，句子变量p可以用来代表你选择的任何$\mathcal{L}_{\mathcal{s}}$句子。引入变量不仅仅是为了方便。没有它们，就无法以适当的普遍方式描述$\mathcal{L}_{\mathcal{s}}$及其特征。但是，变量不能被误认为是句子。正如x和y不是数字一样，p和q也不是$\mathcal{L}_{\mathcal{s}}$的句子。也就是说，$\mathcal{L}_{\mathcal{s}}$中的句子只包含大写字母。

**【句子与命题】**

在这里，哲学家通常说句子表达命题。句子因语言而异，相比之下，命题则被认为具有一种超越语言的意义。

举例来说，不同的句子可以用来表达相同的命题：英语句子「Snow is white」表达的命题与法语句子「La neige est blanche」表达的命题相同。同样地，同一个句子在不同场合可以用来表达不同的命题：英语句子「They are flying planes」可以用来表达两个不同的命题。你能看出它们是什么吗？

尽管在讨论语言时引用命题概念确实很方便——例如，你可以说当两种语言中的句子都用来表达同一个命题时，一种语言中的句子可以翻译成另一种语言中的句子——但你应该记住，哲学家们对于命题是什么，甚至是否存在这样的实体，尚未达成共识。

练习2.01 请将以下英语句子翻译成$\mathcal{L}_{\mathcal{s}}$符号：

1. 苏格拉底勇敢。
2. 苏格拉底爱赞西佩。
3. 赞西佩爱苏格拉底。
4. 敏捷的棕色狐狸跳过懒惰的狗（此句为经典打字练习句）。
5. Every good boy does fine.（此为音乐五线谱记忆口诀，对应EGBDF）。

## 2.02 真值联结词

英语和其他自然语言的丰富性源于它们能够用有限的词汇产生无限的句子。掌握一门语言就在于精通产生和理解属于这个无限句子库的句子的方法。生成句子的一种基本方法是将简单句子组合成复合句。你可以把"苏格拉底很智慧"和"苏格拉底很快乐"这两个句子连接起来，形成复合句：

苏格拉底很智慧，并且苏格拉底很快乐。

在将简单句组合成复合句的过程当中，我们经常以掩盖其结构的方式修改原句。因此，虽然你可以将"苏格拉底很智慧"和"苏格拉底很快乐"这两个句子组合成上面的句子，但我们更可能会说成：

苏格拉底，这个智慧的人，很快乐。

或者更有可能说成：

苏格拉底既智慧又快乐。

在第一个例子中，"苏格拉底很智慧"这个句子被转换成定语从句"这个智慧的人"，并嵌入到"苏格拉底很快乐"这个句子中。在第二个例子中，两个句子中重复出现的成分被省略了。这些及其他类似的语言现象在自然语言中都很常见。

在使用英语的过程中，人们会将简单句组合成更大、信息量更丰富的句子。这一点对$\mathcal{L}_{\mathcal{s}}$也同样适用。但是，两者之间存在重要差异。首先，如上述例子所示，由简单英语句子构建的英语句子通常包含对原始简单句子的修改。一个句子与另一个句子结合时，可能会被转换成从句，或者重复的成分会被省略。而在$\mathcal{L}_{\mathcal{s}}$中，简单句子保持其独立性。这是形式语言（如$\mathcal{L}_{\mathcal{s}}$）能够揭示自然语言中隐含或潜在的逻辑结构的原因之一。

$\mathcal{L}_{\mathcal{s}}$和英语之间的第二个差异在于，$\mathcal{L}_{\mathcal{s}}$中允许句子组合的机制比自然语言典型的组合机制更为受限。在本章中，你将了解到五种真值函数句子连接词（英文也称为逻辑连接词、逻辑常量或逻辑算子）。这些连接词用于将简单的$\mathcal{L}_{\mathcal{s}}$句子连接在一起，形成更复杂的句子。与自然语言中的对应词不同，而真值函数连接词不会影响它们所连接的句子的结构。复杂的$\mathcal{L}_{\mathcal{s}}$句子显然是由简单$\mathcal{L}_{\mathcal{s}}$句子构成的复合体。

反映了$\mathcal{L}_{\mathcal{s}}$语言的这一特征，简单的$\mathcal{L}_{\mathcal{s}}$句子被称为原子句（基本句），并与分子句（复合句）相区别。自然界中的分子是由原子作为部分构成的；在构成分子时，原子保持其原有特性。同样地，$\mathcal{L}_{\mathcal{s}}$中的分子句是由保持其句子特性的原子构成的。不难发现，自然语言在这方面存在着重要的差异。在构建复杂句子时，我们通常会改变其简单组成部分的结构，以致难以辨认。英语的这一特征是我们每个人都经常不假思索地使用的，这在把英语译成$\mathcal{L}_{\mathcal{s}}$时可能会带来困难。因此，在构建翻译时，为找到与某个英语句子相对应的$\mathcal{L}_{\mathcal{s}}$句子，你往往需要恢复那些已经变得不明显的信息。

## 2.03 否定：¬
符号¬在逻辑句子系统Ls中表示否定。通过在Ls句子前添加¬符号，你可以否定它。这与在中文句子前添加"并非"来否定句子的方式相似。假设你用Ls句子W来表示：

苏格拉底是智慧的。

那么句子¬W则表示：

并非苏格拉底是智慧的。

或者用更口语化的说法：

苏格拉底并不是智慧的

同样，假设你给H赋予含义：

苏格拉底是快乐的。

在这种情况下，它的否定¬H则表示：

并非苏格拉底是快乐的。

也就是说：

苏格拉底并不是快乐的。

**【真值函数联结词（Truth-Functional Connectives）】**

 $\mathcal{L}_{\mathcal{s}}$使用五种真值函数联结词： 

| $\neg$  否定（并非...）                   |
| :-------------------------------------------- |
| $\land$  合取（...并且...）         |
| $\lor$ 析取（...或...）                 |
| $\supset$ 条件（如果...那么...；仅当...） |
| $\equiv$ 双条件（...当且仅当...）             |

否定是将要介绍的五个句子真值联结词中的第一个。通过将¬的运算与汉语中的"事实并非如此.…"进行比较，你可以对其意义获得一个直观的理解。这种意义可以通过真值表来精确地说明。

Ls中句子的真值只能取这两个中的一个：真（T）或假（F）。真值表展示了联结词如何影响它所在的句子的真值。下表呈现的是否定联结词：

| $p$  | $\neg$p |
| ---- | ------- |
| T    | F       |
| F    | T       |

请注意，该表使用了命题变项p，而不是某个特定的句子。这在一定程度上对这个定义赋予了其原本没有的概括性。真值表表明，对于任何Ls句子p，如果p为真，则¬p为假；如果p为假，则¬p为真。那么，否定则是颠倒它所连接的句子的真值。在这方面，Ls中的否定类似于汉语中的否定。如果句子"苏格拉底是智慧的"为真，那么"并非苏格拉底是智慧的”这个句子为假，（或"苏格拉底不是智慧的"为假）；如果原句为假，其否定则为真。

Ls是一种真值函数语：Ls中每个句子的真值都是其成分句（constituent sentences）的真值所决定的函数。在实践中，这意味着，就给定的任意Ls句子p，如果你知道（i）其成分句（constituent sentences）的真值，和（ii）真值函数联结词的定义，你就能准确地确定该句子的真值（即判断其真假）。如果你知道句子A为假，那么（根据上述定义）你就知道¬A为真，以此类推。

## 2.04 合取：∧
第二个真值联结词表示合取运算，在Ls中用倒楔形符号∧表示。与否定一样，Ls中的合取也反映了汉语中的合取。如果在两个句子之间放置∧，结果就是一个新的复合句。因此，从W和H出发，你可以构造合取句W∧H。在汉语中，合取句

苏格拉底是智慧的且苏格拉底是快乐的。

是通过用"且"来连接"苏格拉底是智慧的"和"苏格拉底是快乐的"这两个句子而形成的。你可以自由地将否定句与非否定句或其他否定句组合，形成更复杂的合取式：

¬W ∧ H
W ∧ ¬H
¬W ∧ ¬H

这些都是完全可接受的句子，就像由两个以上原子语句构建的句子一样：

(¬W ∧ ¬H) ∧ A
(W ∧ ¬H) ∧ (A ∧ B)

一般来说，你可以组合任意有限长度的合取句。在每种情况下，最终得到的句子的真值都将是其成分句（constituent sentences）真值的函数。

∧的真值表呈现如下所示：

p q    p ∧ q 
T T       T
T F       F
F T       F
F F       F

这个真值表比用于呈现否定的真值表更复杂。在否定运算中，目标是要明确对单个句子进行否定的作用：对任何句子的否定的结果都是使该句子的真值反转一一从真变为假，或从假变为真。这只需要单个命题变项。该变项所涉及的句子的所有可能的真值都可以用表格中的两行来表示：一个附加否定符号的句子可以为真或为假。

由于联结词用于连接成对的句子，因此，∧的真值表呈现需要额外的行，用来表示被连在一起的句子其真值所有可能的组合。

∧符号两边的句子称为合取项。每使用一次∧都涉及一对合取项。因此，我们需要考虑四种可能的真值组合：（一）可能两个合取项都为真；（二）可能第一个为真，第二个为假；（三）可能第一个为假，第二个为真；（四）可能两个合取项都为假。

∧ 的真值表显示了在给定了这些组合中每一个合取项的真值时，得到的整个合取式的真值结果。合取式只有在其两个合取项都为真时才为真（这种情况体现在表格的第一行）。在其他所有情况下，所得到的合取式都为假——正如其余各行所示。

逻辑语言Ls中的连接特征与英语中的连接相对应。一般来说，当英语句子用"and"连接时，只有在其成分句（即其合取项）都为真时所得到的复合句才为真，否则为假。“苏格拉底是智慧的且快乐的。”这个句子，当且仅当“苏格拉底是智慧的”和“苏格拉底是快乐的”这两个句子都为真时，才为真。（需要注意，上述汉语句子是“苏格拉底是智慧的且苏格拉底是快乐的”的一种文体变体。）

【真值函数】

Ls是一种真值函数语言。在这种语言中，每个句子都是一个函数，其真值完全由其成分句（constituent sentences）的真值决定。如果你知道简单句子的真值，就可以确定包含这些简单句子的任何复杂句子的真值。

Ls中的联结词（¬，∧，∨，⊃，≡）都是真值函数联结词。这意味着它们的定义是由它们对其所在的句子所起的作用而决定的。

把¬p或p∧q理解为函数——真值函数——正如x2是一个数学函数一样。

真值表类似于函数表，以表格形式展示某个特定函数的运算过程。例如，平方函数可以用下表表示：

x   x2 
0   0 
1   1 
2   4 
3   9 
4   16 
5   25 
⫶    ⫶

表格左侧的值代表函数的定义域；右侧的值代表函数的值域。函数提供从定义域到值域的映射：将一个集合的元素映射到另一个集合的元素。其中，正整数集合中的元素与该集合中的元素相关联。真值表则是将真值映射到真值。

## 2.05 句法标点
在进一步探讨Ls的奥秘之前，我邀请您简要思考一下符号的歧义问题。假设要求您计算下列算式的值：

2 + 3 x 5

在没有额外信息的情况下，这个算式具有二义性，也就是说，它可能表示：

(2加3)再乘以5 (= 25)

或者表示：

2加上(3乘5)的积 (= 17)

这种由对原始算式解读方式不同导致的结果上的差异，说明了为什么数学家必须避免歧义。

为了避免歧义，你可以采用各种符号惯例。例如，你可以规定始终按从左到右的顺序执行运算。如果遵循这个惯例，上面的算式将按第一种方式解释。或者，你可以采用一种括号表示法来强制某种解读：

(2 + 3) x 5
或
2 + (3 x 5)

这个规则（如果要正式表述的话）是：括号内的表达式应替换为其计算结果。因此，(2 + 3)将被替换为5，(3 x 5)将被替换为15。

对于Ls来说，将采用类似的技术。考虑这个句子：
¬P ∧ Q

这个表达式是否应该理解为P的否定¬P与Q的合取？还是P∧Q这个合取式的否定？为了减少混淆，Ls采用了一个惯例，即用括号来明确否定符号和其他运算符的运算作用域。因此，合取
P ∧ Q
的否定将写作：
¬(P ∧ Q)
相反，如果你想让否定符号仅作用于句子的第一个合取项，你只需去掉括号：
¬P ∧ Q
以上内容可以总结为一个简单的规则：否定符号就只适用于紧随其后的表达式。请看以下句子：

¬(P ∧  Q) ∧ R
¬((P ∧  Q) ∧ R）
P ∧ (Q ∧ ¬ R)

在第一个表达式中，否定符号的范围包括联结式(P∧Q)，但不包括右侧的联结项R。而在第二个表达式中，整个复合表达式都被否定。在最后一个表达式中，否定符号的范围仅包括最右边的联结项R。

练习2.05
使用¬和∧联结词将以下汉语句子翻译成Ls。

令E = 埃尔维斯唱歌；F = 芬顿调查；G = 乔治逃跑；H = 荷马逃跑。

1. 乔治和荷马逃跑。
2. 荷马逃跑且乔治逃跑。
3. 芬顿调查且荷马不逃跑。
4. 并非芬顿调查且荷马不逃跑。
5. 芬顿调查且埃尔维斯唱歌且乔治逃跑。
6. 并非乔治和荷马逃跑。
7. 荷马和乔治逃跑，且芬顿不调查。
8. 荷马和乔治不逃跑。
9. 芬顿不调查，且乔治和荷马不逃跑。
10. 并非荷马和乔治逃跑且芬顿不调查。

## 2.06 析取符号：∨
第三种真值函数联结词表示析取，用楔形符号∨表示。在英语中，析取最常见的表达方式是"either...or..."，在中文中相当于"……或…”，例如下面这个句子：

在下雨，或，阳光明媚。

Ls中的析取与其英语对应词在某些重要方面有所不同。通过真值表的表示，这些差异就变得清晰可见：

p q   p∨q
T T    T 
T F    T 
F T    T 
F F    F

根据真值表所示，在逻辑系统Ls中，析取式（"或"的逻辑表达）只有在其组成分句（即析取项）都为假时才为假；其他情况下都为真。

真值表中的第二行、第三行和第四行与我们对汉语中"或"的理解很好地吻合。假设我说出上述析取式“在下雨，或，阳光明媚”。如果其中一种情况为真，你会认为这句话为真：如果在下雨但没有阳光（这种情况对应真值表的第二行），或者阳光明媚但没下雨（对应第三行）。同样，如果既不阳光明媚也没下雨（对应真值表的第四行），你会认为这句话为假。

要将真值表第一行与中文的日常用法对应起来比较困难。根据第一行，如果析取式的两个析取项都为真，则整个析取式为真。这似乎与汉语的日常用法不太相符。比如，如果我对你说：

“Iola会在周一或周二到达。”

你会期望在周一或周二见到Iola，而不会认为她在这两天都会“到达”。这可能是汉语中理解"...或…."结构最常见的方式。

如果我们要详细说明使用上述句子时的真实含义，我们可能会这样表述：
“Iola会在周一或周二到达，但不会在这两天都到达。”

这种结构表达的是不相容析取式：“A为真，或，B为真，但A、B不能同时为真”。从真值表可以看出，在Ls中，如果两个析取项都为真，析取式也为真———也就是说“A为真，或，B为真，并且A、B可以同时为真”。虽然这种结构（相容析取）在汉语中出现的频率低于不相容析取，但确实存在。考虑这个句子：

“员工在周末或节假日工作将获得1.5倍工资。”这种句子可能会出现在劳动合同条款中。它的意思是说，在正常工作时间以外工作的情况下，员工将获得额外报酬：在周末、节假日，或同时属于这两者的情况。假设上周六恰逢元旦，而你加班了数个小时。如果你的雇主坚持以不相容析取的方式解读上述条款，声称上周六既是周末又是节假日，被排除在应付1.5倍工资的情况之外。若你的雇主以此为由拒绝按照1.5倍支付你的劳动报酬，你一定不会给他好脸色看的。

【有歧义的句子】
前面练习中的一些句子存在歧义，它们可能有两种以上不同的含义，因此可以有多种解读版本。请指出哪些句子存在歧义。请注意在选择不同含义时，是否需要采用不同的Ls翻译方式。

要表达一般意义上的析取，重要的是要区分不相容析取（“A为真，或，B为真，但A、B不能同时为真”）和相容析取（“A为真，或，B为真，并且A、B可以同时为真”）。你可能会觉得逻辑学家选择在Ls中用相容方式定义析取很奇怪，但原因很简单：使用析取符号∨来表示相容析取，你可以同时实现两种目的。通过巧妙构造，你就能构建出既表达不相容析取又表达相容析取的句子。

假设Ls句子W用来表达"苏格拉底是智慧的"，H表达"苏格拉底是快乐的"，B表达"苏格拉底是无聊的"。有了这些解释，再加上我们对真值函数联结词（¬、∧和∨）的理解，你就能产生无数复杂的Ls句子。考虑以下例子及其中文对应：

(W ∧ B) ∨ H
苏格拉底是智慧的且无聊的，或者苏格拉底是快乐的。

(¬W ∨ B) ∧ ¬ H
苏格拉底不是智慧的或他是无聊的，并且他是不快乐的。

¬W ∨ ¬H
苏格拉底不是智慧的，或者，他不是快乐的。

只要你理解第三个句子保留了苏格拉底既不智慧又不快乐的可能性，这些翻译就很直观。

观察上述句子就能发现在Ls中表示不相容析取的简单方法。让我们再看这个句子：

Iola将在周一或周二到达。

如前所述，这个句子最自然的用法是表达Iola将在周一或周二到达，但不会两天都到达。让我们将这个表述分解为几部分。首先，这个句子表明Iola将在周一或周二到达而不是，比如说，在周五。这可以表示如下：

M ∨ T

这个汉语句子还暗示Iola不会在周一和周二都到达。（这一点可从背景信息中推知——例如，到达发生在拜访开始时，而Iola的拜访如果在周一开始就不能在周二开始，反之亦然。）句子的这层含义可以在Ls中通过否定联结词来表达：

¬(M ∧ T)

这个否定合取式断言lola不会在周一和周二都到达，或者更口语化地说，不会同时在这两天到达。否定符号的范围包括整个合取式。

合取式的否定与否定式的合取有重要区别（否定符号不能"分配"）。上面的Ls句子与下面这句表达的含义完全不同：

¬M ∧ ¬T

这个逻辑句子的意思是lola既不会在周一到达也不会在周二到达，也就是说她不会在这两天中任何一天到达。毫无疑问，这个句子与我们最初的析取式"lola会在周一或周二到达"是不一致的，也与句子

M ∨ T

也是不一致的，后者至少表达了原句的一个成分。如果两个析取项都为假，则析取式不可能为真。
现在应该清楚了，原始句子在Ls中的不相容析取含义可以通过逻辑句子的合取式来表示：

M ∨ T
引入了原句中"...或..."的一个成分，以及

¬(M ∧ T)
引入了"不能同时为真"的一个成分。当这两部分合取在一起时，就变成了：

(M ∨ T) ∧ ¬(M ∧ T)
这个复杂表达式的第一个合取项表达了句子的析取层面，而第二个合取项表达了其不相容层面。

在实践中，将汉语析取式翻译成Ls句子时，你可以采用以下原则：将析取式译为相容析取（即仅使用∨），除非这些句子只能被理解为不相容析取。即便一个句子既可理解为相容析取也可理解为不相容析取，也应该仅用∨来翻译。

【Ls语言中的歧义】
Ls语言使用常见的数学惯例，即用括号来消除句子的歧义。（当一个有歧义句子的本意被明确时，它的歧义就被消除了。）表达式

A ∨ B ∧ C

存在歧义，可解释为：
(A ∨ B) ∧ C
和
A ∨ (B ∧ C)
Ls语言不允许含有歧义的句子，因此第一个表达式不是Ls的合法句子。通过按照上述两种方式之一添加括号，它可以变成合法句子。这两个句子的含义相同吗？

练习2.06
使用¬（否定）、∧（合取）和∨（析取）联结词，将以下汉语句子翻译成Ls。
设E = 埃尔维斯唱歌；F = 芬顿调查；G = 乔治逃跑；H = 荷马逃跑。

1. 埃尔维斯唱歌且荷马逃跑。
2. 荷马逃跑或乔治没有逃跑。
3. 芬顿调查，且要么荷马没有逃跑要么乔治逃跑。
4. 并非芬顿调查或荷马没有逃跑。
5. 要么芬顿没有调查，要么荷马没有逃跑。
6. 荷马或乔治其中一人逃跑，但非两者。
7. 埃尔维斯唱歌且荷马和乔治逃跑，或者芬顿没有调查。
8. 荷马或乔治没有逃跑。
9. 芬顿没有调查或埃尔维斯没有唱歌，但不会同时发生。
10. 要么埃尔维斯唱歌，要么乔治或荷马逃跑。
