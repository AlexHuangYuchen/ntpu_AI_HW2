# 本程式使用 Google Colab 的 Secrets 功能管理 API 金鑰。
請在 Colab 左側的 Secrets 面板中加入：

Key: OPENAI_API_KEY
Value: <你的 OpenAI 金鑰>

程式會自動使用：

    api_key = userdata.get("OPENAI_API_KEY")

讀取金鑰，並初始化 OpenAI 客戶端。所有功能（相似度、分類、摘要）
都可以直接執行，不需修改任何程式碼。
