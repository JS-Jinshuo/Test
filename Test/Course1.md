# 课程一：初见Speech Recognition
语音模型：即将 **sound** 转换成 **text**

* **Text:** a sequence of Token
  * 长度：**N** ， 总种类数量：**V**
* **Sound:** vectors sequence
  * 长度：**T** ， 总种类数量：**d**
---

## 一、Text Token
**种类**
1. Phoneme：即 a unit of sound，可以理解为发音的音标
2. Grapheme：即 smallest unit of a writting，比如【26个英文字母+空格+标点符号】
3. Word：即语言中的单词
4. Morpheme：即 smallest meaningful unit，比如英语单词的词根
5. Bytes：直接用字节表示一组Text，常见的诸如 UTF-8 编码
   
**大家用的（大趋势）**
