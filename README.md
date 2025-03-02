#To calculate the total stock amount in the cafe
menu = ["coffee", "tea", "muffin", "sandwich"]

stock = {
  "coffee": 100,
  "tea": 95,
  "muffin": 110,
  "sandwich": 50
}

price = {
  "coffee": 26.00,
  "tea": 21.00,
  "muffin": 22.5,
  "sandwich": 23.3
}

total_stock_worth = 0
for item in menu:
  item_value = stock[item] * price[item]
  total_stock_worth += item_value

print("The total stock worth is: ", total_stock_worth)

