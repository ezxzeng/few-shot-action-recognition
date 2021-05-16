python run.py -c /work/tp8961/tmpfsar/otam_ssv2-tpb1-lr0.001 --dataset /work/tp8961/video_datasets/data/somethingsomethingv2_256x256q5_7l8 --tasks_per_batch 1 --method otam --test_iters 30000 50000 70000 100000 --num_gpus 4 --num_test_tasks 1000 -r


python run.py -c /work/tp8961/tmpfsar/pal-nopcc_ssv2-tpb1-lr0.001 --dataset /work/tp8961/video_datasets/data/somethingsomethingv2_256x256q5_7l8 --tasks_per_batch 1 --method pal --test_iters 10000 20000 30000 50000 70000 100000 --num_gpus 4 --num_test_tasks 1000 --print_freq 1

python run.py -c /work/tp8961/tmpfsar/pal-nopcc_ssv2-tpb1-lr0.001 --dataset data/ssv2small --tasks_per_batch 1 --method pal --test_iters 10000 20000 30000 50000 70000 100000 --num_gpus 4 --num_test_tasks 1000 --print_freq 1

python run.py -c /work/tp8961/tmpfsar/pal-nopcc_ssv2-tpb1-lr0.001 --dataset /work/tp8961/video_datasets/data/somethingsomethingv2_256x25s --val_iters 125000 150000 175000 200000 250000 --num_gpus 4 --num_test_tasks 1000 --print_freq 1000 -i 255020 -r