## Plates - Restaurant - Customers/Guest

**group_names** *{"Chase" 3, "Smith" => 2, "Floyd" => 1, "Lovers" => 6}*
**total_orders** *(12)*
**ordered** *(true)*
**eating** *(true)*
**waiting_on_check** *(true)*
**average_meal_time** *(25.5)*
**waiting_list** *("Walt", "Carrie", "Justin", "Victor")*
**reservations** *("Jack","Allen","Prince Henry")*
**amount_of_reservations** *(3)*
**more_guests** *(0)*


## Methods

**wait_time** *This calculates what the waiting time is for Customers who would like to wait for a table*
```ruby
(average_meal_time * (waiting_list + amount_of_reservations))
```

**maximum_guests** *This calculates if there is room for anymore Customers/guests*
```ruby
if amount_of_reservations > 25
  p "No more guests"
else
  p 25 - amount_of_reservations = more_guests
  p "#{more_guests} more spots available for seating!"
end
```

**seating_available** *This uses the more_guests variable to calculate the seating_available*
```ruby
if more_guests > 0
  p "#{more_guests} are available"
else
  p "Sorry no available today"
end
```
**ready_to_clear** *This notifies the waiter that the table is done eating and ready to be cleared*
```ruby
if eating == true
  ready_to_clear = false
  p "Ready to be cleared:"
  p ready_to_clear
elsif eating == false
  ready_to_clear = true
  p "Ready to be cleared:"
  p ready_to_clear
end
``
