## Restaurant

### Class: Menu & Prices

**Diner_Name** *(string)*
**breakfast** *(hash)*
**lunch** *(hash)*
**dinner** *(hash)*
**specials** *(hash)*
**morning** *(boolean)*
**midday** *(boolean)*
**evening** *(boolean)*


##Methods

**breakfast_menu_available**
```ruby

if morning == true
  p "Morning Menu is available! Good Morning All!"
else
  p "Morning Menu is only available before 11am!"
end

```

**lunch_menu_available**
```ruby

if midday == true
  p "Lunch Menu is available! Good Morning All!"
else
  p "Lunch Menu is only available from 11am - 4pm!"
end

```

**dinner_menu_available**
```ruby

if evening == true
  p "Evening Menu is available! Good Morning All!"
else
  p "Evening Menu is only available from 4pm - 8pm!"
end

```

**specials_menu_available**
```ruby
if evening == true
p "Specials Menu is available! Good Morning All!"
else
p "Sorry, Specials are only available during Evening hours 4pm - 8pm!"
end
```
