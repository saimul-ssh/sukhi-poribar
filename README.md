
# Getting Started
To get started with this project, follow these steps:
1. Clone this repository to your local machine.
```
git clone https://github.com/SannketNikam/Chatbot.git](https://github.com/saimul-ssh/sukhi-poribar
```
2. Install the required Python libraries using:
```
pip install -r requirements.txt
```
3. Train the model using:
```
python training.py
```
4. Established Database connection with mysql using:
```
CREATE DATABASE user-system
USE user-system

CREATE TABLE `user` (
  `userid` int(11) NOT NULL,
  `name` varchar(100) NOT NULL,
  `email` varchar(100) NOT NULL,
  `password` varchar(255) NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4;

ALTER TABLE `user`
  ADD PRIMARY KEY (`userid`);

```
5. Final step: Run this app ->>>
```
flask run
```



