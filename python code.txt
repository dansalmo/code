import datetime
now = datetime.datetime.now()
print"current date:"
print str(now)
print "Current date:"
print "Current day: %d" % now.day
print now.strftime("%d")
from datetime import date
oldDate = date(2013,01,11) # year, month
dayofWeek = ['Monday', 'Tuesday', 'Wednesday', 'Thursday', 'Friday', 'Saturday', 'Sunday']
print "The day of the week on %s was a %s" % (oldDate.strftime("%d%b%Y"), dayofWeek[date.weekday(oldDate)])
if dayofWeek[date.weekday(oldDate)]==['Saturday','Sunday']:
    print "Hurray!"
elif dayofWeek[date.weekday(oldDate)]=='Friday':
    print"Start getting happy :) its about to be a weekend "
else:
    print"Get back to work"
