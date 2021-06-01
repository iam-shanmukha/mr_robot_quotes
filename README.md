# mr_robot_quotes
A bunch of Mr. Robot Quotes in Terminal

![mr_robot_quotes](https://user-images.githubusercontent.com/50124557/120297907-2f326d80-c2e7-11eb-9342-5f0613df66fa.png)

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
# Contribution
- Add your favorite quote to `/data/quotes` file and give a pull request
# Credits
Inspired from [BobRossQuotes](https://github.com/kz6fittycent/BobRossQuotes)
