1.代码中用到了一些工具包，如果没有下载过需要手动下载一下，下载指令如下：
（1）打开cmd命令窗口（win+r，之后输入cmd）
（2）在命令行中依次输入pip install nltk 和 pip install python-docx
（3）提示successfully installed表示安装成功

2.nltk_data 涉及到的语料库使用指令下载容易出现错误，因此有一个"nltk_data.rar"，你需要把它解压到以下地址：
'C:\\Users\\Administrator\\AppData\\Roaming\\nltk_data'，没有的文件夹自己创建一下，压缩包中是从nltk_data
这一层开始的，所以你找到Roaming文件夹后把文件解压到这个下面应该就可以了。

3.xml文件与notebook文件默认放在了同一文件夹下，如果你的路径不同，记得在代码中修改为对应路径，或者将该notebook文件放到与xml文件一个文件夹下（修改位置在代码中有标注）

4.你的需求中没有要求提炼detailed_description,但是我看了一下brief_summary已经是一个摘要了，剩下的文本中值得进行提炼的就是这个部分，因此我额外提取了detailed_description并做了summarization。

