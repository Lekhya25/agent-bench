---
dataset_info:
  features:
  - name: instance_id
    dtype: string
  - name: description
    dtype: string
  - name: init
    dtype: string
  - name: get_agent_result
    dtype: string
  - name: get_ground_truth
    dtype: string
  - name: ground_truth
    dtype: string
  - name: comparison_method
    dtype: string
  splits:
  - name: osbench
    num_bytes: 114025
    num_examples: 144
  download_size: 52165
  dataset_size: 114025
configs:
- config_name: default
  data_files:
  - split: osbench
    path: data/osbench-*
---
