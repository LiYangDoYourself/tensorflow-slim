# tensorflow-slim
1 convert_image_to_tfrecords.py 将已有的数据集转换成tfrecord格式 （注意修改slim/datasets 里样本数量和分类数 还有txt）<br/>
2 train_image_classifier.py 开启训练 <br/>
3 export_inference_graph.py 将图固话进pb文件 <br/>
4 freeze_graph.py 冻结数据和图 <br/>
5 quantize _graph.sh 压缩模型（执行graph_transforms） <br/>
