# Interview-Task
Write a small trading program in a Jupyter notebook

## Overview

In this task, I would like you to conduct a small research project entirely from scratch. The task is structured to be as close to the on-the-job experience as possible, so you:

- will be coding in Python,
- will be expected to envision a structure for your solution,
- may run into unanticipated difficulties along the way,
- are free to leverage off open source libraries/tools you know,
- are free to Google, StackOverflow, or check external resources, and
- should also see if this role truly interests you.

## Task

Construct a simple trading signal on some constituents of the [S&P500](https://en.wikipedia.org/wiki/S%26P_500) (that is, not the index), and then run it through a backtest. Present its PnL and any relevant risk/reward metrics you wish.

_Note_: The signal does not need to carry any IP (intellectual property). You can even implement [momentum](<https://en.wikipedia.org/wiki/Momentum_(technical_analysis)>) as described by Wikipedia. In fact, do this, if you have no prior trading experience.

You will need to fetch the data to support this work yourself. Use a library of your choice, but if you have no prior convinctions, try [yfinance](https://github.com/ranaroussi/yfinance). This would necessitate you learning to use a new tool, which, invariably will happen on the job too.

You will need to conduct your analysis with [pandas](https://github.com/pandas-dev/pandas) and to present it with [jupyter](https://github.com/jupyterlab/jupyterlab/). Be sure to include some charts, using any visualization library of your choice.

Simplifying assumptions:

- The period of time can be anytime to anytime.
- The universe over the period of time can be assumed to be constant, with the same constituents as those in the S&P today.

Feel free to make further simplifying assumptions - they are not forbidden. Just be prepared to explain why you did it.

## Submission

Upload your code into a new repo under the `DavidCico-HexTrust` account. If you are unable to do this, then email your code to `david.cicoria@hextrust.com`.
