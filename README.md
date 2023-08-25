This repo contains the synthetic data for the Nugget paper.

The file `docs.txt` contains all the documents. Each line contains a doc id and the doc itself, separated by \\t.

The file `task.jsonl` contains the metadata of the task. Each line is a data point, where `source` is the id of the source doc, `candidates` are candidate doc ids, and the `answer` is the index of the target document in the candidate list.

Note that the paraphrase identification dataset contains 3 splits, but we only experiment with the dev set.

