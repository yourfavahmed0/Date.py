from datetime import datetime

# Get today's date
today = datetime.now()

# Format: YYYY-MM-DD
date_str = today.strftime("%2025-%7-%25")

# Print or use the date
print(f"Today's date is: {date_str}")