本次作业利用LSBSteg.py程序将学号、姓名等文本信息隐藏到test.png图片中,得到hide.png

隐藏信息：
python LSBSteg.py encode -i test.png -o hide.png -f info.txt

作用：
将info.txt的内容隐藏至test.png图片中生成一个新的文件hide.png

提取信息：
python LSBSteg.py decode -i hide.png -o deinfo.txt

作用：
提取hide.png中隐藏的文本信息并输出至deinfo.txt中