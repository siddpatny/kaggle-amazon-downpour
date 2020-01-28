# kaggle-amazon-downpour
Kaggle amazon from space classification using CNN with Distributed Downpour SGD

Arguments:
use cuda : Use GPU (bool) (Default = false)
optimizer/-o : Optimizer Name (String) (Default = adam)
data path/-d: Path for Training Data (String) (default="/scratch/gd66/spring2019/lab2/kaggleamazon/")
nstep/-n : num of steps (Int) (default=2)

mpirun -np <No of Ranks> python lab4_sp5331.py -o adam -d /scratch/gd66/spring2019/lab2kaggleamazon/ -n <num of steps>

Output File Format:
Output<No of Ranks>_<No of Steps>.jobId
