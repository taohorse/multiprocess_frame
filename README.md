# multiprocess_frame
a frame for python multiprocess to solve GIL
# 框架实现说明：
* BasicWorkerPool
  实现进程池的状态管理，进程池中进程的启动、停止、状态监控指令的下发。
* BasicWorker
  实现单个进程的状态管理，进程的启动、停止任务的执行。
* WorkerControllerWithInputThread
  具体进程业务逻辑的实现。
* BasicWorkerControler
  业务逻辑实现基类。
# 使用说明：
  用户只要继承各个类型，根据自己业务实现业务逻辑即可。可以参考main函数中的测试用例。

 
