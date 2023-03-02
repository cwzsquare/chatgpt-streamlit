# chatgpt-streamlit

当然是基于 chatgpt 的`gpt-3.5-turbo`的 api 的一个小型对话 demo 。
![sample](https://i.imgur.com/NavMcXL.png)

## 运行方法
python3 ，依赖于`openai`、`streamlit`

运行方法：

```
streamlit run app.py
```
（其他问题可以直接问chatgpt）

## 注意事项
1. 请在 app.py 中填入自己的 api_key ，去 https://platform.openai.com/account/api-keys 申请吧；
2. streamlit确实比较适合 web demo ，特别是直接渲染 markdown ~~，但bug估计不少~~
3. 大概率是自用的小 demo ，但欢迎 fork 自改