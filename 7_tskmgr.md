Reference:>https://www.ithome.com/0/489/510.htm

#CTRL + Shift + Esc#
大多数人启动任务管理器的方法是右击任务栏选择任务管理器，或者按CTRL + Alt + Del，然后选择任务管理器。但实际上，按CTRL + Shift + Esc就可以直接启动任务管理器，这要简单得多，并且可以在不使用shell的情况下打开任务管理器。

为什么说这比其他方法更有用呢？因为在不涉及shell的情况下，这个快捷键可以让你在shell本身崩溃的情况下也能启动任务管理器，有时候任务栏消失就不能右键启动任务管理器。

Plummer说，即使在任务管理器本身崩溃时，也可以使用同样的快捷方式启动该应用，而这一切都是因为这个快捷键从一开始设计就专门考虑到了这个问题。

“如果任务管理器曾经卡死或崩溃，按ctrl-shift-esc启动另一个任务管理器。Winlogon会寻找一个现有的实例，并尝试重启它，最多10秒。如果旧的任务管理器没有在这段时间内以秘密代码响应，那么另一个任务管理器将被启动。”他说：“这样一来，只要有一些资源可用，你永远不会打不开任务管理器。”

任务管理器精简模式
很多用户都已经知道，APP死机、系统资源耗尽，可能会导致各种问题，包括电脑一开始就无法启动任务管理器。

这是因为没有资源来加载任务管理器，所以开发者在创建这个APP的时候，也准备了一个精简模式来处理资源不足的问题。

换句话说，这是一个特殊的“安全”模式，你可以启动，然后直接点开进程选项卡，看看是什么原因导致资源占用，然后手动杀死进程，让系统恢复到正常工作状态。同样，你可以使用上述的快捷方式来完成，因为当系统资源耗尽时，任务管理器会自动进入精简模式。

“任务管理器会在资源不足的情况下以精简模式加载，比如只加载进程页面。它是极少数不会在出现问题时直接‘失败和退出’的应用程序之一。”Plummer说。

重置任务管理器
不用说，在某些情况下，即使任务管理器也难以处理系统上的所有崩溃，因此任务管理器本身有时也可能会崩溃。

不过不用担心，因为Plummer表示，你只需要用一个非常小的技巧就可以轻松地将其重置，并将其恢复到正常状态。

“如果任务管理器一旦内部损坏，请杀死/关闭它。然后重启它的同时按住CTRL、ALT和SHIFT键，任务管理器在启动时如果检测到了这个组合键，就会将所有内部设置重置为出厂时的状态。”他还解释说：“我写的每一个应用都有这个小技巧！”。

总而言之，Windows任务管理器是一个比大多数人想象的要复杂得多的应用，而这一切都是因为它在开发之初就考虑到了用户在需要该应用时可能遇到的大部分场景。幸运的是，微软在这么多年的时间里并没有改变任务管理器的根基，所以上述技巧不仅在老版本的Windows中可以使用，在Windows 10中也可以正常使用。