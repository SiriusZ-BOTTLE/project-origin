# project-origin

[^-^]: # (下面是中文版)
## 项目(代号) : 源

### 项目简介
本项目是一个大型的开放式多人创作项目. 创作内容不限, 创作时间不限, 创作者不限. 只要你有创作的意向和兴趣, 并能提供一些不错的设定, 故事等等, 都可以参与到这个项目中.  
基于项目中的分类标准, 该项目通常情况下可以接受任何类型的创作形式以及内容. 但涉及到政治, 反人类或抄袭的内容不得加入该项目. 注意, 色情, 血腥, 恐怖内容是被允许的.

### 本项目的Github网址: 
- [https://github.com/SiriusZ-BOTTLE/project-origin](https://github.com/SiriusZ-BOTTLE/project-origin)

### 项目内容
项目中可能出现的内容包括但不限于: 
- 文学相关
  - 故事
  - 小说
  - 人物
  - 史诗
  - 传记
  - 世界观
  - 国家
  - 宗教
  - 组织
  - 语言
- 美术设计相关:
  - 服装设计
  - 建筑设计
  - 美术风格
  - 艺术流派
- 生物学相关
  - 生物种类
  - 种族
  - 组织器官
  - 生物类别划分规则
- 天文学相关
  - 各类虚构架空的天体
- 理科学术相关
  - 用于完善世界观的各类科学学科比如数学物理化学等等

### 项目规范
> 注意该规范仅用于规范文档书写, 小说传记等非设定性质的文本不需要考虑该规范
- 文件命名
  - 文件的命名需要依照其内容的类别, 格式是: 
  ```所属定义集合名称-类别前缀-编号-前缀-内容名称-后缀.文件格式```
  注意必须按照该格式命名, 否则不应该加入正式标准

- 分组规则
  - 在为项目添加一些内容前, 你应该先创建一个定义集, 并为他取名, 然后你可以在集合内自由创作
  - 通常情况下, 一个世界观的名称, 一个国家的名称都可以作为定义集合的名称, 名称也可以是纯粹的无意义符号, 看你喜好
  - 你也可以与他人共同维护一个集合, 但是注意不能在顶层目录下直接添加文件

- 文件中的名词解释
  - 所有文件对于不常用词, 生僻词, 或者虚构的词以及可能存在歧义的词, 必须在文件开头对其使用表格进行罗列与解释
  - 举例:
    |  词   | 其它语言的对应词 |    解释     |
    | :---: | :--------------: | :---------: |
    |  xxx  |      xxxxx       | xxxxxxxxxxx |
    |  xxx  |      xxxxx       | xxxxxxxxxxx |

- 文件对其它文件的引用
  - 考虑到一个人创建的某个文档可能包含对他人或自己创建的已经存在的文件中的内容的引用. 被引用的文件名和内容必须在文档开头以表格进行标注
  - 举例:
    | 引用的概念/内容 | 引用目的 |  文件路径   |
    | :-------------: | :------: | :---------: |
    |       xxx       |  xxxxx   | xxxxxxxxxxx |
    |       xxx       |  xxxxx   | xxxxxxxxxxx |

- 项目中允许的内容:
  - **原创的内容**
  - **在征得原作者同意后的二次创作内容**
  - **小规模借鉴其它作品内容的部分原创内容**
- 被项目所禁止的内容:
  - **抄袭, 或者未经原作者同意的情况下搬运的内容**
  - **反人类, 反社会的内容**
  - **涉嫌隐射政治, 与政治有关的任何内容**
  - **完全无效, 没有意义, 或者被多数维护者认为是非常糟糕的内容**
- 命名及书写规范
  - 下划线分割
    - 同一个词组之间应该使用下划线分割,
    - 由于中文的特殊性大多数情况下可能不需要使用下划线分割
    - 举例
    ```
    default_world
    //中文可能不需要下划线分割
    初始世界
    ```
  - 横线分割
    - 举例
    ```
    xxx-xxxxx
    //前面的W-0-0是编号, 代表世界分类中的第0-0号, 后面跟着该世界的名称
    W-0-0-初始世界观
    ```
  - 点号索引
    - 举例
    ```
    //表示: 教国的国王的王冠, 逐级向下索引
    教国.国王.王冠
    //表示: 甲星的北半球
    甲星.北半球
    ```
  - 定义集/定义空间
    - 举例
    ```
    //以下服号代表了一个定义集, 其中"初始世界观"是其名称
    {初始世界观}
    ```
  - 双冒号索引
    - 用来指示一个文件中的内容或者指示一个文件夹中的文件
    - 举例
    ```
    //表示: 定义集1下的文件file1.md中的xxx内容
    {定义集1}/file1.md::xxx
    ```
  - 一些基本**类别前缀**
    - 用于区别不同的分类, 提高文件的可读性

    | 前缀  |     英文     |      类别      |
    | :---: | :----------: | :------------: |
    |   C   |  collection  |      集合      |
    |   S   |   setting    |      设定      |
    |   W   |    world     |  世界/世界观   |
    |   R   |     race     |      种族      |
    |  NO   |    novel     |      小说      |
    |  LA   |   language   |      语言      |
    |  NA   |    nation    |      国家      |
    |   O   | organization |   组织/团体    |
    |  LE   |    legend    |      传说      |
    |  LI   |  literature  |      文献      |
    |   E   |     epic     |      史诗      |
    |  PI   |   pictrue    | 图片/图画/插画 |
    |  MU   |    music     |      音乐      |
    |   U   | unclassified |     未分类     |
    

---

[0-0]: # (下面是英文版)
## project : origin
- nobody translates this content now
- 暂时无人翻译




