```
@startuml
user -> ATM : InsertCard()
user -> keypad : Input(PIN)
keypad -> ATM : [invalid pin] Warning()
ATM -> Monitor : [invalid pin] Display()
Monitor -> ATM :[Invalid pin] StopService()
Monitor -> ATM :[Valid pin] ContinueService()
ATM -> Monitor : DisplayMainMenu()

user -> keypad : Check(balance)
ATM -> Account : CheckBalance()
account -> Monitor : ShowBalance()

@enduml
```
