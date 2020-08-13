usernumberofseconds = int(input("Enter the number of seconds :"))

days = int(usernumberofseconds / 86400)
hours = int((usernumberofseconds % 86400) / 3600 )
minutes = int(((usernumberofseconds % 86400) % 3600 ) / 60)
seconds = int(((usernumberofseconds % 86400) % 3600 ) % 60)

print( str(days) + "day(s)", str(hours) + "hour(s)", str(minutes) + "minute(s)", str(seconds) + "second(s)")
