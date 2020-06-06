## Restaurant

### Class: Menu & Prices

**Diner_Name** *(Wak'n Bac'n)*
**breakfast** *("Three Eggs" => 4.20,"Eggs & Toast" => 5.50,"Pancakes and Two Eggs" => 6.75,"Omelette Breakfast Sandwich with Milk Pancakes or Waffles" => 10.20)*
**lunch** *("Brunch Crunch" => 4.20,"Hot Noodles" => 5.50,"Southern Pulled Pork" => 6.75,"Lean Machine" => 10.20)*
**dinner** *("Wild Bac'n Pasta" => 4.20,"Breakfast for Dinner" => 5.50,"Chicken Salad" => 6.75,"Steak Dinner" => 10.20)*
**specials** *("Bison Pasta" => 7.20,"Hawaiian Surprise" => 9.50,"Soup of The Day" => 6.75,"Sampler" => 15.20)*
**morning** *(false)*
**midday** *(false)*
**evening** *(true)*


##Methods

**breakfast_menu_available** *Method that allows breakfast to be ordered*
```ruby
if morning == true
  p "Wak'n Bac'n Morning Menu is available! Good Morning All!"
else
  p "Wak'n Bac'n Morning Menu is only available before 11am!"
end
```

**lunch_menu_available** *Method that allows lunch to be ordered*
```ruby
if midday == true
  p "Wak'n Bac'n Lunch Menu is available! Good Morning All!"
else
  p "Wak'n Bac'n Lunch Menu is only available from 11am - 4pm!"
end
```

**dinner_menu_available** *Method that allows lunch to be ordered*
```ruby
if evening == true
  p "Wak'n Bac'n Evening Menu is available! Good Morning All!"
else
  p "Wak'n Bac'n Evening Menu is only available from 4pm - 8pm!"
end
```

**specials_menu_available** *Method that allows specials to be ordered*
```ruby
if evening == true
p "Wak'n Bac'n Specials Menu is available! Good Morning All!"
else
p "Sorry, Wak'n Bac'n Specials are only available during Evening hours 4pm - 8pm!"
end
```
