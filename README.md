# CTR-prediction-through-cross-domain-data-from-ads-and-news-feeds

### Description:

preprocess, get train and test data from csv file: 
python preprocess.py --input_dir "input_dir"

model train and predict, get pctr: 
python train.py --input_dir "input_dir" --output_dir "output_dir" --model_config_path "model_config_path"


### Environment:

tensorflow==2.0.0

#python train.py --input_dir data --output_dir data_out --model_config_path config/config.json