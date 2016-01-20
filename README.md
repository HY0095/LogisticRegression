# LogisticRegression

           看到许多含有Logistic Regression的Python包，但或多或少，都缺少较全面的模型控制及结果检验参数，造成实际工作中的许多不便。
        这一点无法跟R中的LR Model相比，更不说跟SPSS或SASl。之前用R曾尝试写了几次，实现部分函数或功能，不过最后都东流了...
        
        终于下定决心，参照SAS Logistic Procedure。用Python来实现其中的Stepwise过程（解决了Stepwise，Forward和Backward就简单了）。
        stepwise.ipynb就是通过一个实例，测试了下其中的StepwiseModel。（测试数据来自于SAS中的logistic模块：http://support.sas.com/documentation/cdl/en/statug/63962/HTML/default/viewer.htm#statug_logistic_sect059.htm）
        
