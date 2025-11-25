# Cloud Tensor Storage Benchmarks

Earthmover's benchmark notebooks for cloud tensor storage libraries.
See [blog post] for more details.

## Running on Coiled

```python
coiled env create --conda environment.yml --name earthmover-demos
coiled notebook start --vm-type m8g.8xlarge --software earthmover-demos --region us-east-1 --sync
```
