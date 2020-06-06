## Restaurant - Customers/Guest

**group_names** *(array)*
**group_size** *(integer)*
**total_orders** *(float)*
**ordered** *(boolean)*
**eating** *(boolean)*
**waiting_on_check** *(boolean)*
**average_meal_time** *(float)*
**waiting_list** *(array)*
**reservations** *(array)*
**amount_of_reservations** *(integer)*
**more_guests** *(integer)*


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
else
  ready_to_clear = true
end
``
