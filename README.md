# TE.AI.2024.SPPU
AI practicals

def vacuum_agent(location, status):
    if status == "Dirty":
        return "Suck"
    elif location == "A":
        return "Move Right"
    else:
        return "Move Left"

location = input("Enter vacuum location (A/B): ")
status = input("Enter room status (Clean/Dirty): ")

action = vacuum_agent(location, status)

print("Location:", location)
print("Room Status:", status)
print("Agent Action:", action)
