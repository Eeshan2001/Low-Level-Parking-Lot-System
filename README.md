# Low-Level-Parking-Lot-System
This repository gives an overview of how we can design a basic parking lot in Python. It creates parking lot with given number of slots. The cars follow Greedy approach while being parked in the slots.

LowLevel_ParkingSystem.py script defines the following functions -
1. `create_parking_lot n` - Given n number of slots, create a parking lot
2. `park car_number car_color` - Parks a vehicle with given registration number and color in the nearest empty slot possible. If there are no more empty slots available, it shows a message "Sorry, parking lot is full".
3. `status` - Prints the slot number, registration number and color of the parked vehicles.
4. `leave x` - Removes vehicle from slot number x
5. `check_car_number_with_carcolor car_color` - this will display All car number with same color
6. `check_slot_number_with_carcolor car_color` - this will display All filled slots with same color
7. `check_slot_number_with_carno car_no` - this will display slot alloted to car_number

LowLevel_ParkingSystem.py can be run through shell or through file containing test cases. 
Vehicle.py is a separate class where we can define the type of vehicles that can be parked. it only contains class `Car`
An example file `run_test_case.txt` has been provided in repo.
To run with a file execute `python LowLevel_ParkingSystem.py -f run_test_case.txt`   

![Screenshot (461)](https://user-images.githubusercontent.com/80475016/156886639-a1a6ab12-f005-4282-8d65-fea93c7acec3.png)
