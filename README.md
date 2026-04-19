# oldglycine-skills
oldglycine's little skills

Now in demo!(4/1 2026)

欢迎issue和意见！
Welcome issueeeeeeeeeeeees!!!

## 食用方法
告诉Agent"帮我安装skills就行"
> Please install Skills from github.com/OldGlycine/oldglycine-skills

## Skills
1. oldglycine-paper-reference-adder
- Step1. cd /path/to/your/workspace 
- Step2. 开启Agent
- Step3. 告诉Agent如下信息
    1. **input** 定位到哪个文件夹存放了你的论文文件
    ```目前推荐你的论文这么写，当然，Skill自己会引导Agent尝试分析论文结构
        folder/
        ├── custom.bib              # Citations
        ├── main.tex                # Concat all tex in section/
        └── section/                # All sections
            ├── 0_abstract.tex
            ├── 1_introduction.tex
            ├── 2_related_work.tex
            ├── 3_method.tex
            ├── 4_experiment.tex
            ├── 5_conclusion.tex
            └── ...
    ```
    2. **num_references** 添加引用数目 (default 10)
    3. **output** ADD.MD的位置，这里记录了"引用添加位置" 和 "引用文献"，方便追踪

- 当前优势: 
    - 无需 Google Scholar API.
    - Skill简单，token消耗较少.
