####样式的继承与覆盖
```
demo1     通过对class为abstract的标签和它下面的a标签设置样式，达到使所有的文字都显示成 color为grey的效果，
          所有的链接也要与其它文字显示一样，灰色，没有下划线。
          同时，所有的标签都要象前面一样有边框，border的值设置为thin black solid就可以了。
demo2     本题目里h1元素已经被style标签里的元素选择器设置成了红色。
          要求在外部css文件中，使用优先级更高的id选择器，来覆盖掉红色的设置，将其设置为黑色。
demo3     本题目里h1元素已经被内联样式设置成了灰色。
          要求在外部css文件中，仍然使用id选择器，通过　!important　来覆盖掉灰色的设置，将其设置为黑色
demo4     本题目里要求a元素被设置为黑色。 但是class为hehe的a元素，则要被设置为白色，并且背景要被设置成灰色(grey)
demo5     我们写两个class hehe1和hehe2. 让class为hehe1的元素，颜色为黑色。
          让class为hehe2的元素，颜色为白色，背景颜色是灰色。
          最终要让同时拥有hehe1和hehe2的元素a，显示为hehe2的效果
demo6     要求让class为abstract的元素，颜色是白色（white），背景色是灰色（grey），边框是medium black solid
          并且让span也继承abstract的border
```