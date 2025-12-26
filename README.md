# daily_update.p
import datetime
import random

print("Daily GitHub activity - Day 40")

today = datetime.date.today()

# Generate random battery percentages and analyze
battery_levels = [random.randint(10, 100) for _ in range(6)]
low_battery = [b for b in battery_levels if b < 30]

print(f"Today's date: {today}")
print("Battery levels:", battery_levels)
print("Lowest level:", min(battery_levels))
print("Highest level:", max(battery_levels))
print("Devices with low battery (<30%):", len(low_battery))

