# small_snippet
have something wrong with the torch.load of DDP
To reproduct the error, type this:

python eval.py (the path of data,like:/home/newdisk/zyx/small_snippet/vrp20_ten_seed1234.pkl) --model (the path of model parameters) --decode_strategy greedy --eval_batch_size 1

eg.
python eval.py /home/newdisk/zyx/small_snippet/vrp20_ten_seed1234.pkl --model /home/newdisk/zyx/small_snippet/outputs/run_20230330T151842/epoch-1.pt --decode_strategy greedy --eval_batch_size 1

The model parameters are stored in outputs.
