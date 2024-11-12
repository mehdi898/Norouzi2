import random
starting_money = 1000
bet_amount = 50
probability_win = 0.5
current_money = starting_money
rounds = 0
while current_money > 0:
    rounds += 1
    if random.random() < probability_win:
        current_money += bet_amount
    else:
        current_money -= bet_amount
    print(f"Round {rounds}: Money = {current_money}")
print("\nThe gambler is bankrupt!")
print(f"Total rounds played: {rounds}")