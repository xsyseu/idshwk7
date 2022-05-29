# idshwk7
利用LSB算法将文本信息隐藏到png图片中

隐藏信息：python LSBSteg.py encode -i test.png -o encode.png -f info.txt

作用：将info.txt的内容隐藏至test.png图片中生成一个新的文件encode.png

提取信息：python LSBSteg.py decode -i encode.png -o decode.txt

作用：提取encode.png中隐藏的文本信息并输出至decode.txt中
