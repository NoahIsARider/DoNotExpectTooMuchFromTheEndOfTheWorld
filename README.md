![image](https://github.com/user-attachments/assets/baba7406-33da-4353-a481-b9337cf47e4c)

[DON'T EXPECT MUCH FROM THE END OF THE WORLD!!!](https://movie.douban.com/subject/35772577/)

### English
# README

## I. Model Overview
This model is developed based on `LLM - Research/Meta - Llama - 3 - 8B - Instruct` and is applied to text generation tasks in the field of Natural Language Processing (NLP). It uses the Pytorch framework and follows the Apache License 2.0 open - source protocol.

## II. Model Features and Advantages
1. **High - quality Text Generation**: Through careful training and fine - tuning, it can meet various text generation needs.
2. **Powerful Architecture Support**: Relying on a powerful basic model architecture, it performs well in language understanding and generation.

## III. Dataset Introduction
The dataset is stored in the `noah_dataset.json` file and focuses on key issues in the social and political fields. It has the following characteristics:
1. **Focused and Diverse Themes**: It revolves around issues such as the split between the old and new left, the impact of migrant workers, and the refugee crisis, covering from macro - political theories to micro - social phenomena. For example, the split between the old and new left involves the geopolitical order after World War II and the differences between factions; the impact of migrant workers analyzes the changes in the European social structure due to labor mobility; the refugee crisis is analyzed from multiple perspectives such as the responses of various governments, deep - seated problems, and legal - theoretical dilemmas, providing materials for research in different fields.
2. **Structured Q&A Format**: It is presented in the form of question - answer pairs. Each data item contains a clear question (`instruction` field) and a detailed answer (`output` field). This is not only convenient for the training, validation, and testing of question - answering systems but also allows researchers and users to quickly locate and obtain information on specific questions.
3. **Rich and Detailed Content**: It covers a wide range of specific questions, such as the evolution of political ideas, the analysis of social phenomena, theoretical discussions, and the presentation of real - world problems. There are in - depth analyses of the old and new left and the refugee issue, meeting the needs of different research directions.
4. **Great Practical Significance**: The topics involved are closely related to current social real - world problems, such as the multi - dimensional analysis of the refugee crisis and the exploration of the relationship between global capitalism and the refugee crisis, providing reference and theoretical support for understanding and researching real - world problems.
5. **Potential Educational Value**: It can be used as an educational resource in schools and training institutions. For example, in political science and sociology courses, teachers can use the question - answer pairs to guide students to discuss and think, cultivating their critical thinking and problem - solving abilities.

References include: *The End is Nigh: Europe, Refugees, and the Left*, *On History*, *Key Concepts of Deleuze*, *Foucault: Key Concepts*, *The Matrix of Visual Culture (Discussing Film Theory with Deleuze)*, *Amusing Ourselves to Death・The Disappearance of Childhood*, *Imagined Communities*

## IV. Download and Installation

Execute the command to clone the model repository:

```
git lfs install
```

```
git clone [https://www.modelscope.cn/LLM - Research/Meta - Llama - 3.1 - 8B - Instruct.git](https://github.com/NoahIsARider/DoNotExpectTooMuchFromTheEndOfTheWorld.git
```
Use the existing dataset or replace it with your own dataset. Open the terminal in the folder `DoNotExpectTooMuchFromTheEndOfTheWorld` and execute the following to open the interactive interface:
```
python app.py
```

## V. Usage Example
After the model is downloaded, it can be integrated into projects according to specific application scenarios. Call it according to the corresponding API or interface specifications to achieve the text generation function. For example, in a text - creation application, input prompt information or a theme, and the model will generate text content such as stories, articles, and dialogues. The `test.py` file is a usage example.

## VI. Model Training and Optimization
The model training uses advanced algorithms and technologies. It is trained and optimized with a large amount of text data to improve performance and generation quality. Specific training details and parameter settings can be adjusted and improved according to actual situations.

## VII. Future Development and Contributions
### Reference Websites
The writing of the training script of this model can refer to: [https://github.com/datawhalechina/self - llm](https://github.com/datawhalechina/self - llm)

This model is developed based on Meta - Llama - 3.1 - 8B - Instruct, and the original website is: [https://www.modelscope.cn/search?search=Meta - Llama - 3.1 - 8B - Instruct](https://www.modelscope.cn/search?search=Meta - Llama - 3.1 - 8B - Instruct)

The dataset can be found and previewed on this website: [https://www.modelscope.cn/datasets/NoahIsARider/NoahIsACollector](https://www.modelscope.cn/datasets/NoahIsARider/NoahIsACollector)

Developers and researchers are welcome to further study and improve this model. If you have new ideas, discoveries, or improvement suggestions, you can communicate and cooperate by submitting a Pull Request or an Issue to jointly promote the development and application of the model.

## VIII. Precautions
When using this model, ensure that the usage behavior complies with the requirements of the Apache License 2.0. Appropriately review and verify the content generated by the model to ensure its accuracy and reliability.

### Chinese
# README

## 一、模型概述
本模型基于 `LLM - Research/Meta - Llama - 3 - 8B - Instruct` 开发，应用于自然语言处理（NLP）领域的文本生成任务。采用 Pytorch 框架，遵循 Apache License 2.0 开源协议。

## 二、模型特点与优势
1. **高质量文本生成**：经精心训练和微调，能满足多种文本生成需求。
2. **强大架构支持**：依托强大基础模型架构，在语言理解和生成方面表现良好。

## 三、数据集介绍
数据集存储于 `noah_dataset.json` 文件，聚焦社会政治领域关键议题，具有以下特点：
1. **主题聚焦且多元化**：围绕新老左翼分裂、移民工人影响、难民危机等议题，涵盖宏观政治理论到微观社会现象层面。例如新老左翼分裂涉及二战后地缘政治秩序及派别差异；移民工人影响分析了劳动力流动对欧洲社会结构等改变；难民危机从各国政府反应、深层次问题及法律理论困境等多角度剖析，为不同领域研究提供素材。
2. **结构化问答形式**：以问答对形式呈现，每个数据项含明确问题（`instruction` 字段）及详细回答（`output` 字段）。既方便问答系统训练、验证和测试，也便于研究人员和用户快速定位获取特定问题信息。
3. **内容丰富详实**：涵盖广泛具体问题，如政治思想演变、社会现象分析、理论探讨及现实问题呈现。在新老左翼和难民问题上有深入分析，满足不同研究方向需求。
4. **具有重要现实意义**：涉及主题与当今社会现实问题紧密相关，如对难民危机多维度分析，及全球资本主义与难民危机关系探讨，为理解和研究现实问题提供参考及理论支持。
5. **潜在教育价值**：可作为教育资源，用于学校、培训机构教学。如在政治学、社会学课程中，教师利用问答对引导学生讨论思考，培养批判性思维和分析问题能力。

参考文献包括：《终局将至：欧洲、难民与左翼》，《论历史》，《德勒兹关键概念》，《福柯：关键概念》，《视觉文化的基体(与德勒兹探讨电影理论)》，《娱乐至死・童年的消逝》，《想象的共同体》

## 四、下载与安装

执行命令克隆模型仓库：

```
git lfs install
```

```
git clone [https://www.modelscope.cn/LLM - Research/Meta - Llama - 3.1 - 8B - Instruct.git](https://github.com/NoahIsARider/DoNotExpectTooMuchFromTheEndOfTheWorld.git
```
使用已有数据集，或者替换成你自己的数据集，在文件夹DoNotExpectTooMuchFromTheEndOfTheWorld中打开终端并执行下面打开交互界面：
```
python app.py
```

## 五、使用示例
模型下载完成后，可依据具体应用场景集成到项目中，按相应 API 或接口规范调用实现文本生成功能。如在文本创作应用中，输入提示信息或主题，模型生成故事、文章、对话等文本内容。test.py文件是一个使用实例

## 六、模型训练与优化
模型训练采用先进算法和技术，经大量文本数据训练优化以提升性能和生成质量。具体训练细节和参数设置可依实际情况调整改进。

## 七、未来发展与贡献
### 参考网站
本模型训练脚本的编写可参考：[https://github.com/datawhalechina/self - llm](https://github.com/datawhalechina/self - llm)

本模型基于Meta - Llama - 3.1 - 8B - Instruct开发，原网址为：[https://www.modelscope.cn/search?search=Meta - Llama - 3.1 - 8B - Instruct](https://www.modelscope.cn/search?search=Meta - Llama - 3.1 - 8B - Instruct)

数据集可以在该网站找到并且预览：[https://www.modelscope.cn/datasets/NoahIsARider/NoahIsACollector](https://www.modelscope.cn/datasets/NoahIsARider/NoahIsACollector)

欢迎广大开发者和研究人员对本模型进一步研究改进。如有新想法、发现或改进建议，可通过提交 Pull Request 或 Issue 方式交流合作，共同推动模型发展应用。

## 八、注意事项
使用本模型时，确保使用行为符合 Apache License 2.0 协议要求。对模型生成内容应适当审核验证，保证准确性和可靠性。
