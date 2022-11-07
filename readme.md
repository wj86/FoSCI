## FoSCI dataset

The repository includes the data in FoSCI, which is our work early accessed on TSE2019.

documentation: the specification, user guide of the subjects.

testscenario:  the test scenarios for manual functional testing.

testplan: the formal testplan files with test cases, recorded by Apache JMeter.

traces: the collected execution traces.

supplements： the supplementary materials for FoSCI paper draft.


## FoSCI approach implementation

Our FOSCI implementation is also published and please see the *fosci-wrap* on the release page (V2 release).



## Our other microservice-related work

### microservice measurement

Software industrial practices decouple legacy software systems into microservice architectures to improve software maintainability and to achieve faster market delivery. Evaluating microservice code maintainability is a critical issue, facing the difficulties of multi-sourced data and diverse concerns of maintainability. By analyzing source code, code execution trace, and code revision history, we propose a multi-sourced feature space model to unify the representation of software multi-sourced data. Based on this model, we establish a microservice maintainability measurement system with comprehensive metrics, in terms of the concerns of functionality, modularity, modifiability, and interaction complexity. Accordingly, we also implement a tool prototype called MicroEvaluator, and carry out experimental analysis on open-source software systems.

Please see our paper for details: Jin WX, Zhong DH, Zhang YY, Yang MF, Liu T. Microservice Maintainability Measurement Based on Multi-sourced Feature Space[J]. Journal of Software, 2021, 32(5): 1322-1340


## Reference

** Please star this repository and reference the following papers if FoSCI helps you. We will continue to update this work.**


 ```
    @article{jin2019service,
  title={Service candidate identification from monolithic systems based on execution traces},
  author={Jin, Wuxia and Liu, Ting and Cai, Yuanfang and Kazman, Rick and Mo, Ran and Zheng, Qinghua},
  journal={IEEE Transactions on Software Engineering},
  year={2019},
  publisher={IEEE}
}

    @inproceedings{jin2018functionality,
  title={Functionality-oriented microservice extraction based on execution trace clustering},
  author={Jin, Wuxia and Liu, Ting and Zheng, Qinghua and Cui, Di and Cai, Yuanfang},
  booktitle={2018 IEEE International Conference on Web Services (ICWS)},
  pages={211--218},
  year={2018},
  organization={IEEE}
}

    @article{晋武侠2021基于多源特征空间的微服务可维护性评估,
  title={基于多源特征空间的微服务可维护性评估},
  author={晋武侠 and 钟定洪 and 张宇云 and 杨名帆 and 刘烃},
  journal={软件学报},
  volume={32},
  number={5},
  pages={1322--1340},
  year={2021}
}
```
