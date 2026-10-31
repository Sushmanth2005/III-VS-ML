Problem Statement
The amount of a new transaction is not known in advance, yet an estimate of it is useful for budgeting, for planning future spending and for flagging unusually large expenses. When expense records are kept in spreadsheets, any estimate must be made manually using simple averages, which ignore the combined effect of the category, the payment method and the date.
Simple averages and hand-written rules also fail to capture the complex, multi-dimensional relationships present in real spending data, and they provide no objective measure of accuracy. There is therefore a need for a data-driven system that learns from historical transactions, generalises to new ones, and predicts the amount automatically and reliably.
Solution
Every payment, whether a card swipe, a UPI transfer, a bill or a cash purchase, produces a record of how, when and on what money was spent. When these records are collected over time they form a dataset that can be analysed to understand spending behaviour, and the growth of digital payments has made such data more structured and more readily available than before.
Traditional expense tracking, however, is descriptive: it records and summarises what has already been spent but cannot estimate the value of a new transaction. Manual analysis of spreadsheets is also time-consuming and cannot capture the combined influence of many attributes such as the category, the payment method and the date.
Machine learning is well suited to this problem because the relationship between a transaction’s context and its amount is not a simple formula. This project therefore builds an end-to-end pipeline that cleans the data, trains two regression models, evaluates them objectively, and deploys the better model as a usable web application.


