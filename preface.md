# 你不知道的JavaScript
# 前言

我相信你注意到，但是这系列丛书标题中的“JS”并不是一个用来诅咒JavaScript的缩写词，尽管我们可能经常咒骂这门语言的奇怪特性。

在互联网发展的早期，JavaScript就已经成为了支撑网页内容交互体验的基础技术。那时JavaScript的作用可能仅仅是生成一些闪烁的鼠标轨迹或者烦人的弹出窗口，但是经过了大约20年的发展，JavaScript的技术和能力都发生了天翻地覆的变化，现在的JavaScript毫无疑问已经成为了世界上使用范围最广的软件平台————互联网————的核心技术。

但是作为一个语言来说，它总是成为大家批评的对象，部分原因是它有很多历史遗留问题，但主要原因是它的设计哲学有问题。就像Brendan Eich曾经说过的，JavaScript甚至连名字都给人一种“蠢弟弟”的感觉，就像是它更成熟的大哥Java的不完整版本。不过名字只不过是营销策略上的一个意外，这两个语言有许多本质上的区别。JavaScript和Java的关系，就像Carnival（嘉年华）和Car（汽车）的关系一样，八杆子打不着。

JavaScript借鉴了许多语言的概念和语法，比如C风格的过程式编程以及不太明显的Scheme/Lisp风格的函数式编程，因此吸引了许多开发者，甚至是那些不会编程的新手。用JavaScript来编写“Hello World”是非常简单的，因此这门语言很有吸引力并且很好上手。

虽然JavaScript可能是最早出现的语言之一，但是由于其本身的特殊性，相比其他语言，能真正掌握JavaScript的人比较少。如果想用C、C++这样的语言编写功能全面的程序，那需要对语言有很深的了解。但是对于JavaScript来说，编写功能全面的程序仅仅是冰山一角。

JavaScript语言本质上有许多复杂的概念，但是却用一种*看起来*比较简单的方式体现出来，比如回调函数，因此JavaScript开发者通常只是简单地使用这些特性，并不会关心语言内部的实现原理。

JavaScript既是一门充满吸引力、简单易用的语言，又是一门具有许多复杂微妙技术的语言，即使是经验丰富的JavaScript开发者，如果没有认真学习的话也无法真正理解它们。

这就是JavaScript的矛盾之处，也是这门语言的阿喀琉斯之踵。由于JavaScript不必理解就可以使用，因此通常来说很难真正理解语言本身，这就是我们面临的挑战。

## 使命

如果每次遇到JavaScript中出乎意料的行为时，你的反应就是把它加入黑名单（很多人都是这么做的），那用不了多久你就会把JavaScript语言真正的多样性全部排除。

剩下的部分就是非常著名的“好的部分”（The Good Parts），但是亲爱的读者们，我恳请你们把它称作“简单的部分”、“安全的部分”甚至“不完整的部分”。

“你不知道的JavaScript”系列丛书要做的事恰好相反：学习并且深入理解整个JavaScript，尤其是那些“难的部分”。

在本书中，我们要直面当前JavaScript开发者不求甚解的大趋势，他们往往不会深入理解语言内部的机制，遇到困难就会退缩。我们要做的恰好相反，不是退缩，而是继续前进。

你们应当像我一样，不满足于只是让代码正常工作，而是想要弄清楚“为什么”。我希望你能勇于挑战这条崎岖颠簸的“少有人走的路”，拥抱整个JavaScript。掌握了这些知识之后，无论什么技术、框架和流行词语你都能轻松理解。

这个系列中的每本书专注于语言中一个最容易被误解或者最难理解的核心部分，进行深入、详尽的介绍。在阅读本书时，你应当审视自己对于JavaScript的理解，仔细阅读思考书中讲解的理论和那些“你需要知道”的东西。

现在你所理解的JavaScript很可能是从别人那里学来的不完整版。这样的JavaScript只是真正的JavaScript的影子。学完这个系列之后，你就会掌握真正的JavaScript。读下去吧，我的朋友，JavaScript恭候你的光临。

## 总结

JavaScript非常特殊，只学一部分的话非常简单，但是想要完整地学习会很难（就算学到够用也不容易）。当开发者感到迷惑时，他们通常会责怪语言本身，而不是怪自己对语言缺乏了解。这个系列就是为了解决这个问题，让你打心眼儿里欣赏这门语言。

**注意**: 本书中的许多例子都需要运行在即将到来的现代JavaScript引擎环境中，比如：ES6。部分代码在旧（ES6之前的）引擎上可能无法正常运行。