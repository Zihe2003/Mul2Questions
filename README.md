![image](https://github.com/ZiheLiu-nlp/MulRQuestions/assets/85715842/bd6f44dd-0944-4479-8852-0a3d40e74225)

# MulRQuestions
## Dataset download
  You can download the MulRQuestions dataset at the following link: https://drive.google.com/drive/folders/1sT-qBekvGKdJBFmi7oKvZulO9wyX5gTg?usp=drive_link
## Dataset discription
  MulRQuestions is **the first large-scale Chinese-temporal** knowledge graph question answering dataset based on the paper "Towards Multi-Hop Reasoning over Dense Temporal Knowledge Graphs".
## Dataset example
  If you download the data set you will see that it consists of two parts: **Temporal KG** and **Reasoning QA.** Next, I'll illustrate the data format with an example:
    { 
        "questions": "Q18656签下Q63659是在哪一年？",
        "answer": [
            "2004"
        ],
        "answer_type": "time",
        "template": "{tail}签下{head}是在哪一年？",
        "entities": [
            "Q18656",
            "Q63659"
        ],
        "times": [],
        "relations": [
            "P54"
        ],
        "type": "simple_time",
        "paraphrases": "曼徹斯特聯足球俱樂部签下加夫列尔·海因策是在哪一年？"
    },
