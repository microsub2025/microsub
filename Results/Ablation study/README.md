# Ablation study
This folder contains the experimental results used in the ablation study. The ablation study evaluates the effectiveness of the three features employed in the proposed method.

## w/o filtering
***w/o filtering*** indicates a case where common components in the web app graph are not filtered out.

## w/o mapping clusters to use cases by semantic similarity
In ***w/o mapping clusters to use cases***, we assume that the ground truth is known. Then, We use the Hungarian algorithm to match clusters to use cases in a way that maximizes accuracy.

## w/o filtering out isolated components
In this case, we do not filter out isolated components.