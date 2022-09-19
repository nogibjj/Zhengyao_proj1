# Zhengyao_proj1

## Project Workflow
![image](https://github.com/nogibjj/Zhengyao_proj1/blob/main/image.png)

## Test CLI
```
databricks clusters list --output JSON | jq
databricks fs ls dbfs:/
databricks jobs list --output JSON | jq
```

## Query Command
```
chmod +x query.py
./query.py cli-query
./query.py cli-query --query "YOUR QUERY CODE"
// "YOUR QUERY CODE" can be like "SELECT * FROM default.netflix1_csv LIMIT 2"
```

## Dataset
[dataset source](https://www.kaggle.com/datasets/ariyoomotade/netflix-data-cleaning-analysis-and-visualization)