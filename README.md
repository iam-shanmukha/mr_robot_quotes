# mr_robot_quotes
A bunch of Mr. Robot Quotes in Terminal
# Usage
```
git clone https://github.com/iam-shanmukha/mr_robot_quotes.git
cd mr_robot_quotes
python3.6 mr_robot_quotes.py
```
To get quotes on Terminal startup, modify `.bashrc` file
```
echo "python3.6 $(pwd)/mr_robot_quotes.py" >> ~/.bashrc
source ~/.bashrc
```
# Customization
- To remove `MR ROBOT` ascii logo, remove below lines in `mr_robot_quotes.py`
```
with open(ascii_path) as ascii_file:
        print(ascii_file.read()
```
- To add or remove quotes, change `/data/quotes` file
# Credits
Inspired from [BobRossQuotes](https://github.com/kz6fittycent/BobRossQuotes)
