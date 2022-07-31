
### 中文詞向量
>#### 自做語料庫模型
>1. 先將所需文字(.txt)放入資料夾
>
>1. 使用 *製作語料模型.ipynb*
>    * 生成 *corpus.txt* 和 *corpusSegDone.txt*(暫存檔案可不理會)
>    * 生成自定義維度的模型 *word300.model*
>    * [語料模型參數設定解說](https://www.youtube.com/watch?v=gBH1kocbfZI)

>#### 維基百科語料庫模型
>1. 至維基百科下載 *zhwiki-20220101-pages-articles-multistream.xml.bz2*
>
>1. 使用 *製作wiki模型.ipynb* (檔案很大一般須要跑很久)
>    * 生成多項暫存可不理會
>    * 生成自定義維度的模型 *wiki.model*

>#### 歐式餘弦
>1. *中文詞向量.ipynb*
>    * 生成歐式和餘弦的csv檔
>    * [中文詞向量教學影片](https://youtu.be/-ja07wQ03ak)
>1. *四維製作.ipynb*
>    * 將csv做成四維圖型
>    * [四維散佈圖](https://youtu.be/ngUYXhXWrYw)
>1. *歐式餘弦介紹.ipynb*
