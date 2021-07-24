# 12 个有趣的 CSS 文本阴影
像大多数 CSS 效果一样，文本阴影在基本形式中实现起来非常简单，但如果您真的在其中进行一些工作，它们可以采用各种不同的形式。 使用逗号作为分隔符，您可以将 CSS 阴影堆叠在一起，以显着增加效果的强度和真实感。 看一些例子：


![](https://raw.githubusercontent.com/hongwenjun/css-shadow/master/img-samples/01%20The%20Basic%20Shadow.jpg)
## The Basic Shadow
	text-shadow:  2px  4px  3px  rgba(0,0,0,0.3);

![](https://raw.githubusercontent.com/hongwenjun/css-shadow/master/img-samples/02%20Quick%20and%20Dirty%20Letterpress.jpg)
## Quick and Dirty Letterpress
    body  {
	    background:  #222;
    }

    #text h1 {
	    color:  rgba(0,0,0,0.6);
	    text-shadow:  2px  2px  3px  rgba(255,255,255,0.1);
    }

![](https://raw.githubusercontent.com/hongwenjun/css-shadow/master/img-samples/03%20Hard%20Shadow.jpg)
## Hard Shadow
	text-shadow:  6px  6px  0px  rgba(0,0,0,0.2);

![](https://raw.githubusercontent.com/hongwenjun/css-shadow/master/img-samples/04%20Double%20Shadow.jpg)
## Double Shadow
	text-shadow:  4px  3px  0px  #fff, 9px 8px 0px rgba(0,0,0,0.15);

![](https://raw.githubusercontent.com/hongwenjun/css-shadow/master/img-samples/05%20Down%20and%20Distant.jpg)
## Down and Distant
    text-shadow:	0px  3px  0px  #b2a98f,
				    0px  14px  10px  rgba(0,0,0,0.15),
				    0px  24px  2px  rgba(0,0,0,0.1),
				    0px  34px  30px  rgba(0,0,0,0.1);

![](https://raw.githubusercontent.com/hongwenjun/css-shadow/master/img-samples/06%20Close%20and%20Heavy.jpg)
## Close and Heavy
    text-shadow:	0px  4px  3px  rgba(0,0,0,0.4),
				    0px  8px  13px  rgba(0,0,0,0.1),
				    0px  18px  23px  rgba(0,0,0,0.1);

![](https://raw.githubusercontent.com/hongwenjun/css-shadow/master/img-samples/07%20A%20Little%20Help.jpg)
## Seriously 3D Text
    text-shadow:	0 1px 0 #ccc,
					0 2px 0 #c9c9c9,
					0 3px 0 #bbb,
					0 4px 0 #b9b9b9,
					0 5px 0 #aaa,
					0 6px 1px rgba(0,0,0,.1),
					0 0 5px rgba(0,0,0,.1),
					0 1px 3px rgba(0,0,0,.3),
					0 3px 5px rgba(0,0,0,.2),
					0 5px 10px rgba(0,0,0,.25),
					0 10px 10px rgba(0,0,0,.2),
					0 20px 20px rgba(0,0,0,.15);

![](https://raw.githubusercontent.com/hongwenjun/css-shadow/master/img-samples/08%20True%20Inset%20Text.jpg)
## True Inset Text
    background-color: #666666;
    -webkit-background-clip: text;
    -moz-background-clip: text;
    background-clip: text;
    color: transparent;
    text-shadow: rgba(255,255,255,0.5) 0px 3px 3px;

![](https://raw.githubusercontent.com/hongwenjun/css-shadow/master/img-samples/09%20Glowing.jpg)
## Glowing
    text-shadow: 0px 0px 6px rgba(255,255,255,0.7);


![](https://raw.githubusercontent.com/hongwenjun/css-shadow/master/img-samples/10%20Superhero.jpg)
## Superhero
    text-shadow:	-10px 10px 0px #00e6e6,
				    -20px 20px 0px #01cccc,
					-30px 30px 0px #00bdbd;
![](https://raw.githubusercontent.com/hongwenjun/css-shadow/master/img-samples/11%20Multiple%20Light%20Sources.jpg)
## Multiple Light Sources
    text-shadow:	0px 15px 5px rgba(0,0,0,0.1),
				    10px 20px 5px rgba(0,0,0,0.05),
					-10px 20px 5px rgba(0,0,0,0.05);
					
![](https://raw.githubusercontent.com/hongwenjun/css-shadow/master/img-samples/12%20Soft%20Emboss.jpg)
## Soft Emboss
    color: rgba(0,0,0,0.6);
    text-shadow:	2px 8px 6px rgba(0,0,0,0.2),
                    0px -5px 35px rgba(255,255,255,0.3);
