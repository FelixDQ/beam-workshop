# beam-workshop

Objective: Count the number of times each word occurs in `gs://dataflow-samples/shakespeare/kinglear.txt` and output it into a file

## How to run
Create venv
```sh
python -m venv env
```

Activate it:
```sh
source env/bin/activate
```

Install requirements:
```sh
pip install -r requirements.txt
```

Run the pipeline:
```
python pipeline.py --output output.txt
```

