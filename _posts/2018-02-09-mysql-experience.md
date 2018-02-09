The experience of trying to install and connect to a mysql

1. Tried two types of ways for installation. (1) download the dmg (for Mac) and install it like a app, (2) used homebrew to install in terminal [this site](https://www.cnblogs.com/chenmo-xpw/p/6102933.html) has good words for these two ways.


2. The first trick I met was that it seemed the version 5.7 could not work well with the latest macOS. It costed me one day to finally catch this [trap](https://devmarketer.io/learn/do-not-install-mysql-macos-sierra-how-to-fix/). too bad!


3. I then installed version 5.6. The install went well, and I could see mysql on Mac System Preference Pane. And it was running green. Nice. Then I downloaded mysql workbench, a GUI tool for mysql management. the second trick happened. I could not connect to mysql instance with my account. 也就是说，你装好了mysql, 他也跑起来了，但你就是连不上他，我靠。
    finally I resolved this issue by experience from [here](http://www.jb51.net/article/105668.htm), though I was not fully understanding why.

4. Now, I have mysql running and I can connect to it with my account. You may play with it by following the instructions [here](https://dev.mysql.com/doc/refman/5.6/en/selecting-all.html).

5. My original try was for working out a node-mysql solution for a task, and really did not anticipate there were so many tricks in working with such a mature database. Playing with mongodb with node only totally cost me several hours.