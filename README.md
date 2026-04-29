# Project #1: Dukan Inventory Manager
items = {
    "atta": 150,
    "chini": 120,
    "daal": 250
}

print("--- Dukan Search System ---")
search = input("Kaunsa saman check karna hai? ").lower()

if search in items:
    print(f"{search.capitalize()} ki qeemat Rs.{items[search]} hai.")
else:
    print("Ye saman list mein nahi hai.")
