# rohit-demo
This is my first repo
<br>
Author--rohit tiwari

def process():
    average = {"Bus":10,"Car":20,"Bike":40,"Truck":8}
    petrol=105
    Diesel=70
    x =int(input("Write your vehicle type \nBus=1\nCar=2Bike=40\nTruck=80\n"))
    y=input("write your fuel mode'Petrol' or 'Diesel'")
    amount=int(input("Enter Amount"))
    match x:
        case 1 if y=="petrol":
            fuel=amount/petrol
            print("Amount of fuel",fuel)
            print(f"your vehicle will run upto,{fuel*10}km")
        case 1 if y=="Diesel":
            fuel2=amount/Diesel
            print("Amount of fuel ",fuel2)
            print ("Average of your vehicle id",fuel2*average["Bus"])
        case 2 if y=="petrol":
            fuel1=amount/petrol
            print("Amount of fuel",fuel1)
            print(f"your vehicle will run upto,{fuel1*20}km")
        case 2 if y=="Diesel":
            fuel2=amount/Diesel
            print("Amount of fuel ",fuel2)
            print ("Average of your vehicle id",fuel2*average["Bus"])
        case 3 if y=="petrol":
            fuel1=amount/petrol
            print("Amount of fuel",fuel1)
            print(f"your vehicle will run upto,{fuel*40}km") 
        case 4 if y=="petrol":
            fuel=amount/petrol
            print("Amount of fuel",fuel)
            print(f"your vehicle will run upto,{fuel*8}km")
        case 4 if y=="Diesel":
            fuel2=amount/Diesel
            print("Amount of fuel ",fuel2)
            print ("Average of your vehicle id",fuel2*average["Bus"]) 
process()