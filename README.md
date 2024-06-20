# Meta-ED: Cross-lingual Event Detection Using Meta-learning for Indian Languages 
### Dataset
For collecting the dataset, please go to the link and fill in the registration form to collect the password: 

https://ednilfire.github.io/ednil/2020/dataset.html



### Requirements

- python 3.7
- pytorch 1.0.0
- pytorch_pretrained_bert


To train the code:

python main.py --result_dir directory_name -seed 667 --freeze_layer 0


To evaluate the results:

python main.py  --k_shot 10 --max_ft_steps 16  --test_langs te   --model_dir saved_model_directory --seed 667  --freeze_layer 0






