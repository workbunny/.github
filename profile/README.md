## Hi there 👋 一个even-loop玩具

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->

    一个event-loop实验品；

    是一个类似ReactPHP、AMPHP的事件循环组件；

    该项目主要研究ext-parallel和PHP-fiber在event-loop中如何有效结合，
    研究PHP在不利用ext-event、ext-ev、ext-uv等拓展的前提下是否可以实现
    更高的处理能力。

    An event loop experiment;

    It is an event loop component similar to ReactPHP and AMPHP;

    This project mainly studies how ext-parallel and PHP-fiber can
    be effectively combined in event-loop, and studies whether PHP 
    can achieve higher processing power without using extensions 
    like ext-event, ext-ev, ext-uv, etc.
___


    2022-05-09:

    目前ext-parallel还未支持PHP8.X，所以该项目仅实现了简单的基于libevent等基于系统I/O复用事件驱动的event-loop；

    等待ext-parallel的支撑
