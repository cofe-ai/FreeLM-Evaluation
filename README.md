# FreeLM-Evaluation

The data used in evaluating FreeLM is released in this rep.

Because the test data of [GLUE](!https://gluebenchmark.com/) is not published, we sample `1k` instances from the development set of GLUE. Then, we use this sub-dataset to evaluate our proposed FreeLM and baselines.

Note that the OpenAI API is expensive, so we only sample `1k`. If you have more budget, you could use the `5k` or `10k` versions.
