# TableView with rxSwift
Applying rxSwfit on tableview in various situations

There are several ways to develope tableview with rxSwfit.

This one is one of the way, not the answer you must follow.


## Example 1. Showing data on tableview cell
<center><img src="./images/example1.png" width="100" height="100"></center>

- Showing fruit name and image on tableview.
- Data: BehaviorRelay
- Binding data on tableview with Rxswift

## Example 2. Get data from cell textfield
![example2_1](./images/example2_1.png){: width="100" height="100"}

![example2_2](./images/example2_2.png){: width="100" height="100"}

과일 치면(textfield) 이미지 보여주기

## Example 3. Treat button event from tableview cell 
![example3](./images/example3.png){: width="100" height="100"}

disposed bag 을 cell에다가 해주고나서
table view 밖에서 cell.bag을 해서 처리해주어야 한다.
왜 이렇게 하는지는 모르겠는데... 어쨌든 미션 클리어ㅠㅠ
