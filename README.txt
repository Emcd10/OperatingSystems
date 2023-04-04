This code shows the produccer and consumer problem by using semaphores and shared memory. The producer will produce items and put them on the table, which can hold two
items. The consumer will consume items off the table if there are items to consume. The producer will produce whenever there is room on the table


Compilation:
$ gcc producer.c -pthread -lrt -o producer
$ gcc consumer.c -pthread -lrt -o consumer
$ ./producer & ./consumer&
