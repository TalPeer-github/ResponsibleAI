![header](https://capsule-render.vercel.app/api?type=waving&height=300&color=160040&text=Responsible%20AI&textBg=false&desc=Law,%20Ethics%20and%20Society&fontColor=FAF4FF&animation=fadeIn&descAlignY=55&fontAlignY=25&stroke=27005D&strokeWidth=.5&fontSize=65&descSize=48&theme=holi)
![header](https://capsule-render.vercel.app/api?type=transparent&color=160040&height=65&reversal=true&textBg=True&fontSize=26&fontColor=FAF4FF&stroke=160040&strokeWidth=.7&text=%20Faculty%20of%20Data%20and%20Decisions%20Science%20-nl-%20&desc=%20Technion%20-%20Israel%20Institute%20of%20Technology&descSize=18&descAlignY=70&fontAlign=50&animation=fadeIn&reversal=true&textBg=True&section=header&theme=holi)
![header](https://capsule-render.vercel.app/api?type=transparent&color=160040&height=65&reversal=true&textBg=True&fontSize=26&fontColor=FAF4FF&stroke=160040&strokeWidth=.7&text=Faculty%20of%20Law%20-nl-%20&desc=%20Tel-Aviv%20University&descSize=18&descAlignY=70&descAlignX=50&fontAlign=50&animation=fadeIn&reversal=true&textBg=True&section=header&theme=holi)
![footer](https://capsule-render.vercel.app/api?type=waving&height=120&color=160040&text=Final%20Project&textBg=false&desc=Spring%202024&animation=fadeIn&descAlignY=90&fontAlignY=65&strokeWidth=.2&fontSize=28&descSize=16&reversal=false&fontColor=FAF4FF&stroke=160040&strokeWidth=.09&section=footer&descAlign=50&fontAlign=50&theme=holi)

![header](https://capsule-render.vercel.app/api?type=soft&color=160040&height=45&section=header&text=Authors&fontSize=28&fontAlign=7&fontColor=FAF4FF&reversal=true&theme=holi)
- Tal Peer (Technion) tal.peer@campus.technion.ac.il
- Carmel Soceanu (Technion) carmel.so@campus.technion.ac.il
- John Farran (Technion) John.f@campus.technion.ac.il
- Shahaf Karp (TAU) shahafkarp@mail.tau.ac.il
- Noam Ronen (TAU) noamronen2@mail.tau.ac.il
- Chaim Danino (TAU) chaimdanino1@mail.tau.ac.il

![header](https://capsule-render.vercel.app/api?type=soft&color=160040&height=45&section=header&text=Background&fontSize=28&fontAlign=10&fontColor=FAF4FF&reversal=true&theme=holi)
### **Worldbuikding notebook** - **HR_toy_case.ipynb**

In this project, we conduct an algorithmic audit of an AI system within a concrete context.<br>
The audit requires the integration of technological, legal, and ethical perspectives on novel case studies, values, and sectors.<br>

![header](https://capsule-render.vercel.app/api?type=transparent&color=160040&height=30&section=header&text=Algorithmic%20Audits&fontSize=20&fontAlign=10.8&fontColor=FAF4FF&reversal=false&textBg=true&theme=holi)

Audits of automated decision systems are proposed as a way to curb discrimination and disinformation, and to hold those who deploy algorithmic decision-making accountable for their harms.<br>
Many other uses of related terms, such as impact assessment, also impose obligations on covered entities to benchmark the development and implementation of algorithmic systems against some acceptable standard.

![header](https://capsule-render.vercel.app/api?type=transparent&color=160040&height=30&section=header&text=Human%20In%20%The%20Loop&fontSize=20&fontAlign=11.5&fontColor=FAF4FF&reversal=false&textBg=true&theme=holi)

Our project aims to audit an AI system within the context of **Human In The Loop** - <br>
Deep learning models have a greater capacity to learn complex patterns and interactions within data, which makes them more susceptible to perpetuating and even amplifying biases present in the training data. The lack of transparency and interpretability in these models further complicates efforts to identify and correct these biases, underscoring the need for careful data management, preprocessing, and the implementation of fairness-aware training techniques.

By demonstrating how easily bias can be introduced using a basic model with a Human In The Loop (HITL) layer (where basic models are much more explainable than the complex models commonly used today), and training it on generated data that accurately represents the population, we can highlight the potential for bias in more complex AI algorithms. We designed our toy-world in such a way that allows us to effectively test the hypothesis about the sufficiency of HITL in addressing bias.

![header](https://capsule-render.vercel.app/api?type=soft&color=160040&height=45&section=header&text=Dependencies&fontSize=28&fontAlign=11.5&fontColor=FAF4FF&reversal=true&theme=holi)


Project environment dependencies are listed in `requirements.txt`.
From the project root folder, run:

```bash
pip install -r requirements.txt
```

![header](https://capsule-render.vercel.app/api?type=soft&color=160040&height=45&section=header&text=Acknowledgment&fontSize=28&fontAlign=14&fontColor=FAF4FF&reversal=true&theme=holi)

Course information can be found on https://learn.responsibly.ai/2024-spring-tau-technion/ <br>
All Rights Reserved.
