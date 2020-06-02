專案的目標？To desing an algorithm to conquer Chinese ancient game -- GO. 

使用的技術是？ A tree that contain two deep neural networs(policy net work & value network). The policy neural network will predict the next move and will also narrow the search to consider only the moves most likely to lead to a win. The value network is used to reduce the depth of the search tree. It estimates the winner in each position in place of searching all the way to the end of the game.

資料來源？30 millions moves from games played by human experts.
