# base6666662d
Running a Real-Time Event Listener for Base Logs Python:
event_filter = contract.events.Transfer.createFilter(fromBlock="latest")
while True:
    print(event_filter.get_new_entries())
