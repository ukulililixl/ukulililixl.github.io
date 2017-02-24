# Example

We write a very simple example to test the framework we build:

* In our test, we use one husky master and one husky worker.
* Husky worker will run a program, which will create an instance of our redis_inputformat.
* Then send request to the husky master for some keys.
* husky master knows that this is a request which want to get data from redis, then will use our RedisAssigner
* In our RedisAssigner, we hardcode one key and return to the husky worker.
* Then husky worker will send request to redis and get value of the key.
