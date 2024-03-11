# educhain

A Python package for generating educational content using Generative AI. Educhain makes it easy to apply Generative AI in various educational use cases to create engaging and personalized learning experiences 

## Installation

```shell
pip install git+https://github.com/satvik314/educhain.git
```

## Usage

### Use it to Generate MCQs

```shell
from educhain import qa_engine

topic = "Quantum Entanglement"
level = "Intermediate"

mcq = qa_engine.generate_mcq(topic, level)
print(mcq)
```

### Effortlessly create Lesson Plans


```shell
from educhain import content_engine

topic = "Medieval History"
level = "Beginner"

lesson_plan = content_engine.generate_lesson_plan(topic, level)
print(lesson_plan)
```


## Next Steps

Will be releasing more features for MCQ Generation
- Bulk Generation
- Outputs in JSON format
- Export questions to CSV
- Generate questions from text/pdf file


