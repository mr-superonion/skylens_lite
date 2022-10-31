
Run the following commends to estimate the nzs and two-point correlation
functions:

```shell
myqsub mpirun ./meas_nz_true.py --minId 0 --maxId 2268 --mpi
myqsub mpirun ./meas_2pcf.py --minId 0 --maxId 2268 --mpi
```
Note, `myqsub` can be found [here](https://github.com/mr-superonion/dotfiles_server/blob/main/bin/myqsub)
