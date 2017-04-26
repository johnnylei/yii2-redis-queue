# yii2-redis-queue
基于yii2通过redis的订阅／发布者模式实现的消息队列

# install 
composer require --prefer-dist johnnylei/yii2-redis-queue

#usage
配置文件
'redis_queue'=>[
    'class'=>'johnnylei\redis_queue\RedisQueue',
],
