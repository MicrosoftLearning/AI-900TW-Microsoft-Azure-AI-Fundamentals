## 本機開發本機開發本機開發本機開發本機開發 

如果您正在本機電腦上工作，可以追隨以下步驟來設定您的環境以便使用實驗室工作。  

### C++ 可轉散發套件 
1. 下載並安裝 [Visual C++ 可轉散發套件 (x64)](https://aka.ms/vs/16/release/vc_redist.x64.exe) 

### Python 和必要套件 
1. 安裝 [Python 3.6.1](https://www.python.org/downloads/release/python-361/)  
   - **重點**：選取選項把 Python 新增到 PATH 變數並且以預設 Python 環境登錄 
2. 完成安裝後，開啟*命令提示字元*並輸入以下命令以安裝必要套件： 

> pip install ipython jupyter matplotlib pillow requests azure-cognitiveservices-vision-computervision azure-cognitiveservices-vision-customvision azure-cognitiveservices-vision-face azure-cognitiveservices-language-textanalytics azure.cognitiveservices.speech azure_ai_formrecognizer 

### Visual Studio Code 
1. 如果還沒有 Visual Studio Code，[請在此處下載](https://code.visualstudio.com/Download)。完成安裝後，開啟 Visual Studio Code 並在擴充套件索引標籤 (CTRL+SHIFT+X) 上，搜尋並安裝 Microsoft 中的 **Python** 擴充套件。

2. 在 Visual Studio Code 中，開啟新的終端機，輸入 **git clone https://github.com/MicrosoftLearning/AI-900TW-Microsoft-Azure-AI-Fundamentals** 然後選取 *[Enter]*。 

