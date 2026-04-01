# oldglycine-skills
oldglycine's little skills

Now in demo!(4/1 2026)

Welcome issueeeeeeeeeeeees!!!

## How to eat?
Just tell Claude Code:
> Please install Skills from github.com/

## Skills
1. oldglycine-paper-add-citations
- Step1. cd /path/to/your/workspace 
- Step2. Start your agent
- Step3. Tell the agent 
    1. **input** to locate the folder where your LaTeX file for the paper is stored
    ```Currently, the recommended folder structure is
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
    2. **num_references** to set the number of citations (default 10)
    3. **output** to set the path for the ADD.MD report
    and start citation adding.

- Current advantages: 
    - Free for Google Scholar API.
    - Simple skill.
- Current drawbacks:
    - Currently, it can only add citations in the @article format.
    - I'm not entirely sure whether using "scholarly" to access the papers will trigger any security risk control measures by Google Scholar.