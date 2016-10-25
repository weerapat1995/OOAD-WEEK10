# OOAD-WEEK10
Sequence Diagram

### Sequence Diagram_1

Code

```
actor Customers
"Customers"->"Shop owner":Buy
"Shop owner"->"Book Sales":"Record sales"
"Customers"->"Shop owner":Pay
"Customers"<-"Shop owner":Receipt
"Shop owner"->"Stock":Edit Item
"Customers"<-"Shop owner":Product
```


Diagram

<img src="https://github.com/weerapat1995/OOAD-WEEK10/blob/master/HOMEWORK/Sequence1.png?raw=true">

###Sequence Diagram_2

Code

```
actor User
"User"->"Computer":Login
"User"->"Computer":"Get Print
"Computer"->"Printer":"Get Print"
"User"<-"Printer":"Print out"
```


Diagram

<img src="https://github.com/weerapat1995/OOAD-WEEK10/blob/master/HOMEWORK/Sequence2.png?raw=true">


###Sequence Diagram_3

Code

```
actor Passenger
"Passenger"->"Ticket vending machines":"Selected stations"
"Passenger"<-"Ticket vending machines":"How many people(1-5)"
"Passenger"->"Ticket vending machines":"Selected many people"
"Ticket vending machines"->"Ticket vending machines":"Calculate money"
"Passenger"<-"Ticket vending machines":"Prices"
"Passenger"->"Ticket vending machines":"Pay"
"Passenger"<-"Ticket vending machines":"Get token"
```

Diagram

<img src="https://github.com/weerapat1995/OOAD-WEEK10/blob/master/HOMEWORK/Sequence3.png?raw=true">


###Sequence Diagram_4

Code

```
actor Passenger
"Passenger"->"Reservation system":"Make resevation"
"Passenger"->"Reservation system":"Enter pin"
"Reservation system"->"Reservation manager":"Verify pin"
"Reservation system"<-"Reservation manager":"Valid"
"Passenger"<-"Reservation system":"Ask for destination"
"Passenger"->"Reservation system":"Destination"
"Reservation system"->"Reservation manager":"Destination"
"Reservation manager"->"Destination":"Show flight"
```


Diagram

<img src="https://github.com/weerapat1995/OOAD-WEEK10/blob/master/HOMEWORK/Sequence4.png?raw=true">


###Sequence Diagram_5

Code

```
actor Customer
"Customer"->"Auto Top Up":"Touch"
"Customer"<-"Auto Top Up":"Phone company?"
"Customer"->"Auto Top Up":"Selected phone company"
"Customer"<-"Auto Top Up":"Prices"
"Customer"->"Auto Top Up":"Selected Prices"
"Customer"->"Auto Top Up":"Pay"
"Customer"<-"Auto Top Up":"Massege Thank you"
```

Diagram

<img src="https://github.com/weerapat1995/OOAD-WEEK10/blob/master/HOMEWORK/Sequence5.png?raw=true">

