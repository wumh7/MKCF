In this directory, we have manually made GT files for the Alice, Billy, Camen, Dolphy and Ellen.
They contains the bounding rects and polygon vertex for each target in every frame.
Each txt file is a dictionary type.
It uses the frame id as the main key. In each frame, it gives the 'Boundingbox'[x, y, width, height], 'Rotatedbox'[x,y,w,h, angle], 'Centroid'[x0,y0],'Polygon'[[x1,y1], ..., [xn, yn]] information of the targets.

可以通过Show_GT 函数来查看数据。

1.zhicheng_Alice 自60帧左下位置开始，400帧右下位置结束。 
                   80帧开始被后续船舶追赶， 120帧超越。
                   170帧开始尺度变大，
                   190帧与相近逆行船舶的杂波干扰，200帧结束
                   212帧穿越第二艘逆行船舶的杂波区，222帧结束。
                   227帧自身杂波变重，235帧好转。
                   253帧出现岸边的假回波，287帧假回波与之汇合。
                   289帧过桥，304帧出桥
                   330帧进入大桥的多径干扰回波区域，400帧结束。
                   
2.zhicheng_Camen  自2帧桥右侧多径开始
                    34-67穿桥而过
                    100帧多径干扰加重，170帧为甚。
                    190帧多径杂波会遇反向船舶
                    207帧多径回波极强
                    217帧多径回波再次会遇方向船舶
                    221帧多径回波扩展顶峰
                    222帧之后船舶回波减小，多径回波也减少。
                    380帧之后趋于稳定。

3.zhicheng_Billy 一条自北而南的轻快的小艇。
