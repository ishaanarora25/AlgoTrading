# AlgoTrading

## Overview

This repository consists of a **learning-focused algorithmic trading project** built following the [FreeCodeCamp Algorithmic Trading tutorial](https://www.youtube.com/watch?v=xfzGZB4HhEE&t=817s). It includes templates and foundational code structures from the tutorial; the repository represents an attempt to understand how to build and implement an algorithmic trading system.

## Project Structure

```
AlgoTrading/
    |--- CodeCampTutorial/
    |        |--- 001_equal_weight_S&P_500.ipynb
    |        |--- 002_quantitative_momentum_strategy.ipynb
    |        |___ 003_quantitative_value_strategy.ipynb
    |--- .gitignore
    |--- LICENSE 
    |--- README.md
    |___ environment.yml
```

## About

- ```environment.yml```: Conda virtual environment specs
- ```CodeCampTutorial/```: Directory that consists of the FreeCodeCamp tutorial
  - ```CodeCampTutorial/001_equal_weight_S&P_500.ipynb```: Jupyter Notebook of project that builds an alternative of the S&P 500 where each company has an equal weight
  - ```CodeCampTutorial/002_quantitative_momentum_strategy.ipynb```: Jupyter Notebook of project that implements a quantitative momentum strategy: creates an equal weight portfolio of 50 stocks with the highest price momentum
  - ```CodeCampTutorial/003_quantitative_value_strategy.ipynb```: Jupyter Notebook of project that implements a quantitative value strategy: creates an equal weight portfolio of 50 stocks with the best value metrics


## References

As mentioned earlier, this project follows the [FreeCodeCamp Algorithmic Trading tutorial](https://www.youtube.com/watch?v=xfzGZB4HhEE&t=817s). The code is taken from Nick McCullum's [algorithmic-trading-python](https://github.com/nickmccullum/algorithmic-trading-python/tree/master) repository.


## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
