#include<sys/ipc.h>
#include<sys/shm.h>
int shmget(key_t key,int size,int shmflg)
char *shmat(int shmid, char *shmaddr, int shmflg)
char *shmdt (int shmid, chsr *shmaddr, int Shmflg)
int shmctl(int shmid, int cmd,struct shmid_ds *buf)
