# APITest
基于python实现的对后端接口进行自动化测试的框架

##实现原理
简单来说，通过requests网络请求库以及xlrd的excel文件操作库来实现，原理将api数据按照自定的格式填写在excel文件里面，然后通过xlrd库操作该文件，实现对应的数据填充，最后通过requests网络请求库来实现网络请求，通过对结果和预期的比较，看是否请求成功。
##后续
有时间会更新详细的设计原理以及实现过程。
